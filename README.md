# Hand-Gesture-Controlled-Volume-Python-
See tutorial in my youtube channel: https://youtu.be/sCuLoIY_F7s
---

![Demo GIF](121212.png) 

## Overview

This Python script uses computer vision and the MediaPipe library to detect hand gestures from a webcam feed and control the system's audio volume based on the hand gesture. By performing specific hand gestures in front of your webcam, you can easily adjust your computer's audio volume without touching any buttons.

## Features

- **Hand Gesture Detection**: The script utilizes the MediaPipe library to detect hand landmarks in real-time.
- **Volume Control**: It interprets the distance between the thumb and index finger to control the system's audio volume.
- **Visual Feedback**: Provides visual feedback in the form of a volume bar and percentage on the webcam feed.
- **Customizable**: You can fine-tune the volume control sensitivity and customize the visual feedback.

## Dependencies

Before using this code, ensure you have the following dependencies installed:

- OpenCV (cv2)
- MediaPipe (mediapipe)
- NumPy (numpy)
- comtypes
- pycaw

You can install these dependencies using pip:

```bash
pip install opencv-python mediapipe numpy comtypes pycaw
```

## Getting Started

1. Clone this repository to your local machine:

```bash
git clone https://github.com/Arminsbss/Hand-Gesture-Controlled-Volume-Python-.git
```

2. Navigate to the project directory:

```bash
cd hand-gesture-volume-control
```

3. Run the script:

```bash
python main.py
```

4. Use hand gestures to control the volume. The README code provided earlier explains the specific gestures and controls in detail.

## Configuration

You can adjust the volume control sensitivity and customize the appearance of the volume bar by modifying the code. Look for the comments in the code that indicate where these adjustments can be made.

## Contributions

Contributions are welcome! If you have ideas for improvements, please open an issue or create a pull request.

## Acknowledgments

- Thanks to the creators of MediaPipe for their hand tracking library.

## Support

If you have any questions or encounter issues, feel free to [open an issue](../../issues). We're here to help!

---


