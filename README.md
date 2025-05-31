# Smart Multimodal Chatbot for Disabled People (Accessight)

A powerful AI-driven educational and assistive chatbot platform that supports **sign language recognition**, **speech-to-text**, **text-to-speech**, **multilingual conversation**, and **interactive dashboards** to help deaf, mute, and visually impaired users communicate and learn more effectively.

---

## Features

- Real-time **Sign Language to Text** conversion using CNN-based gesture recognition.
- **Speech-to-Text** recognition using `SpeechRecognition`.
- **Text-to-Speech** voice output using `pyttsx3`.
- **Multilingual chatbot** (English, Tamil, Hindi, etc.) using `googletrans`.
- **Custom-trained chatbot** using `ChatterBot` and YAML files.
- **Sign Language Dictionary** with gesture images and meanings.
- **PDF Summarization** using the T5 NLP model (optional module).
- **Dashboard** to track learning progress and feedback.

---

## Tech Stack

| Component        | Tools Used                     |
| ---------------- | ------------------------------ |
| Language         | Python                         |
| GUI              | Tkinter                        |
| Chatbot Core     | ChatterBot                     |
| Translation      | googletrans / deep_translator  |
| TTS              | pyttsx3                        |
| STT              | SpeechRecognition              |
| Vision / Gesture | OpenCV, MediaPipe              |
| Deep Learning    | TensorFlow / Keras             |
| NLP              | HuggingFace Transformers (T5)  |

---

## Folder Structure

├── chatbot/ # YAML Q/A files
├── sign_language_model/ # Trained CNN model
├── images/ # Sign dictionary images
├── scripts/
│ ├── chatbot_gui.py # Chatbot interface
│ ├── sign_to_text.py # Sign language detection
│ ├── speech_to_text.py # Voice input handler
│ ├── text_to_speech.py # Voice output
├── README.md


---

## Installation

pip install chatterbot
pip install googletrans==4.0.0-rc1
pip install pyttsx3
pip install SpeechRecognition
pip install opencv-python
pip install tensorflow

 ## How to Run
 
 - Clone this repository.
 - Train or place the model in Accessight/.
 - Run the chatbot GUI:
   python app.py

## Use Case

 This chatbot helps differently-abled users (especially deaf, mute, and visually impaired) to:
- Learn using visual and audio feedback
- Communicate naturally through sign or voice
- Access educational material in their preferred mode
- Get real-time responses in multiple languages






