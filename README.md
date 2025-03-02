# AI Hand Gesture Controlled Mouse

This project uses hand gestures to control your computer's mouse and perform actions like left-click, right-click, double-click, and taking screenshots. It leverages **MediaPipe** for hand tracking, **OpenCV** for video processing, and **PyAutoGUI** for mouse control.

## Features
- **Mouse Movement**: Move the mouse pointer using your index finger.
- **Left Click**: Perform a left-click gesture.
- **Right Click**: Perform a right-click gesture.
- **Double Click**: Perform a double-click gesture.
- **Screenshot**: Take a screenshot with a specific hand gesture.
- **Real-Time Gesture Detection**: Detects gestures in real-time using your webcam.

## How It Works
The project uses the MediaPipe Hands model to detect and track hand landmarks in real-time. Based on the position and angles of these landmarks, it identifies specific gestures and translates them into mouse actions using PyAutoGUI.

### Gesture Recognition
- **Mouse Movement**: Extend your index finger and move your hand to control the mouse pointer.
- **Left Click**: Form a specific hand gesture (defined by angles between landmarks) to perform a left-click.
- **Right Click**: Form another gesture to perform a right-click.
- **Double Click**: Use a gesture to trigger a double-click.
- **Screenshot**: Use a unique gesture to capture and save a screenshot.

## Requirements
To run this project, you need the following Python libraries:
- `opencv-python`
- `mediapipe`
- `pyautogui`
- `pynput`

## Run the project 
```bash
git clone https://github.com/Syam-1133/AI-Hand-Gesture-Controlled-Mouse

pip install opencv-python mediapipe pyautogui pynput

python main.py
