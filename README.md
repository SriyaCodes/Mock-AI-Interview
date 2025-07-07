# 🎤 Mock AI Interview Platform

A web-based platform that simulates real-time interviews using AI. It generates intelligent questions, records user responses via audio/video, evaluates them instantly, and provides detailed feedback — just like a real interviewer, but smarter and always available!

🌐 **Live Demo**: [https://intelliview-frontend.onrender.com/](https://intelliview-frontend.onrender.com/)

---

## 🚀 Features

- 🤖 **AI-Driven Interview Simulation**  
  Dynamic questions based on topic & difficulty using Groq LLM.

- 🎥 **Audio & Video Capture**  
  Record responses with your webcam & mic via WebRTC + MediaRecorder.

- 🗣️ **Speech Transcription**  
  Converts spoken answers to text using OpenAI's Whisper.

- 📊 **Real-Time Evaluation**  
  Feedback on:
  - Grammar & clarity  
  - Answer accuracy  
  - Confidence & tone  
  - Emotions (via Google MediaPipe)

- 📈 **Instant Scoring & Feedback**  
  Get your performance score, improvement tips, and past history.

- 🔐 **Secure Auth**  
  JWT-based login & protected sessions.

---

## 🧭 How It Works

1. **Sign Up / Login**  
2. **Start Interview** – Questions are generated on the fly  
3. **Respond** – Record audio/video answers  
4. **Get Evaluated** – Real-time AI feedback  
5. **Track History** – View past sessions anytime

---

## 🛠️ Tech Stack

- **Frontend:** React.js  
- **Backend:** Node.js + Express  
- **Database:** MongoDB  
- **Speech-to-Text:** Whisper  
- **NLP:** Groq LLM API  
- **Facial Analysis:** Google MediaPipe  
- **Auth:** JWT

## 📮 Feedback / Contributions

Found a bug? Got an idea? PRs are welcome!  
Let's build the future of mock interviews together. 🤝

---

© 2025 IntelliView.
