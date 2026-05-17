# American Sign Language Detection using MediaPipe & TensorFlow Lite

This project is a real-time American Sign Language (ASL) hand gesture recognition system built using Python, MediaPipe, OpenCV, and TensorFlow Lite.

The system detects hand landmarks from webcam input and classifies ASL alphabet gestures in real time using a trained keypoint classification model.
<img width="1600" height="959" alt="image" src="https://github.com/user-attachments/assets/238abbc6-5e41-409b-9c0f-26dd242c201f" />




## Features

* Real-time ASL hand gesture detection
* MediaPipe hand landmark tracking
* TensorFlow Lite gesture classification
* Webcam-based gesture recognition
* Dataset collection mode
* Custom model training support
* Lightweight and fast CPU inference

## Technologies Used

* Python
* OpenCV
* MediaPipe
* TensorFlow Lite
* NumPy

## Project Workflow

1. Capture hand landmarks using MediaPipe
2. Store landmark coordinates into CSV dataset
3. Train TensorFlow Lite classifier
4. Perform real-time gesture recognition

## Folder Structure

```bash
model/
utils/
assets/
app.py
main.py
requirements.txt
```

## Installation

```bash
pip install -r requirements.txt
```

## Run Project

```bash
python main.py
```

## Training

The project supports custom dataset collection and training for new ASL gestures.

* Press `k` to enable landmark collection mode
* Collect gesture samples
* Train classifier using the generated dataset

## Applications

* Sign language recognition
* Accessibility tools
* Human-computer interaction
* Gesture-controlled systems
* Educational AI projects

## Future Improvements

* Sentence-level ASL recognition
* Deep learning CNN integration
* Mobile deployment
* Multi-hand gesture recognition
* Speech output generation

## Author

Praveen Kumar
GitHub: https://github.com/PRK9547
