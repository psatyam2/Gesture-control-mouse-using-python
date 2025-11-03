🖐️ Gesture Control Mouse Using Python

This project allows you to control your computer mouse with hand gestures using your webcam. Built with Python, OpenCV, MediaPipe, and PyAutoGUI, it converts real-time hand movements into cursor actions — enabling a futuristic, touch-free interaction with your computer.

🧠 How It Works

Using your webcam feed, the program detects and tracks your hand with MediaPipe’s Hand Tracking module. It identifies key points (landmarks) on your fingers and analyzes their positions to recognize gestures. These gestures are then mapped to specific mouse actions via PyAutoGUI, such as:

🖱️ Index finger movement → Move cursor

👆 Pinch gesture → Left click

✌️ Two-finger pinch → Right click

🖐️ Vertical motion → Scroll up/down

⚙️ Features

Real-time hand detection and tracking

Gesture-based click, scroll, and movement control

Adjustable sensitivity and smoothing

Cross-platform support (Windows, macOS, Linux)

Works with any standard webcam

🧩 Tech Stack

Python 3.x

OpenCV – image and video processing

MediaPipe – hand landmark detection

PyAutoGUI – controlling mouse events


2️⃣ Install Dependencies
pip install -r requirements.txt

3️⃣ Run in PyCharm

Open PyCharm and select Open Project → choose this folder.

Ensure your Python interpreter is set to Python 3.x.

Open gesture_mouse.py.

Click Run ▶️ or press Shift + F10 to start.

Allow camera access and move your hand to control the cursor!

This project demonstrates the power of computer vision and AI-based gesture recognition for intuitive, hands-free computing.
