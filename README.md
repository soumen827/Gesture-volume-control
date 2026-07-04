# 🎵 Gesture Volume Controller

> Control your computer's volume using **hand gestures** with the power of **Computer Vision**, **OpenCV**, and **Python**.

<p align="center">
  <img src="assets/hand_landmarks.jpg" alt="Hand Landmarks" width="850">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?logo=python">
  <img src="https://img.shields.io/badge/OpenCV-Computer%20Vision-green?logo=opencv">
  <img src="https://img.shields.io/badge/MediaPipe-Hand%20Tracking-orange">
  <img src="https://img.shields.io/badge/Status-Completed-brightgreen">
  <img src="https://img.shields.io/badge/License-MIT-blue">
</p>

---

## 📖 Overview

The **Gesture Volume Controller** is a Computer Vision project that enables users to control the **system volume** using **hand gestures** captured through a webcam.

The application detects **21 hand landmarks** using **MediaPipe**, calculates the distance between the **thumb tip** and **index finger tip**, and smoothly maps this distance to the system's audio level in real time.

This project demonstrates the practical use of **Computer Vision**, **Hand Tracking**, and **Human-Computer Interaction (HCI)**.

---

## 📸 Hand Landmark Detection

The project uses **MediaPipe Hands**, which detects **21 key landmarks** on a human hand.

<p align="center">
  <img src="assets/hand_landmarks.jpg" alt="Hand Landmarks" width="750">
</p>

The distance between:

- 👍 **Thumb Tip (Landmark 4)**
- ☝️ **Index Finger Tip (Landmark 8)**

is used to adjust the system volume.

---

## ✨ Features

- 🎥 Real-time webcam hand tracking
- ✋ Detects 21 hand landmarks
- 🔊 Gesture-based volume control
- ⚡ Smooth volume interpolation
- 📊 Live FPS display
- 🖥️ Works without touching the keyboard or mouse
- 🚀 Fast and lightweight implementation

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| Python | Programming Language |
| OpenCV | Webcam & Image Processing |
| MediaPipe | Hand Landmark Detection |
| NumPy | Mathematical Computation |
| Matplotlib | Data Visualization |
| Pycaw | Windows Volume Control |
| ctypes | System API Integration |

---

## 📂 Project Structure

```text
Gesture-Volume-Controller/
│
├── assets/
│   └── hand_landmarks.jpg
│
├── volume_controller.py
├── requirements.txt
├── README.md
└── LICENSE
```

---

## ⚙️ Installation

### Clone the repository

```bash
git clone https://github.com/your-username/Gesture-Volume-Controller.git
```

```bash
cd Gesture-Volume-Controller
```

---

## 📦 Install Dependencies

```bash
pip install -r requirements.txt
```

or

```bash
pip install opencv-python mediapipe numpy matplotlib pycaw comtypes
```

---

## ▶️ Run the Project

```bash
python volume_controller.py
```

Allow webcam access when prompted.

---

## 🎮 How It Works

1. Open your webcam.
2. The program detects your hand.
3. Raise your thumb and index finger.
4. Change the distance between them.
5. The system volume changes accordingly.

### Gesture Logic

| Finger Distance | Volume |
|----------------|---------|
| Small Distance | Low Volume 🔉 |
| Medium Distance | Medium Volume 🔊 |
| Large Distance | Maximum Volume 🔊🔊 |

---

## 🧠 Working Principle

The project follows these steps:

- Capture live video from the webcam.
- Detect the hand using MediaPipe.
- Extract the coordinates of hand landmarks.
- Calculate the Euclidean distance between Landmark **4** and Landmark **8**.
- Map the distance to the system volume range using **NumPy interpolation**.
- Update the system volume continuously.

---

## 📷 Output

- ✅ Live hand detection
- ✅ Landmark visualization
- ✅ Volume percentage display
- ✅ FPS counter
- ✅ Smooth gesture control

---

## 📚 Concepts Used

- Computer Vision
- Hand Tracking
- Human-Computer Interaction (HCI)
- Euclidean Distance
- Image Processing
- Real-Time Video Processing
- Audio Control APIs
- Linear Interpolation

---

## 🔮 Future Improvements

- 🎙️ Brightness control
- 🖱️ Virtual mouse
- ✍️ Air drawing
- 🤏 Multi-hand gesture recognition
- 🖥️ Gesture-based presentation control
- 🤖 AI gesture classification

---

## 🤝 Contributing

Contributions are welcome!

1. Fork this repository
2. Create a feature branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Added new feature"
```

4. Push the branch

```bash
git push origin feature-name
```

5. Open a Pull Request

---

## 👨‍💻 Author

### Soumen Laha

🎓 B.Tech Electronics & Communication Engineering (ECE)  
💻 Aspiring Software Developer  
🚀 Passionate about Computer Vision, AI, Java, Python, and Problem Solving.

---

## ⭐ Support

If you found this project useful, consider giving it a **⭐ Star** on GitHub.

It motivates me to build more open-source projects!

---

## 📄 License

This project is licensed under the **MIT License**.
