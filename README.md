# 🤖 AI Motion & Pose Skeleton Tracker

A real-time AI-powered human motion and pose estimation tool built with Python. Using Google's MediaPipe Pose pipeline and OpenCV, this project tracks 33 distinct body landmarks and overlays a dynamic digital skeleton onto a live webcam feed.

## 🛠 Features
* **Real-Time Skeleton Tracking:** High-fidelity human pose landmark detection.
* **Live Webcam Integration:** Automatically captures, processes, and displays overlays from your default camera feed.
* **Low Latency:** Optimized for steady tracking using MediaPipe's lightweight `model_complexity=1`.
* **Clean Interface:** Press `ESC` at any time to instantly exit the program.

## 📋 Prerequisites
Ensure you have Python 3.8+ installed. You will need to install OpenCV and MediaPipe:

```bash
pip install opencv-python mediapipe