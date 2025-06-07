# Practical 3: File Upload Implementation

✅ Main Features
Upload Files with drag-and-drop or file picker

Validate Files by type and size (max 5MB)

Track Upload Progress with a live progress bar

Support Multiple Files (up to 10 at once)

Responsive UI using Tailwind CSS

Error Handling for invalid files and failed uploads

⚙️ Tech Stack
Next.js for server-side routes

React Hook Form for form handling

React Dropzone for drag & drop

Formidable to parse form data on server

Axios to handle file uploads

Tailwind CSS for styling

🔐 Security
Checks file size/type on both frontend and backend

Creates unique filenames to avoid overwriting

Stores files outside public folder

Sends only safe error messages

🛠 Configuration
Change max file size or types in upload.js and frontend

Uploads go to /uploads folder

Use .env.local to manage upload path and limits

🧪 Test Scenarios
✅ Upload valid image or document

❌ Try uploading unsupported or large file → get error

🚫 Click upload without selecting file → shows warning

✅ Edit or delete works with simple clicks

🌐 Optional Enhancements
Add image preview before upload

Upload to cloud (e.g., AWS S3)

Add login to track user files

Enable file sharing and permissions

Resume broken uploads

Add virus scan before saving

