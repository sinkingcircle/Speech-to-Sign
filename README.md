# Speech-to-Sign

Talk to the system — and watch your words come alive in Indian Sign Language (ISL)!

This project is a real-time speech-to-ISL translator that allows anyone to speak naturally, and see their words instantly converted into animated ISL signs. Designed for accessibility, education, and inclusive communication, the system bridges the gap between hearing and hearing-impaired communities in India.

✨ Key Features
🎙️ Talk Naturally: Speak into your microphone — no typing needed.

🖐️ Real-Time ISL Output: See your spoken words translated into ISL gestures.

🔒 Offline Processing: Powered by Vosk/Kaldi, ensuring complete privacy — no internet required.

🛠️ Lightweight & Fast: Runs smoothly on standard laptops or desktops.

🌟 User-Friendly Interface: Simple, intuitive design using Python’s Tkinter.

🇮🇳 Indian Sign Language Focus: Tailored specifically for ISL, not ASL or other sign languages.

🚀 How It Works
Capture: Audio is captured via your microphone.

Recognize: Speech is converted into text using offline speech recognition.

Process: Text is cleaned, normalized, and tokenized into key words.

Translate: Words are mapped to corresponding ISL signs.

Animate: ISL gestures are rendered as a smooth animated GIF sequence.

🎯 Why This Project Matters
Over 5 million Indians rely on ISL daily, yet real-time speech-to-sign tools are rare. This project empowers more inclusive communication, helping hearing individuals engage meaningfully with hearing-impaired communities — whether in classrooms, hospitals, workplaces, or everyday life.


How to run:

pip install -r requirements.txt

create venv optional

run python main.py
