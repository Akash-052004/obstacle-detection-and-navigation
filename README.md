# 🦯 Obstacle Detection and Navigation for Visually Impaired People

This project uses real-time object detection and audio feedback to assist visually impaired individuals in navigating their surroundings. It leverages YOLOv5 for obstacle detection and provides spoken alerts to ensure safe and informed movement.

---

## 🚀 Features

- Real-time obstacle detection using YOLOv5
- Identifies people, vehicles, traffic lights, and other objects
- Audio feedback to alert users
- Runs entirely in Google Colab
- Lightweight and easy to use

---

## 🧠 Technologies Used

- Python (Google Colab)
- YOLOv5 (Ultralytics)
- OpenCV
- NumPy
- gTTS / pyttsx3 (Text-to-Speech)

---

## ⚙️ Setup Instructions (Colab)

1. Clone YOLOv5 and install requirements:
   ```python
   !git clone https://github.com/ultralytics/yolov5
   %cd yolov5
   %pip install -r requirements.txt

---
## 📓 How It Works

- YOLOv5 detects obstacles in real-time from camera/video input.
- Detected objects are categorized (e.g., "person", "car").
- The system converts detection results to speech using a TTS engine.
- Audio feedback is played to guide the user.

