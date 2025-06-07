# Practical 4: Connecting TikTok Frontend to Server


Overview
This practical shows how to link a Next.js frontend with an Express.js backend. The app includes user login, video display, and social features like following and commenting, similar to TikTok.

Requirements
Node.js installed

Next.js frontend ready

Express.js backend setup

Basic knowledge of React, APIs, and JWT authentication

Installation
Packages to Install
Run this command to add needed libraries:

bash
Copy
Edit
npm install axios jwt-decode react-hot-toast
Implementation Steps
1. Set Up API Client
Create an Axios instance with the backend URL

Add interceptors to handle auth tokens and errors

Set environment variable in .env.local:

bash
Copy
Edit
NEXT_PUBLIC_API_URL=http://localhost:8000/api
2. Manage Authentication State
Create a React context to hold login info

Handle login and logout actions

Wrap the app with AuthProvider for global access

3. Build Authentication UI
Create reusable modal and form components

Add validation and error handling

Connect forms to backend login/signup APIs

4. Update Main Layout
Show different buttons based on login status

Protect certain pages for logged-in users only

5. Video Service
Write functions to get videos, like, and comment

Centralize video-related API calls

6. User Service
Handle user profiles, follow/unfollow actions

Support user search and discovery

7. VideoCard Component
Display individual videos with info

Support real-time likes, comments, and video controls

8. VideoFeed Component
Fetch and show video lists ("For You" and "Following")

Show loading states and handle errors

9. Following Page
Show videos only from followed users

Handle cases where no follows exist

10. User Discovery Page
Allow browsing and searching for users

Support follow/unfollow actions

11. Profile Page
Show user info and videos dynamically based on userId

12. Video Upload
Provide form to upload videos with captions and thumbnails

Validate files before sending

Main Features
JWT-based secure authentication

Video browsing, liking, commenting, and uploading

Social features like following and user discovery

Centralized API calls and error handling

How to Test
Register and log in with multiple users

Upload videos, add captions, and check playback

Follow and unfollow users, check personalized feeds

Like/unlike videos and test commenting

Verify UI changes based on login status and test navigation

Project Structure
css
Copy
Edit
src/
├── app/
│   ├── explore-users/
│   ├── following/
│   ├── profile/[userId]/
│   ├── upload/
│   └── layout.js
├── components/
│   ├── auth/
│   ├── layout/
│   └── ui/
├── contexts/
├── lib/
└── services/
Environment Variables
bash
Copy
Edit
NEXT_PUBLIC_API_URL=http://localhost:8000/api
Useful Links
Next.js Docs

React Hook Form

Axios

JWT Overview

Express.js Docs

Prisma ORM