# 🧠 AI-Powered Mock Interview System

An advanced AI-based web application that simulates real-time technical interviews using AI agents. Built with React, Firebase, and Gemini AI, this tool helps users prepare for job interviews with personalized questions, voice interaction, feedback, and performance analytics.

---

## 🎯 Objective

To provide a realistic, interactive mock interview experience that enhances user confidence and readiness through dynamic AI-generated questions, voice analysis, and facial expression tracking — all within a browser-based platform.

---

## 🚀 Features

- 🗣️ **Speech-to-Text**: Users can answer questions verbally using their microphone.
- 🧑‍⚖️ **AI-Generated Questions**: Real-time, dynamic questions based on user-selected domains using Gemini Pro.
- 📸 **Webcam Capture**: Monitors facial expressions and non-verbal cues during interviews.
- 📊 **AI-Based Feedback**: NLP-powered evaluation of spoken answers with scoring and improvement tips.
- 🔒 **Secure Authentication**: User login and signup via Clerk authentication.
- 📂 **User Dashboard**: Review interview history and performance insights.
- 📁 **Data Storage**: Responses and feedback stored using Firebase Firestore.
- 🌐 **Web Deployment Ready**: Fully functional and deployed on free-tier hosting.

---

## 🧠 How It Works

1. User logs in securely via Clerk.
2. Selects a job role/domain (e.g., Full Stack Developer, Data Scientist).
3. AI generates personalized questions using Gemini Pro.
4. User answers through voice — speech is transcribed using Web Speech API.
5. AI evaluates the response using NLP and returns feedback with performance scores.
6. Interview history is saved for future review.

---

## 📦 Tech Stack

| Layer           | Technologies |
|------------------|--------------|
| 👨‍💻 Frontend      | React.js (Vite), Tailwind CSS |
| 🔙 Backend        | Node.js (for future extensibility) |
| 🔐 Authentication | Clerk |
| 🔮 AI Integration | Gemini Pro (via OpenAI or Google API) |
| 🔊 Voice Input    | Web Speech API |
| 📸 Webcam Input   | MediaDevices API |
| 🧠 NLP Analysis   | Gemini + JavaScript-based text processors |
| ☁️ Database       | Firebase Firestore |
| 🌐 Deployment     | Vercel / Netlify (Frontend) |

---

## 📷 Screenshots

| AI Question Generator | Live Interview Interface | Performance Feedback | Interview History |
|------------------------|--------------------------|-----------------------|--------------------|
| ![Question](https://github.com/GunjalaSiddartha/AI-Mock-Interview-System/blob/main/screenshots/question_gen.png) | ![Interview](https://github.com/GunjalaSiddartha/AI-Mock-Interview-System/blob/main/screenshots/interview_ui.png) | ![Feedback](https://github.com/GunjalaSiddartha/AI-Mock-Interview-System/blob/main/screenshots/feedback.png) | ![History](https://github.com/GunjalaSiddartha/AI-Mock-Interview-System/blob/main/screenshots/history.png) |

---

## 🛠️ Installation & Setup

```bash
# 1. Clone the repository
git clone https://github.com/GunjalaSiddartha/AI-Mock-Interview-System.git
cd AI-Mock-Interview-System

# 2. Install dependencies
npm install

# 3. Set up environment variables
# .env file (for Clerk, Gemini API keys, Firebase config)

# 4. Start the development server
npm run dev
