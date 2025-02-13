🌟 Beyond Sight – AI-Powered Assistive Application
Beyond Sight is an AI-driven assistive tool designed to empower visually impaired individuals by helping them navigate their surroundings with confidence. Using real-time object detection and facial recognition, the application provides auditory feedback, allowing users to identify nearby objects and recognize familiar faces from their saved contact database.

🚀 Key Features
🔊 Voice-Guided Navigation – Offers step-by-step audio guidance to help users move safely.

🛑 Object Detection – Identifies objects in the environment and announces them audibly.

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

