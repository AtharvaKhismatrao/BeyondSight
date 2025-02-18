# 🌟 Beyond Sight – AI-Powered Assistive Application


Beyond Sight is an AI-driven assistive tool designed to empower visually impaired individuals by helping them navigate their surroundings with confidence. Using real-time object detection and facial recognition, the application provides auditory feedback, allowing users to identify nearby objects and recognize familiar faces from their saved contact database.





# 🚀 Key Features



## 🔊 Voice-Guided Navigation – Offers step-by-step audio guidance to help users move safely.

![object](https://github.com/AtharvaKhismatrao/BeyondSight/blob/a6b4a061eb2976b5d8c130b56d97b28f15bc0838/images/WhatsApp%20Image%202025-02-14%20at%2000.23.21_76700fa6.jpg)


## 🛑 Object Detection – Identifies objects in the environment and announces them audibly.

![object](https://github.com/AtharvaKhismatrao/BeyondSight/blob/361088243f65b4a7e595f8f3eb7b73e71caffa5d/images/WhatsApp%20Image%202025-01-31%20at%2009.22.48_f4d204c5.jpg)


🧑‍🤝‍🧑 Facial Recognition – Recognizes and speaks out the names of known individuals using a CSV-based contact database.

![object](https://github.com/AtharvaKhismatrao/BeyondSight/blob/a6b4a061eb2976b5d8c130b56d97b28f15bc0838/images/WhatsApp%20Image%202025-02-14%20at%2000.23.22_88f15a87.jpg)


## 🗣 Audio Assistance – Converts detected text and recognized names into speech using ElevenLabs TTS API.


![object](https://github.com/AtharvaKhismatrao/BeyondSight/blob/89421898ff81779525aaa53930c31e9bce002301/images/WhatsApp%20Image%202025-02-14%20at%2000.23.23_86553540.jpg)



## 📏 Depth Detection – Measures the distance of objects to enhance spatial awareness.


![object](https://github.com/AtharvaKhismatrao/BeyondSight/blob/89421898ff81779525aaa53930c31e9bce002301/images/Screenshot%202025-02-14%20011439.png)








# 🛠️ Technologies Used








- Python (OpenCV, Face Recognition, TensorFlow, NumPy, Pandas)

- Text-to-Speech (TTS) powered by the ElevenLabs API

- Computer Vision for facial and object recognition

- Machine Learning for facial detection

- CSV Database for storing and retrieving recognized faces











# 🔧 Installation Guide









## 1️⃣ Clone the Repository


git clone https://github.com/AtharvaKhismatrao/BeyondSight.git



## 2️⃣ Install Dependencies


pip install -r requirements.txt  


## 3️⃣ Set Up ElevenLabs API


- Sign up at ElevenLabs

- Get your API key

- Open speech.py and replace "your_api_key_here" with your actual key










# 📌 How It Works








- 📷 The camera detects faces and objects in real time.


- 🧑‍💼 If a recognized face is detected, the system announces the person’s name.


- 🔍 Surrounding objects are identified and described audibly.


- 🗺️ The system provides voice-based navigation assistance for smooth movement.











# 🚀 Future Enhancements









- 🌍 Multi-Language Support – Expand TTS functionality to support multiple languages.


- 🖐 Gesture Recognition – Enable hands-free control using simple hand gestures.


- ☁ Cloud Integration – Store user profiles and history for personalized assistance.













# 📜 License










- This project is licensed under the MIT License – feel free to modify and use it!


