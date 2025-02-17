Overview

The Task Manager App is a simple and efficient task management system built with React and Firebase. It allows users to:

Authenticate using Google Sign-In

Add, edit, and delete tasks

Mark tasks as completed

Features

🔐 Google Authentication

✅ Task creation, editing, and deletion

🎯 Mark tasks as completed

☁️ Real-time database integration with Firebase

📱 Responsive design

Technologies Used

Frontend: React.js

Backend: Firebase Firestore (NoSQL Database)

Authentication: Firebase Authentication (Google Sign-In)

Hosting: Firebase Hosting (optional)

Installation & Setup

Clone the repository:

git clone https://github.com/YOUR_GITHUB_USERNAME/task-manager-app.git
cd task-manager-app

Install dependencies:

npm install

Set up Firebase:

Go to Firebase Console

Create a project and get your Firebase config values

Replace the placeholders in firebaseConfig inside TaskManager.js

Run the app:

npm start

Open http://localhost:3000 in your browser.

Firebase Configuration

Replace the placeholder values in the project with your Firebase credentials:

const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_AUTH_DOMAIN",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_STORAGE_BUCKET",
  messagingSenderId: "YOUR_MESSAGING_SENDER_ID",
  appId: "YOUR_APP_ID"
};

How to Use

Sign in using Google Authentication.

Add a new task by entering text and clicking "Add Task".

Mark tasks as completed by clicking "Complete".

Delete tasks if they are no longer needed.

Sign out when finished.# Task-Manager
