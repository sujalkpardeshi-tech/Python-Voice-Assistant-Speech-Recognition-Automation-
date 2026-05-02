# Python-Voice-Assistant-Speech-Recognition-Automation-
A desktop-based voice assistant built using Python that can recognize speech, perform web searches, fetch Wikipedia summaries, and open applications like Google and Instagram using voice commands. This project demonstrates integration of speech recognition, text-to-speech, and automation libraries.


## 📌 Overview
This project is a **Python-based Voice Assistant** that can listen to user commands, process them, and respond using speech output. It integrates **speech recognition, text-to-speech, and web automation** to perform real-time tasks.

The assistant can:
- Respond to greetings
- Search Wikipedia
- Open websites
- Perform Google searches

## 🚀 Features
- 🎤 Voice command recognition
- 🔊 Text-to-speech response
- 🌐 Open websites (Google, Instagram, YouTube)
- 📚 Wikipedia search with summary
- ⏱️ Time-based greeting system
- 🔎 Dynamic Google search for unknown queries

## 🛠️ Technologies Used
- Python
- pyttsx3 (Text-to-Speech)
- speech_recognition (Voice Input)
- wikipedia (Information Retrieval)
- webbrowser (Automation)
- datetime (Time-based logic)
- OS module


---

## ⚙️ How It Works

1. The assistant greets the user based on the time of day.
2. It listens to the user's voice command.
3. Converts speech into text using Google Speech API.
4. Executes commands based on keywords:
   - "Wikipedia" → Fetch summary
   - "Open Google" → Launch browser
   - "Open Instagram" → Open Instagram
   - Custom queries → Google search

---

## ▶️ Installation & Setup

### 1️⃣ Install dependencies
```bash
pip install pyttsx3 SpeechRecognition wikipedia
