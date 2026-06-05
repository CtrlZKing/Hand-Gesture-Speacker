# Sign Language Recognition System

A Python-based project that uses OpenCV and MediaPipe to track hand gestures and translate them into text/speech.

# ⚠️ Known Issues & Status
This project is a work-in-progress. Currently, I am facing a persistent AttributeError: module 'mediapipe' has no attribute 'solutions' while running the script in IDLE.

🔷**Gesture Detection:** The model is currently trained to recognize my specific signs.

🔷**Stability:** The system currently struggles with "jitter" (oscillating between gestures). I'm working on implementing a smoothing/debouncing logic to stabilize the output.

# 🛠 How You Can Help
Since I'm still new to Computer Vision, I'd appreciate any contributions or advice!

🔷**Fixing Environment Issues:** If you know why MediaPipe is throwing the AttributeError in IDLE, please open an issue or let me know!

🔷**Smoothing Logic:** If you have suggestions for stabilizing the prediction frames (to stop the audio overlapping/jittering), feel free to submit a Pull Request.

# Tech Stack
*Python

*OpenCV

*MediaPipe

**Developed by:** `CtrlZking`
