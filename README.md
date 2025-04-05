# 🖱️ Virtual Mouse using Eye Tracking

A Python-based virtual mouse system that allows users to control their cursor and perform click actions using eye movement and blinking, powered by **OpenCV**, **MediaPipe**, and **PyAutoGUI**.

## 🚀 Features

- Cursor movement using eye gaze (tracked via the right eye).
- Left-click action triggered by blinking (detected via the left eye).
- Basic calibration support (placeholder logic included).

## 🧠 How It Works

- Uses MediaPipe's **Face Mesh** to detect facial landmarks.
- Tracks the **right eye** (landmark 474–478) for cursor control.
- Monitors **left eye** (landmarks 145 and 159) to detect blinking.
- If the eye remains closed beyond a threshold, a click is triggered.
- Smoothing is applied to prevent cursor jitter.

## 🧰 Tech Stack

- [OpenCV](https://opencv.org/) – Real-time computer vision.
- [MediaPipe](https://mediapipe.dev/) – Facial landmark detection.
- [PyAutoGUI](https://pyautogui.readthedocs.io/) – Cursor control and automation.


## 🎮 Controls

- **Move Cursor**: Look around using your right eye.
- **Click**: Blink your left eye (hold it shut briefly).
- **Calibrate**: Press `c` (Currently in development).
- **Quit**: Press `q`.

## 📌 Notes

- Works best in well with one who is not using spectacles.
- Ensure your webcam is unobstructed.
- Try adjusting the blink threshold if false positives occur.



## 👨‍💻 Author

**Falak Rana**  
[LinkedIn]([https://www.linkedin.com/](https://www.linkedin.com/in/falak-rana-125520221/)) • [GitHub](https://github.com/falakrana)
