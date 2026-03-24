# 🎙️ CompanioAI – AI Voice Companion

> A real-time, bilingual AI voice assistant that understands and responds naturally in **Urdu and English**.

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=flat-square&logo=python)
![Whisper](https://img.shields.io/badge/OpenAI-Whisper-green?style=flat-square)
![AI](https://img.shields.io/badge/AI-Powered-orange?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-lightgrey?style=flat-square)

---

## 📌 Overview

**CompanioAI** is a voice-based AI companion designed for seamless, natural conversations. It listens to the user, detects the language in real time, processes speech using Whisper, and generates intelligent responses — making it feel like talking to a real assistant.

Whether you need help with tasks, reminders, quick answers, or just want to have a conversation, CompanioAI is always ready.

---

## ✨ Features

- 🎤 **Real-Time Speech Recognition** – Powered by OpenAI Whisper
- 🌐 **Bilingual Support** – Understands and responds in both Urdu and English
- 🧠 **AI Response Generation** – Context-aware, intelligent replies
- 🔔 **Reminders & Task Help** – Set reminders and get task assistance via voice
- 💡 **Proactive Suggestions** – Offers smart suggestions based on conversation context
- 🔄 **Language Detection** – Automatically detects and switches between languages

---

## 🛠️ Tech Stack

| Component | Technology |
|-----------|------------|
| Speech Recognition | OpenAI Whisper |
| Language Detection | LangDetect / custom NLP |
| AI Response | OpenAI GPT / LLM API |
| Text-to-Speech | gTTS / pyttsx3 |
| Backend | Python 3.10+ |
| Audio Processing | PyAudio / SoundDevice |

---

## 🚀 Getting Started

### Prerequisites

```bash
Python 3.10+
pip
ffmpeg (for Whisper audio processing)
```

### Installation

```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/CompanioAI.git
cd CompanioAI

# Install dependencies
pip install -r requirements.txt

# Set up environment variables
cp .env.example .env
# Add your OpenAI API key to .env
```

### Run the App

```bash
python main.py
```

---

## 📁 Project Structure

```
CompanioAI/
├── main.py               # Entry point
├── speech/
│   ├── recognizer.py     # Whisper speech-to-text
│   └── synthesizer.py    # Text-to-speech output
├── ai/
│   ├── language_detect.py # Language detection
│   └── responder.py       # AI response generation
├── utils/
│   └── reminders.py       # Reminder & task logic
├── requirements.txt
└── .env.example
```

---

## 🌍 Use Cases

- Personal voice assistant for daily tasks
- Multilingual customer support prototype
- Accessibility tool for non-English speakers
- Voice-controlled smart home integration base

---

## 📸 Demo

> _Voice interaction demo coming soon._

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

---

## 📄 License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.

---

## 👤 Author

**Arslan Akif**  
CS Student | Python Developer | AI Enthusiast  
📧 arslanakif2004@gmail.com
