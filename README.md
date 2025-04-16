# 🌙 L.U.N.A. - Logical Universal Networked Assistant

![LUNA Banner](Frontend/Graphics/logo.gif)

## 🌟 Overview
LUNA is an advanced, AI-powered voice assistant designed to interact with you naturally and intelligently. From answering questions and retrieving real-time data to automating your system tasks and analyzing your screen, LUNA serves as your personal digital companion—always ready to help.

Built with a hybrid architecture, LUNA intelligently balances cloud-based services and local system integration to offer fast, privacy-conscious, and accurate responses. Whether you're a developer, student, content creator, or just someone who loves AI, LUNA is designed to enhance your digital experience. It operates through seamless voice commands, understands complex instructions, adapts to your preferences, and can even engage in meaningful conversations.

Use it as a hands-free assistant while working, a productivity booster for automation tasks, or a fun companion for AI-powered interactions. LUNA is flexible, extensible, and tailored to be your AI ally.

## 🤖 What is LUNA?
**L.U.N.A. (Logical Universal Networked Assistant)** is a versatile, conversational AI assistant capable of:
- Holding fluid, human-like conversations
- Executing system commands
- Searching the web and retrieving information
- Controlling media and applications
- Performing image generation and visual analysis

LUNA is built to be more than just an assistant—it's your interface to seamless human-computer interaction.

LUNA addresses these with a hybrid local-cloud architecture, customizable workflows, and an emphasis on privacy and extensibility.

## ✨ Features
- **🎙️ Voice Interaction** – Engage with LUNA using natural speech
- **🧠 Intelligent Task Classification** – Understands if your request needs online data, offline action, or a combination
- **🖥️ System Control** – Launch or close apps, type text, adjust settings
- **🔍 Web Search** – Fetches real-time results using multiple APIs
- **🎵 Media Playback** – Plays music, videos, and online content
- **🖼️ Image Generation** – AI-generated images from user prompts
- **💬 Dynamic Conversations** – Maintains coherent multi-turn dialogue
- **👁️ Screen Analysis** – Describes what's happening on screen
- **📷 Camera Input Analysis** – Detects and interprets webcam visuals

## 🛠️ Tech Stack
- **Frontend**: PyQt5
- **Backend**:
  - **NLP & LLM**: Groq, Cohere APIs
  - **Vision AI**: Google Gemini
  - **Speech**: Web Speech API, Edge TTS
  - **Automation**: Selenium, AppOpener
  - **Audio**: Pygame, playsound
  - **Computer Vision**: OpenCV, MSS

## 📦 Requirements
- **Python Version**: 3.10.10
- **Libraries** (install with `pip install -r Requirements.txt`):

## 🚀 Installation Guide
1. **Install Python 3.10.10**: [Download](https://www.python.org/downloads/release/python-31010/)
2. **Clone the Repository**:
```bash
git clone https://github.com/mk12002/LUNA-AI.git
cd LUNA-AI
```
3. **Set Up Virtual Environment**:
```bash
python -m venv .venv
# Windows
.venv\Scripts\activate
# Linux/Mac
source .venv/bin/activate
```
4. **Install Dependencies**:
```bash
pip install -r Requirements.txt
```
5. **Configure Environment Variables** (`.env` file):
```
CohereAPIKey=your_key
GroqAPIKey=your_key
GeminiAPIKey=your_key
HuggingFaceAPIKey=your_key
Username=YourName
Assistantname=LUNA
InputLanguage=en
AssistantVoice=en-CA-LunaNeural
```

## 🎮 Usage
Start LUNA by running:
```bash
python Main.py
```
### Example Commands:
- "Who was Nikola Tesla?"
- "Open Notepad"
- "Play 'Blinding Lights'"
- "Google search for quantum computing"
- "Generate an image of a cyberpunk city"
- "Analyze my screen"


## 🌐 Impact & Significance
LUNA is more than a project—it’s a step toward frictionless, human-centric AI integration. It showcases:
- **Educational Value**: Great for learning NLP, APIs, CV, and GUI
- **User Empowerment**: Control your system and information effortlessly
- **Innovation**: A truly hybrid assistant blending local control with powerful cloud-based intelligence


## 🧰 Advanced Configuration
Customize the following via `.env`:
- `Username`: Your name
- `Assistantname`: Defaults to LUNA
- `InputLanguage`: e.g., `en`, `hi`, etc.
- `AssistantVoice`: Microsoft/Edge-compatible voice tag

## 🤝 Contributing
Have ideas or found a bug? Contributions are welcome!

## 📄 License
This project is open-source under the MIT License.


