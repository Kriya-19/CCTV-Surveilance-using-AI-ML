# CCTV-Surveilance-using-AI-ML

AI-powered CCTV surveillance system using Machine Learning and Computer Vision to monitor hostels and secured premises. The system detects fights, unauthorized access, anomalies, and guard inactivity, providing real-time alerts and a visual dashboard to enhance safety and situational awareness.

---

## 🧠 Project Overview

This project implements an intelligent surveillance system built on top of existing CCTV infrastructure. Using OpenCV and Roboflow-trained models, the system analyzes live or recorded video feeds to identify suspicious or unsafe activities automatically.

The solution reduces manual monitoring effort while improving response time to critical incidents such as violence, intrusion, or lack of security presence.

---

## 🚀 Features

- Fight detection  
- Unauthorized access detection  
- Guard inactivity monitoring  
- Real-time alerts  
- Live surveillance dashboard  
- Works with CCTV / webcam feeds  
- Modular and extensible design  

---

## 🛠️ Tech Stack

- **Programming Language:** Python  
- **Computer Vision:** OpenCV  
- **Machine Learning Models:** Roboflow (YOLO-based)  
- **Dashboard:** Streamlit  
- **Libraries:** NumPy, Threading  

---

## 📁 Project Structure

CCTV-Surveilance-using-AI-ML/  
├── models/                       # Trained ML models  
├── Gender-and-Age-Detection/     # Optional demographic detection module  
├── streamlit1.py                 # Main dashboard application  
├── .gitattributes  
└── README.md  

---

## ⚙️ Installation

Clone the repository:

git clone https://github.com/Kriya-19/CCTV-Surveilance-using-AI-ML.git  
cd CCTV-Surveilance-using-AI-ML  

(Optional) Create a virtual environment:

python -m venv venv  

Activate the environment:

Windows:  
venv\Scripts\activate  

Linux / macOS:  
source venv/bin/activate  

Install dependencies:

pip install opencv-python roboflow streamlit numpy  

---

## ▶️ Running the Project

Start the surveillance dashboard:

streamlit run streamlit1.py  

The dashboard will open in your browser at:

http://localhost:8501  

---

## 📌 How It Works

1. Connect a CCTV camera or webcam feed  
2. Video frames are captured and processed  
3. Machine learning models analyze human activity  
4. Suspicious or abnormal behavior triggers alerts  
5. Dashboard displays live feed, detections, and logs  

---

## 🧪 Model Training & Customization

To use custom models:

1. Train a dataset using Roboflow  
2. Export the model in YOLO format  
3. Place the model files in the models/ directory  
4. Update the model path in the detection script  

---


