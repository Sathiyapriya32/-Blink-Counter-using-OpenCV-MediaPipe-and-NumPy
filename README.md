# 👁️ Eye Blink Counter

A real-time Eye Blink Counter using OpenCV, MediaPipe, and NumPy in Python.  
This project captures video from the webcam, detects facial landmarks using MediaPipe Face Mesh, calculates the Eye Aspect Ratio (EAR), and counts the number of blinks accurately.


## 📚 Imports
opencv-python

mediapipe

numpy

## ⚙️ Techniques Used
OpenCV for webcam access and image processing

MediaPipe Face Mesh for detecting facial landmarks

Eye Aspect Ratio (EAR) calculation for blink detection

NumPy for distance calculations

## 🖼️ Screenshot

![Screenshot 2025-04-27 at 2 16 42 AM](https://github.com/user-attachments/assets/02de23c5-83ee-4955-ad7c-2a8bbae3b8a6)


## 🎥 Project Explanation Video
🎥 [Watch the Video](https://www.linkedin.com/posts/sathiyapriya-s-22ucs048_eyeblinkcounter-ai-healthtech-activity-7237466614214836224-Qd6E?utm_source=social_share_send&utm_medium=member_desktop_web&rcm=ACoAAEKubiABTjioeFLfoGOrHXFNNCGvYJ6moX8)


## 🔥 How It Works
Open the webcam.

Detect facial landmarks using MediaPipe Face Mesh.

Extract eye landmarks.

Calculate the Eye Aspect Ratio (EAR).

If EAR drops below a threshold for a few frames → count as a blink.

Display blink count and EAR on the screen in real-time.

Press q to quit the application.

## 📦 Installation

Install the required libraries using pip:

```bash
pip install opencv-python mediapipe numpy

