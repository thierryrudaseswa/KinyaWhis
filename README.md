# Kinyarwanda Voice Assistant 🤖

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.12](https://img.shields.io/badge/Python-3.12-blue.svg)](https://www.python.org/)

An intelligent voice assistant for Kinyarwanda language interaction, developed as part of the Intelligent Robotics course.



🌟 Key Features
🎙️ Kinyarwanda Speech Recognition: Built on KinyaWhisper, fine-tuned for 16kHz audio.

🧠 Smart Understanding: Uses fuzzy logic for flexible and context-aware question matching.

📢 Natural Kinyarwanda Responses: Speech output generated via Kinyarwanda TTS.

🔇 Clean Audio Input: Enhanced noise reduction ensures clearer speech detection.

🎚️ Accurate Detection: Employs Voice Activity Detection (VAD) for precise speech segmentation.

🔄 Repetition Filtering: Eliminates redundant transcriptions for smoother results.

📊 Insightful Analytics: Visualize matched queries and system behavior.

🌐 User-Friendly Interface: Seamless interaction through a web app powered by Gradio.

🛠️ Technology Stack
AI Backbone: Hugging Face Transformers

Audio Handling: Librosa + SoundFile

Language Processing: FuzzyWuzzy & Python-Levenshtein for similarity scoring

Frontend Interface: Gradio

Performance Enhancements: WebRTC-based VAD & NoiseReduce for real-time optimization

## Installation 💻

### Prerequisites
- Python 3.12
- FFmpeg (audio processing):
  ```bash
  # Ubuntu/Debian
  sudo apt-get install ffmpeg
  
  # macOS
  brew install ffmpeg
  
  # Windows (via chocolatey)
  choco install ffmpeg
  ```
  
## Quick Start 🚀

- Clone repository
  ```bash
    git clone https://github.com/thierryrudaseswa/KinyaWhis.git
    cd KinyarwandaVoiceAssistant
  ```# Create a virtual environment
python -m venv .venv

# Activate the virtual environment
# For Linux/macOS:
source .venv/bin/activate

# For Windows:
.venv\Scripts\activate
pip install -r requirements.txt

{
  "qa_pairs": [
    {
      "question": "Mwaramuce neza?",
      "answer": "Mwaramutse! Amakuru yanyu?"
    }
  ],
  "default_response": "Vugurura ikibazo."
}


## Example Interactions 🗣️
| Raw Transcription | Matched Question | System Response                                              |
|-------------------|-----------|--------------------------------------------------------------|
| mizeneza          |Umeze neza?| Yego! Turashima Imana.                                       |
