# Real-time Face and Eye Detection

This repository contains a Python script that uses OpenCV to perform real-time face and eye detection in video captured from the default camera. It applies Haar cascades for face and eye detection, drawing rectangles around the detected features.

## Prerequisites

Before running the script, make sure you have the following dependencies installed:

- Python 3.x
- OpenCV
- haarcascade_frontalface_default.xml (Haar cascade file for face detection)
- haarcascade_eye.xml (Haar cascade file for eye detection)

## Usage

1. Clone the repository:

```
git clone https://github.com/your-username/real-time-face-and-eye-detection.git
```

2. Navigate to the project directory:

```
cd real-time-face--and-eye-detection
```

3. Run the script:

```
python face_eye_detect.py
```

4. The script will open a window displaying the real-time video feed from the default camera. It will draw rectangles around the detected faces and eyes.
   To exit, press the letter 'q'


## References

- Haar Cascade xml files: https://github.com/kipr/opencv/tree/master/data/haarcascades
