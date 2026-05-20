# 🎙️ Xena — Voice Assistant

A Python-based voice assistant built as our first coding project in B.Tech (Sem 1, Oct–Nov 2021). 
Xena listens to voice commands and responds with actions like playing music, 
telling the time, fetching Wikipedia summaries, and cracking jokes.

---

## 💡 Motivation

This was our team's first-ever Python project, built during the 1st semester of B.Tech 
Computer Science. We wanted to go beyond a basic console program and build something 
that actually *talks back*. Presented to faculty via Microsoft Teams and received 
positive feedback with a suggestion to extend it with a GUI — which is next on the roadmap.

---

## ⚙️ Features

- 🎵 **Play music** — say "Xena play <song name>" to play on YouTube
- 🕐 **Tell time** — say "Xena time" to hear the current time
- 📖 **Wikipedia search** — say "Xena who the heck is <person>" for a quick summary
- 😂 **Tell jokes** — say "Xena joke" for a random programmer joke
- 👥 **Know your owners** — say "Xena owner"

---

## 🛠️ Tech Stack

- Python 3
- SpeechRecognition — voice to text via Google Speech API
- pyttsx3 — text to speech (offline)
- pywhatkit — YouTube automation
- wikipedia — Wikipedia API wrapper
- pyjokes — random joke generator

---

## 🚀 How to Run

**1. Clone the repository**
```bash
git clone https://github.com/Aditya-Kumar-Sharma/Xena_myVoiceAssistant.git
cd Xena_myVoiceAssistant
```

**2. Install dependencies**
```bash
pip install -r requirements.txt
```

**3. Run Xena**
```bash
python xena.py
```

**4. Say "Xena" followed by your command**

---

## 📁 Project Structure
Xena_VoiceAssistant/
├── xena.py            # Main voice assistant logic
├── requirements.txt   # Python dependencies
└── README.md          # Project documentation
---

## 🔮 Roadmap

- [ ] Add Tkinter GUI to display commands and responses visually
- [ ] Add more commands (weather, calculator, reminders)
- [ ] Improve wake word detection accuracy

---

## 👥 Team

Built with ❤️ by a team of 4 first-year B.Tech students at Bennett University (2021)

- **Aditya Kumar Sharma** — Core development & feature implementation
- **Shivam** — Ideation & concept
- **Vikram** — Feature suggestions
- **Abhay** — Documentation & presentation

---

## 📝 Note

This was our very first Python project — built to explore real-world applications 
of Python beyond textbook exercises. It represents the starting point of our 
journey into software development.
