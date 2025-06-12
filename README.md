Hand Sign Recognition with Speech Output
This project recognizes hand signs using MediaPipe and speaks out the detected signs using pyttsx3 (Text-to-Speech). It uses threading and queue to ensure smooth and real-time communication between the recognition logic and voice engine. This can be especially helpful in building tools for people who rely on hand signs to communicate.

🔧 Libraries Used
mediapipe as mp – for real-time hand tracking

pyttsx3 – to convert recognized signs into spoken words

threading – to run the TTS engine in the background

queue – to manage the sign outputs efficiently

time – for frame management and delays

🚀 Features
Real-time hand sign recognition

Converts recognized signs to speech

Multithreading for non-blocking audio output

Modular and extendable codebase

Can be used as a base for sign language communication tools

🖥️ How It Works
Detects hands using mediapipe and extracts landmarks.

Recognizes specific hand signs based on landmark positions.

Sends the recognized sign to a queue.

A separate thread reads the queue and speaks the sign using pyttsx3
 Future Scope
Add more complex signs

Build a dataset to support custom gestures

Integrate with GUI or mobile application

Add a "no-gesture" class to reduce false predictions

🤝 Contributions
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
