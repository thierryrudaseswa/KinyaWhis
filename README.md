# Kinyarwanda Voice Assistant 🤖

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.8+](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)

An intelligent voice assistant for Kinyarwanda language interaction, developed as part of the Intelligent Robotics course at the University of Rwanda.

![Interface Demo](media/interface-screenshot.png)  
*Example interface - Add your screenshot to `/media` folder*

## Features 🌟
- 🎙️ **Kinyarwanda ASR** using KinyaWhisper (16kHz optimized)
- 🧠 **Contextual Understanding** with fuzzy logic matching
- 📢 **Natural Responses** with Kinyarwanda TTS
- 🔇 **Noise Reduction** using advanced audio cleaning
- 🎚️ **Voice Activity Detection** for precise speech recognition
- 🔄 **Anti-Repetition** transcription filters
- 📊 **Conversation Analytics** with matching insights
- 🌐 **Web Interface** with Gradio integration

## Tech Stack 🛠️
- **Core AI**: Hugging Face Transformers
- **Audio Processing**: Librosa + Soundfile
- **NLP**: FuzzyWuzzy + Python-Levenshtein
- **Interface**: Gradio
- **Optimization**: WebRTC VAD + Noisereduce

## Installation 💻

### Prerequisites
- Python 3.8+
- FFmpeg (audio processing):
  ```bash
  # Ubuntu/Debian
  sudo apt-get install ffmpeg
  
  # macOS
  brew install ffmpeg
  
  # Windows (via chocolatey)
  choco install ffmpeg