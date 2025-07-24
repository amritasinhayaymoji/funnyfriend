# Funny Friend: Yaymoji 🤖 — A Smart Emotion-Aware Companion

Official Submission – Google for Developers API Challenge 2025

Welcome to Funny Friend Web — a voice-enabled, emotion-aware browser assistant that brings empathy, smart home control, and location help together.

This app is built for people who are elderly, alone, or unwell, and combines:

🧠 Emotion-aware chat (via voice + text)

🗣️ Voice assistant for accessibility

🏠 Uses Google Home API for smart device control (fan, AC, party mode, TV, etc.)

🗺️ Uses Google Maps API to suggest emotion-based locations (doctors, spas, parks, gyms)

Designed to work entirely in the browser, this version avoids complex system permissions — but still offers deep care, convenience, and connection through voice and empathy.

🚫 Note: Browser security doesn't allow webcam access, so real-time camera-based emotion/emergency detection is only in the Funny Friend Video Prototype, featured in the YouTube demo.

## 🎯 Live Demo
🔗 [Try the Web App on Render](https://funnyfriend-bs5j.onrender.com/)  
📽️ [Watch Full Demo Video on YouTube](https://youtube.com/your-demo-link)

---

## 🚀 Key Features (Browser App)

| Feature                        | Description                                                                                                  |
|-------------------------------|--------------------------------------------------------------------------------------------------------------|
| 🧠 Emotion Detection           | Detects user emotion from text input using a custom-trained AI model                                        |
| 😂 Personalized Jokes         | Serves jokes based on user emotion, fetched from both local dataset and OpenRouter AI                        |
| 🗺️ Emotion-Based Nearby Help | Finds hospitals, spas, gyms, and more using **Google Maps API** — personalized to your emotional state      |
| 🗣️ Voice Chat                 | Voice-enabled assistant using browser-based **Speech Recognition** and **Speech Synthesis** APIs             |
| 🏠 Smart Home Control         | Controls devices like light/fan using backend API — **Google Home API ready** for future real-world use      |
| 🤖 AI Chat (LLM)              | Smart, emotion-aware conversations powered by **OpenRouter AI**                                             |
| 🌐 Browser-Based              | Fully web-deployed, runs in any modern browser — no installation needed                                     |
| 📡 Google Assistant Ready     | Integrated with **Dialogflow Webhook** — supports smart speaker commands via **Google Assistant**            |

---

## 🧠 How It Works

1. User interacts via voice or text.
2. AI detects emotion using ML model.
3. Based on mood → shows jokes or nearby places.
4. User can talk further with the LLM or control home devices.
5. All responses are voice-enabled.

---

## 🛠️ Technologies Used

- Flask (Python backend)
- HTML/CSS/JavaScript (frontend)
- Bootstrap (mobile-first UI)
- OpenRouter LLM API
- Google Maps API
- Emotion detection (sklearn ML model)
- TTS / STT (browser-based)
- Dialogflow Webhook (Google Assistant integration)
- Hosted on Render

---

 🔄 Google Assistant integration via Dialogflow is fully implemented, but due to webhook hosting limitations on free-tier services, we also built a custom voice interaction system to ensure smooth, flexible use during real-world testing.

---
## 🎬 Bonus: Future Vision Prototype (Shown in Demo Video)

As part of our long-term vision, we’ve also built a backend-only prototype that brings Funny Friend closer to real-world smart devices and physical AI companions.

🔗 GitHub Repo: https://github.com/amritasinhayaymoji/funnyfriend_video.git

🎥 What’s Shown in the Demo:

🧠 Real-time emotion detection from live webcam 

🗣️ LLM-powered AI chat (via OpenRouter) triggered by your detected mood

💡 Smart home control (lights/fan) via backend commands

🎯 Runs fully in Python backend — designed for Raspberry Pi, IoT devices, and smart mirrors

⚠️ Note: This version is not submitted for the Google Home API Developer Challenge but is featured in the YouTube video to show what’s possible next.
---
## 📷 Why Not in Browser?

Webcam-based detection was not included in the browser version due to privacy concerns and strict browser limitations. Instead, we used secure, text-based emotion input to maintain accessibility and compliance.

---
## ⚙️ Deployment Note

This entire project is proudly built and deployed using only free-tier tools (Render, GitHub, open-source libraries). As a result:

The app may temporarily go offline if free quota is exceeded

All features are fully testable by running locally (see below)

A full demo is included in the YouTube video

💡 No premium tools were used — keeping the app lightweight, accessible, and free to use or scale.
With paid APIs (like GPT-4, Dialogflow CX, or cloud AI), the experience can be even smoother and smarter in production.

---

## 👩‍💻 Created By

Amrita Sinha
📧 Email: amritasinha.yaymoji@gmail.com

## 📦 Installation (for judges/testers)

```bash
git clone https://github.com/amritasinhayaymoji/funnyfriend.git
cd funnyfriend
pip install -r requirements.txt
python app.py
# Then open in browser: http://localhost:8000



