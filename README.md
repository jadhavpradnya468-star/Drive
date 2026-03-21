📁 Drive App - File Upload System

A simple Drive-like web application built using Node.js, Express, EJS, and MongoDB.
Users can register, login, and upload files securely just like a mini cloud storage system.

🚀 Features
👤 User Registration
Create a new account
🔐 User Login
Secure authentication system
📤 File Upload
Upload files (PDF or others)
📂 Drive-like Storage
Each user can manage their own files
🔒 Authentication & Authorization
Only logged-in users can upload and access files


🛠️ Tech Stack
Backend: Node.js, Express.js
Frontend: EJS Templates
Database: MongoDB + Mongoose
File Upload: Multer
Authentication: Express-session / JWT
Styling: CSS / Bootstrap (optional)

📦 Installation
Install dependencies:
npm install

Run the Application
Start the server:
node app.js


🌐 Access the App
Open your browser:

http://localhost:3000

📌 How It Works
1.Register
User signs up and data is stored in MongoDB

2.Login
User logs in with credentials

3.Upload File
Authenticated users upload files using Multer

4.Store Data
File info + user data stored in MongoDB

5.Access Files
Users can view their uploaded files

📁 Project Structure

Copy code
Drive
│
├── /uploads         # Uploaded files
├── /models          # Mongoose models
├── /routes          # Express routes
├── /views           # EJS templates
├── /public          # Static files
├── /config          # DB connection
├── app.js           # Main server
└── package.json

✨ Future Improvements
📥 Download files
🗑️ Delete files
📁 Folder system
☁️ Cloud storage (AWS S3 / Supabase)
🔍 Search files
🎨 Modern UI (React / Tailwind)
