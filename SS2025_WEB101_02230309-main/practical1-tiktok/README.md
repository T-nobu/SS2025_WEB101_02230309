
# Practical 1: TikTok Clone

This is a simple TikTok-style web app built with **Next.js**, **React**, and **Tailwind CSS**. It covers core frontend development concepts like routing, component reuse, form handling, and responsive layouts.

---

## 🚀 Features

- TikTok-inspired layout with a sidebar menu
- Scrollable video feed with placeholders
- Navigation pages: For You, Following, Explore, Live, Profile
- User authentication with login and signup forms
- Mock video upload page
- Mobile-responsive interface

---

## 🛠 Technologies Used

- **Next.js 14+** – React framework with App Router
- **React** – For building UI components
- **Tailwind CSS** – For styling
- **React Hook Form** – Form validation and state
- **React Icons** – Icon library

---

## ⚙️ Getting Started

### Prerequisites

- Node.js (v14+)
- npm or yarn
- Git

### 1. Clone the Repository

```bash
git clone https://github.com/02240365/SS2025_WEB101_02240365.git
cd practical1-tiktok
```

### 2. Create the Next.js App

```bash
npx create-next-app@latest
```

Use these settings:
- TypeScript: No
- ESLint: Yes
- Tailwind CSS: Yes
- `src/` directory: Yes
- App Router: Yes

### 3. Install Dependencies

```bash
npm install react-icons react-hook-form
```

### 4. Start Development Server

```bash
npm run dev
```

Go to `http://localhost:3000` in your browser to view the app.

---

## 📁 Project Structure

```
src/
├── app/
│   ├── layout.js
│   ├── page.js
│   ├── globals.css
│   ├── profile/
│   ├── upload/
│   ├── login/
│   ├── signup/
│   ├── following/
│   ├── explore/
│   └── live/
├── components/
│   ├── layout/
│   └── ui/
├── lib/
```

---

## 🧩 Main Components

### `MainLayout.jsx`
- Sidebar navigation
- Top header with search/user actions
- Responsive design

### `VideoCard.jsx`
- Placeholder video with play/pause
- User info and interaction buttons

### `VideoFeed.jsx`
- Renders a list of VideoCards
- Scrollable feed container

---

## 📝 Forms

### Login Form (`/login`)
- Email/password validation
- Loading and error states

### Signup Form (`/signup`)
- Password confirmation check
- Terms and conditions checkbox
- Regex email validation

### Validation Highlights
- Required fields
- Password rules (min 8 chars)
- Custom error messages

---

## 🎨 Styling

Styled with **Tailwind CSS**:
- Mobile-first layout
- Dark mode ready
- Hover/focus effects
- Clean utility classes

---

## 🧭 Navigation Pages

- `For You`: Main feed (Home)
- `Following`: Followed users' content
- `Explore`: Discover content
- `Live`: Live video section
- `Profile`: User info
- `Upload`: Upload mockup
- `Login/Signup`: Auth pages

---

## 📌 Development Highlights

- Component-based architecture
- React hooks for local state
- Form handling with React Hook Form
- App routing with Next.js
- Fully responsive design

---

## ✅ Testing Tips

### Forms
- Submit empty form
- Try invalid email/password
- Test signup mismatches

### Navigation
- Click through all links
- Resize browser for mobile/desktop view

---

## 💡 Future Plans

- Add backend/API support
- Enable real uploads
- Add database integration
- Real-time features (e.g., comments)
- Auth system
- Video streaming

---

## 📚 Resources

- [Next.js Docs](https://nextjs.org/docs)
- [React Docs](https://reactjs.org/docs)
- [Tailwind CSS Docs](https://tailwindcss.com/docs)
- [React Hook Form Docs](https://react-hook-form.com/)
- [React Icons](https://react-icons.github.io/react-icons/)
