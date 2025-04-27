# Anti Spoofing in Face Recognition

This project implements an eye-blink detection-based real-time liveness detection algorithm for face recognition. The goal is to enhance the security of face recognition systems by detecting spoofing attempts using real-time eye-blink patterns.

## Project Structure

1. **`anti_spoof_face_recognition.ipynb`**  
   This Jupyter Notebook contains the full training pipeline for the model. It includes data preprocessing, data augmentation, model training, and evaluation for detecting whether a face is real or spoofed.

2. **`anti_spoof_live_face_recognition_app.ipynb`**  
   This notebook uses the saved model (`eye_status_classifier.h5`) to create a live detection application. It runs real-time liveness detection to verify if the face is live or a spoofed attempt, based on eye-blink detection.

## Installation

To run the project, you need the following dependencies:

- Python 3.x
- TensorFlow
- Keras
- OpenCV
- NumPy
- Pillow
- Matplotlib

You can install the required dependencies using `pip`:

```bash
pip install tensorflow keras opencv-python numpy pillow matplotlib
