# Practical 4: Connecting TikTok Frontend to Server Reflection

Main Concepts Used
Full-Stack Integration
Connected a Next.js frontend with an Express.js backend, showing how client and server communicate in modern web apps.

Authentication

Used JWT tokens for secure, stateless login

Managed login state globally with React Context

Stored tokens safely and added them to API requests automatically

Protected pages based on login status

API Client Setup

Configured Axios with interceptors for handling requests and errors

Organized API calls in separate service files

Used environment variables for backend URLs

State Management

Used React Context for global authentication state

Managed form and UI states locally

Handled loading and error states during API calls

Component Structure

Built reusable UI components like modals and forms

Kept UI, logic, and API calls separated clearly

Passed data correctly through props and state

Social Features

Created "For You" and "Following" video feeds

Enabled likes, comments, follow/unfollow

Supported live UI updates and file uploads

What I Learned
Technical Skills
How to integrate REST APIs with React

Managing authentication tokens securely

Using React Context and custom hooks

Designing protected routes

Handling frontend-backend data flow

Concepts
Good software architecture with separation of concerns

Designing smooth user experiences with loading and error feedback

Importance of client-side and API security

Challenges and How I Solved Them
CORS Issues
API requests were blocked due to CORS errors.
Solution: Configured CORS middleware on backend to allow frontend access.

Authentication State Lost on Refresh
Users were logged out after refreshing.
Solution: Saved tokens in localStorage and reloaded them on app start.

Inconsistent API Error Handling
Some errors didn’t show properly and caused crashes.
Solution: Centralized error handling in Axios with user-friendly messages.

Complex State Management
Props were passed down too many levels, making state hard to track.
Solution: Used React Context and custom hooks to simplify state flow.

File Upload Problems
Large videos failed or took too long to upload.
Solution: Added file size validation, progress indicators, and adjusted timeouts.

Key Takeaways
Clear architecture makes development easier and faster.

Good UX needs proper loading states and error messages.

Security must be planned throughout the app.

Testing with multiple users is essential for social features.

Well-written documentation helps future development.

Future Improvements
Add lazy loading and caching for better performance.

Build real-time notifications and advanced search.

Write automated tests for components and API flows.

Enhance security with refresh tokens and rate limiting.

Conclusion
This practical taught me how to build a full-stack app with a secure login system, video features, and social interactions. Overcoming challenges improved my skills in error handling, state management, and user experience. The project gave me solid experience in combining frontend and backend technologies, preparing me for bigger full-stack projects ahead.