# Practical 5: Implementing Infinite Scroll 📱

## Overview
This practical added infinite scrolling to a TikTok-like app using TanStack Query with cursor-based pagination for smooth, endless content loading.

## Key Concepts

### Cursor-Based Pagination vs Offset-Based
- **Offset-based** uses page numbers and limits but struggles with large or changing data.
- **Cursor-based** uses unique IDs to fetch the next set, making it efficient and reliable for infinite scrolling.

### TanStack Query Benefits
- Built-in infinite scroll support
- Automatic pagination and caching
- Easy error and loading state management

### Intersection Observer API
- Efficiently detects when user scrolls near the bottom
- Triggers loading more content without heavy scroll listeners

## Implementation Highlights

### Backend
- Updated video controllers to support cursor & limit params
- Used Prisma’s `cursor` and `skip` for pagination
- Returned `nextCursor` and `hasNextPage` info for frontend

### Frontend
- Installed TanStack React Query and set up QueryClient
- Created video fetching services supporting cursor param
- Built a custom Intersection Observer hook to detect scroll position
- Used `useInfiniteQuery` to load videos page by page
- Displayed loading spinners and "end of list" message

## Key Takeaways

- Cursor-based pagination is better for infinite scroll with dynamic data.
- React Query simplifies handling pagination, caching, and errors.
- Intersection Observer is a clean, performant way to detect scroll position.
- Proper backend support is essential for smooth infinite scrolling.

## Testing Tips
- Verify videos load initially and on scroll
- Check loading indicators and error handling
- Ensure no duplicates and smooth user experience on slow networks

## Performance Tips
- Use React Query caching wisely
- Consider virtualization for very long lists
- Optimize components with memoization

## Useful Links
- [TanStack Query Docs](https://tanstack.com/query/latest)
- [Intersection Observer API](https://developer.mozilla.org/en-US/docs/Web/API/Intersection_Observer_API)
- [Prisma Cursor Pagination](https://www.prisma.io/docs/concepts/components/prisma-client/pagination)
- [Next.js App Router](https://nextjs.org/docs/app)
