# Funny Friend : Yaymoji 🤖 — A Smart Emotion-Aware Companion [Google for developer 2025]

Welcome to Funny Friend Web – an emotion-aware AI companion that turns mood into action!  
Built for the Google Home API Developer Challenge 2025, this app combines laughter, empathy, Google map and smart home features – all inside your browser.

## 🎯 Live Demo
🔗 [Try the Web App on Render](https://funnyfriend-bs5j.onrender.com/)  
📽️ [Watch Full Demo Video on YouTube](https://youtube.com/your-demo-link)

---

## 🚀 Key Features (Browser App)

| Feature                          | Description                                                                 |
|----------------------------------|-----------------------------------------------------------------------------|
| 🎭 Emotion Detection             | Detects user emotion from text (via AI model)                              |
| 😂 Personalized Jokes            | Shows emotion-matched jokes from local + online sources                     |
| 🏥 Doctor & Help Nearby          | Find hospitals, spas, parks, etc. based on mood via Google Maps API         |
| 🗣️ Voice Chat                    | Talk to the assistant using voice (browser-based Speech Recognition + Speech Synthesis APIs).      |
| 🤖 Smart Home Control            | Controls light/fan using backend APIs (future-ready with Google Home)       |
| 🧠 LLM Chat                      | Uses OpenRouter AI to chat smartly based on your emotion                    |
| 🌐 Web Deployed                  | Runs directly in browser – no install needed                                |
| 🤝 Google Assistant Ready        | Full webhook/Dialogflow integration done (ready for smart speaker)          |

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

 🔄 Google Assistant integration via Dialogflow was not used due to webhook hosting limitations. Instead, we built a custom voice interaction system with full backend control, 
    offering more flexibility for real-world use.
 
---
## 🎬 Bonus: Future Vision Prototype

👉 In the YouTube demo, you’ll also see a sneak peek of our **future roadmap**:

🔗 **Backend-only Emotion + Video Chat . github link https://github.com/amritasinhayaymoji/funnyfriend_video.git

🎥 **Demo shows:**
- Live webcam emotion detection (via DeepFace)
- Backend-based LLM conversation
- Smart device control triggered by facial emotion
- All backend – future-ready for hardware / IoT integration

This version is not part of official submission, but reflects our longer-term ambition.
📷 Webcam-based emotion detection was excluded from the browser version due to privacy concerns and limited browser permissions. Instead, we focused on a lightweight and 
    secure user experience using text-based emotion input.
---
## ⚠️ Deployment Note

This project is deployed using **free-tier services only** (Render & GitHub). Due to these limitations:

- The app may show errors if free quota is exhausted.
- If the app is temporarily unavailable, you can **run it locally** using the instructions below.
- A full demo will also be available in the **submission video**.

No premium tools or paid services were used — this keeps the app lightweight, accessible, and cost-free to run and scale.

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



