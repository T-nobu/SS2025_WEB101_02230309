# Practical 1 Reflection: TikTok Clone 🚀

## 🧠 What I Built & Learned

I developed a TikTok-style frontend app using **Next.js (App Router)**, **React**, **Tailwind CSS**, and **React Hook Form**. This project helped me dive into modern frontend architecture, responsive design, and form management.

### 🔄 Modern App Structure
- Used **Next.js App Router** for file-based routing and layout organization.
- Combined **server and client components** for better performance.
- Created a clean folder structure using `src/app/`, `components/`, and `lib/`.

### 🧩 Component-Based Design
Built modular and reusable UI:
- `MainLayout.jsx`: Shared sidebar/header layout
- `VideoCard.jsx` & `VideoFeed.jsx`: Scrollable content cards
- Separate pages for login, signup, upload, profile, etc.

### 📝 Smart Form Handling
Used **React Hook Form** to:
- Register input fields and validate them
- Display real-time error messages
- Match passwords using custom logic
- Show loading states on submit

```js
confirmPassword: {
  required: "Please confirm your password",
  validate: (value) => value === password || "Passwords do not match"
}
💡 Insights & Future Plans
What I’d Do Next:
Add TypeScript for type safety

Use Redux/Zustand for shared state

Connect to a real backend

Add unit tests and integration tests

Improve accessibility (ARIA, keyboard nav)

Optimize with lazy loading and code splitting

📌 Final Thoughts
This project gave me hands-on experience with modern full-stack-ready frontend tools. I saw how Next.js, React, Tailwind CSS, and React Hook Form all work together smoothly.

Most valuable takeaway: Good architecture, reusable components, and clear validation logic make apps scalable and user-friendly.