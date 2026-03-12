# CodeConnect – Real-Time Collaborative Coding Platform

CodeConnect is a **browser-based collaborative coding platform** that allows multiple developers to write, edit, and run code together in real time.

It provides a shared coding environment with **live synchronization, chat, terminal output, and multi-language support**.

---

## Features

- Real-time collaborative code editing
- Multi-user coding rooms
- Built-in terminal output
- Room chat for communication
- Multi-language support (C/C++, Java, Python, JavaScript)
- Project dashboard
- Secure authentication system

---

## Tech Stack

**Frontend**
- React.js
- Vite
- Monaco Code Editor

**Backend / Services**
- Supabase
- Firebase Authentication
- Ably Real-time Messaging

**Tools**
- Node.js
- npm
- Git

---

# Screenshots

## Home Page

<p align="center">
<img src="screenshots/homepage.png" width="900">
</p>

---

## Create / Join Room

<p align="center">
<img src="screenshots/create-room.png" width="500">
</p>

---

## Collaborative Coding Environment

<p align="center">
<img src="screenshots/room-interface.png" width="900">
</p>

---

# Installation Guide

Follow the steps below to run the project locally.

---

## Step 1: Clone the Repository


git clone https://github.com/your-username/codeconnect.git


Navigate to the project folder:


cd codeconnect


---

## Step 2: Install Dependencies


npm install


---

## Step 3: Setup Environment Variables

Create a `.env` file in the root directory.


VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_ANON_KEY=your_supabase_key

VITE_FIREBASE_API_KEY=your_firebase_api_key
VITE_FIREBASE_AUTH_DOMAIN=your_firebase_auth_domain

VITE_ABLY_API_KEY=your_ably_api_key


---

## Step 4: Run the Application


npm run dev


---

## Step 5: Open the Application

Open your browser and go to:


http://localhost:5173


---

# How to Use

1. Open the website.
2. Sign in to your account.
3. Click **Create / Join Room**.
4. Generate a Room ID or enter an existing room.
5. Share the link with collaborators.
6. Start coding together in real time.

---

# Build for Production


npm run build


Preview production build:


npm run preview


---

# Future Improvements

- Add video collaboration
- Add AI coding assistant
- Add project version control
- Improve terminal execution support

---

# Author

**Srujan Surya**

Computer Science Engineer  
Full Stack Developer

LinkedIn  
https://www.linkedin.com/in/srujan-surya-494439287
