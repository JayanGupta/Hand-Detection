<div align="center">
  
  # ✋ Hand Recognition System

  [![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
  [![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)](https://opencv.org)
  [![MediaPipe](https://img.shields.io/badge/MediaPipe-FF6F00?style=for-the-badge&logo=google&logoColor=white)](https://mediapipe.dev)
  [![cvzone](https://img.shields.io/badge/cvzone-00A86B?style=for-the-badge&logo=python&logoColor=white)](https://pypi.org/project/cvzone/)
  [![Pillow](https://img.shields.io/badge/Pillow-8B008B?style=for-the-badge&logo=python&logoColor=white)](https://python-pillow.org)

  *A real-time computer vision system for detecting hand gestures and finger counts using webcam input.*
</div>

---

## 📖 Overview
This project implements a **real-time hand recognition system** using computer vision techniques.  

It detects hand landmarks, counts the number of fingers raised, and identifies whether the thumb is up — enabling gesture-based interaction systems.

---

## 🚀 Features
- ✋ Real-time hand detection and tracking  
- ✌️ Detection of up to two hands  
- 🔢 Finger counting using landmark positions  
- 👍 Thumb detection (up/down state)  
- 🎯 Visual overlay of hand landmarks  
- 📺 Live output via webcam feed  

---

## 📂 Project Structure
```text
.
├── 📁 notebooks/              # CV practice notebooks
│   ├── Haar_Cascades.ipynb
│   ├── RGB.ipynb
├── main.py                   # Hand recognition script
├── requirements.txt
└── README.md
```

## Notebooks

This repository also includes a couple of Jupyter notebooks where I’ve explored some basic computer vision concepts using OpenCV:

- `Haar_Cascades.ipynb`: Simple face detection using Haar cascades.
- `RGB.ipynb`: Basic operations and color channel manipulation with OpenCV.

These notebooks are included to reflect my ongoing practice and understanding of core computer vision tools in Python.

## Libraries Used

* **cvzone**: For hand tracking and finger counting.
* **MediaPipe**: For detecting hand landmarks and connections.
* **OpenCV**: For capturing and processing the webcam feed.
* **PIL (Pillow)**: For image manipulation and conversion.

**Note**: Ensure your webcam is enabled. The system will:

- Detect hands in real-time
- Display finger count
- Identify thumb position
