# Practical 3: File Upload Implementation Reflection


Key Concepts Applied
Multipart Form Data Handling with FormData (frontend) and formidable (backend)

File Validation on both client and server for type and size

Upload Progress Tracking using Axios onUploadProgress

Drag and Drop Interface powered by react-dropzone

Form State Management via React Hook Form

Major Learnings
File upload requires multiple layers: validation, security, feedback, and error handling

Client-side validation improves UX; server-side validation enforces security

Proper state management is key for responsive UI and error handling

API design needs to handle errors clearly and comply with REST principles

Challenges & Solutions
Disabled Next.js body parser to handle multipart uploads properly

Synchronized validation rules between client and server to avoid user confusion

Improved upload progress feedback for better user perception

Categorized error messages for clear user guidance

Managed drag state carefully to avoid UI glitches

Takeaways
Prioritize user experience in every technical decision

Security must be integrated from the start

Clear, specific error messages enhance usability

Testing edge cases is essential for robust uploads

Good documentation supports future maintenance

Future Improvements
Add testing (unit and integration)

Optimize performance with compression and chunked uploads

Enhance security with virus scanning

Improve UX with image previews and upload queues

Scale with cloud storage and CDN support


