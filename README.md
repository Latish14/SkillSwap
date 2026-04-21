🚀 Community Skill Swap Platform

A simple web-based platform that allows users to exchange skills with each other through peer-to-peer learning and real-time communication.

📌 Project Overview

The Community Skill Swap Platform enables users to:

Share skills they can teach
Find people to learn from
Connect and communicate in real-time

This project focuses on collaborative learning without financial barriers, making skill development accessible to everyone.

✨ Features
👤 User Registration (username-based)
🧠 Add Skills (Teach & Learn)
🔍 Skill Matching System
💬 Real-Time Chat
🌐 Explore Other Users
⚡ Simple and Clean UI
🛠️ Tech Stack
Frontend: HTML, CSS, JavaScript
Backend: Firebase (Firestore)
Database: Cloud Firestore
Hosting: GitHub Pages / Vercel
⚙️ How It Works
User enters a username and adds skills
Data is stored in Firebase Firestore
Users can explore other profiles
Matching system suggests relevant users
Users can start real-time chat
🔥 Getting Started
1. Clone the repository
git clone https://github.com/yourusername/skillswap.git
cd skillswap
2. Setup Firebase
Go to Firebase Console
Create a project
Add a Web App
Copy your Firebase config

Replace this in index.html:

const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_PROJECT.firebaseapp.com",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_PROJECT.appspot.com",
  messagingSenderId: "YOUR_SENDER_ID",
  appId: "YOUR_APP_ID"
};
3. Enable Firestore
Go to Firestore Database
Start in Test Mode
4. Run the Project

Simply open:

index.html
🌍 Deployment

You can deploy the project using:

GitHub Pages
Vercel

After deployment, users can access the app via a public link.

⚠️ Note

Firestore rules are set to allow open access for demo purposes:

allow read, write: if true;

⚠️ Not recommended for production use.

🚀 Future Improvements
Video calling feature
Rating & feedback system
AI-based skill matching
Mobile application
📷 Demo

(Add screenshots here if needed)

👨‍💻 Author

Your Name
B.Tech CSE (Data Science)

📜 License

This project is for academic purposes.
