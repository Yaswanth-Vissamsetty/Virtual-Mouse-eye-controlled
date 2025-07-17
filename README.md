# Eye Controlled Mouse

Control your computer mouse pointer using your eye movements via a standard webcam. This Python project uses OpenCV and MediaPipe’s face and eye tracking to detect your gaze direction and PyAutoGUI to move the cursor and perform clicks—all hands-free!

## Features
- Real-time eye tracking with MediaPipe
- Cursor movement based on gaze direction
- Blink or prolonged eye closure for clicking
- No extra hardware needed besides a webcam

## Installation

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/eye-controlled-mouse.git
   cd eye-controlled-mouse
````

2. Install dependencies:

   ```bash
   pip install opencv-python mediapipe pyautogui
   ```

## Usage

Run the script:

```bash
python eye_controlled_mouse.py
```

Ensure your webcam is connected and allow camera access. Move your eyes to move the cursor and blink to click.

## Requirements

* Python 3.7+
* Webcam

## Future Improvements

* Add gaze calibration for higher accuracy
* Support right-click and scroll with eye gestures
* Enhance blink detection robustness
