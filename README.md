🌟 Beyond Sight – AI-Powered Assistive Application


Beyond Sight is an AI-driven assistive tool designed to empower visually impaired individuals by helping them navigate their surroundings with confidence. Using real-time object detection and facial recognition, the application provides auditory feedback, allowing users to identify nearby objects and recognize familiar faces from their saved contact database.



🚀 Key Features



🔊 Voice-Guided Navigation – Offers step-by-step audio guidance to help users move safely.

🛑 Object Detection – Identifies objects in the environment and announces them audibly.

![object](https://github.com/AtharvaKhismatrao/BeyondSight/blob/361088243f65b4a7e595f8f3eb7b73e71caffa5d/images/WhatsApp%20Image%202025-01-31%20at%2009.22.48_f4d204c5.jpg)


🧑‍🤝‍🧑 Facial Recognition – Recognizes and speaks out the names of known individuals using a CSV-based contact database.

🗣 Audio Assistance – Converts detected text and recognized names into speech using ElevenLabs TTS API.

📏 Depth Detection – Measures the distance of objects to enhance spatial awareness.


🛠️ Technologies Used
Python (OpenCV, Face Recognition, TensorFlow, NumPy, Pandas)
Text-to-Speech (TTS) powered by the ElevenLabs API
Computer Vision for facial and object recognition
Machine Learning for facial detection
CSV Database for storing and retrieving recognized faces

🔧 Installation Guide
1️⃣ Clone the Repository
git clone https://github.com/AtharvaKhismatrao/BeyondSight.git
2️⃣ Install Dependencies
pip install -r requirements.txt  
3️⃣ Set Up ElevenLabs API

Sign up at ElevenLabs
Get your API key
Open speech.py and replace "your_api_key_here" with your actual key

📌 How It Works
📷 The camera detects faces and objects in real time.
🧑‍💼 If a recognized face is detected, the system announces the person’s name.
🔍 Surrounding objects are identified and described audibly.
🗺️ The system provides voice-based navigation assistance for smooth movement.

🚀 Future Enhancements
🌍 Multi-Language Support – Expand TTS functionality to support multiple languages.
🖐 Gesture Recognition – Enable hands-free control using simple hand gestures.
☁ Cloud Integration – Store user profiles and history for personalized assistance.

📜 License
This project is licensed under the MIT License – feel free to modify and use it!
