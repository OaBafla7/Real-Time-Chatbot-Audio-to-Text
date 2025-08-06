# Real-Time Voice Chatbot 🤖🎙️

An AI-powered voice chatbot with real-time speech recognition and text-to-speech capabilities in Arabic

<img width="1156" height="1020" alt="Screenshot 2025-08-05 144754" src="https://github.com/user-attachments/assets/b37631cf-c32e-44f4-8f00-497ede01e51f" />

## Features
- Speech-to-Text (STT) using Whisper 🎙→📝  
- Intelligent response generation using Cohere's Command R+ 🤖💡  
- Text-to-Speech (TTS) using gTTS 📝→🎧  
- Full Arabic language support 🇸🇦  

## Requirements
- Python 3.8 or newer
- The following Python libraries:

```bash
pip install speechrecognition gtts playsound cohere

Installation & Usage

Install requirements:

bash
pip install -r requirements.txt
Get API key from Cohere

Edit the file with your API key:

python
co = cohere.Client("your_api_key_here")
Run the chatbot:

bash
python chatbot.py
