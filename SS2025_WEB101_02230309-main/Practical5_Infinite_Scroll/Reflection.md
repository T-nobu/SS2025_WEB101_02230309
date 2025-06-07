Practical 5 Reflection: Implementing Infinite Scroll 🤔
Key Concepts Applied
Cursor-Based Pagination
Uses a unique cursor instead of page numbers, making pagination efficient and consistent even when data changes. We implemented this on the backend with Prisma’s cursor queries and the n+1 pattern.

TanStack Query (React Query)
Leveraged useInfiniteQuery for easy infinite scrolling with built-in caching, loading, and error management.

Intersection Observer API
Efficiently detects when the user reaches the bottom of the feed, triggering new data loads without costly scroll event listeners.

Custom React Hook (useIntersectionObserver)
Encapsulates observer logic for reuse and cleaner code.

What I Learned
Cursor-based pagination offers better performance and reliability compared to offset-based pagination.

React Query’s infinite query hook simplifies managing loading states and caching.

Intersection Observer is a modern, efficient way to handle scroll-triggered actions.

Full-stack integration is key — backend and frontend must work closely for seamless pagination and error handling.

Challenges & Solutions
Understanding cursor logic: Used diagrams, debugging logs, and step-by-step implementation to grasp it.

Observer not triggering: Added margin, ensured element visibility, and verified refs.

Duplicate videos: Ensured unique keys and proper cursor handling, used React Query’s deduplication.

Loading feedback: Added clear loading indicators and "end of feed" messages.

Frequent refetching: Tuned staleTime and cacheTime, and monitored cache with DevTools.

Technical Insights
Optimized performance with lazy loading and caching strategies.

Improved user experience with progressive loading and error recovery.

Organized code with custom hooks and a clean service layer.

Future Improvements
Virtualization for very long lists (e.g., react-window).

Optimistic updates for smoother UI interactions.

Offline support with React Query’s offline-first mode.

Conclusion
This practical was invaluable for mastering modern infinite scroll techniques. Combining cursor-based pagination, TanStack Query, and Intersection Observer creates a smooth, scalable user experience like major platforms use. Debugging, full-stack thinking, and user-focused loading states were critical lessons. This foundation prepares me well for building efficient, real-world applications.

Takeaway: Building modern web apps requires balancing performance, UX, and scalability from the start — these tools and patterns help achieve that. 🌟