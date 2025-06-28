
# Emotion Detector

A real-time facial emotion detection application using OpenCV and Keras. This project captures video from your webcam, detects faces, and predicts the emotion displayed on each face using a pre-trained deep learning model.

## Features

- Real-time face detection using OpenCV's Haar Cascade.
- Emotion classification using a Keras deep learning model.
- Supports the following emotions: Angry, Disgust, Fear, Happy, Neutral, Sad, Surprise.

## Requirements

- Python 3.x
- OpenCV (`opencv-python`)
- Keras
- TensorFlow (backend for Keras)
- NumPy

Install dependencies with: pip install opencv-python keras tensorflow numpy


## Files

- `realtime.py` — Main script for real-time emotion detection.
- `emotiondetector.json` — Model architecture (JSON format).
- `emotiondetector.h5` — Model weights (HDF5 format).

## Usage

1. Place `realtime.py`, `emotiondetector.json`, and `emotiondetector.h5` in the same directory.
2. Run the script:
    ```
    python [realtime.py]
    ```
3. The webcam window will open. Detected faces will be highlighted with a rectangle and labeled with the predicted emotion.

## Notes

- Make sure your webcam is connected and accessible.
- The model files (`emotiondetector.json` and `emotiondetector.h5`) must be present in the same directory as the script.
- Press `ESC` or close the window to exit.

## License

This project is for educational purposes.

