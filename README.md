# Virtual_mouse-using-hand-gestuers-
 A Python-based virtual mouse that uses real-time hand gesture recognition with MediaPipe and OpenCV to control cursor movement and mouse clicks — all touch-free and webcam-driven.
# 🖐️ Virtual Mouse Using Hand Gestures

A Python-based virtual mouse that uses hand gesture recognition via a webcam to control mouse operations like cursor movement, left click, right click, and double click — all without touching the mouse!

![Demo](demo.gif) <!-- Optional: Add a demo GIF or screenshot -->

---

## 📌 Features

- 🎯 Real-time hand tracking using MediaPipe
- 🖱️ Cursor movement based on index finger
- ✅ Gesture-based Left Click, Right Click, and Double Click
- 💻 Works on any system with a webcam
- 🔍 Simple and clean Python implementation

---

## 🧠 Technologies Used

- **Python 3.x**
- **OpenCV** – for video capture and frame processing
- **MediaPipe** – for real-time hand landmark detection
- **pyautogui** – for controlling mouse movements
- **pynput** – for simulating mouse clicks

---

## 🖥️ How It Works

1. MediaPipe tracks 21 hand landmarks in real-time.
2. The angles between finger joints and distances between key points are calculated.
3. Specific gestures (like finger bends and distances) are mapped to:
   - Move the cursor
   - Perform mouse clicks (left, right, double)

---

## ⚙️ Installation

1. **Clone the repo**  
```bash
git clone https://github.com/yourusername/virtual-mouse-hand-gesture.git
cd virtual-mouse-hand-gesture

👨‍💻 Author
Pankaj Kailas Lanjulkar
B.Tech Computer Engineering
📍 DBATU | CSE Department

