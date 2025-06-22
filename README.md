# Facial Recognition System

A Python-based facial recognition system that detects and recognizes faces in real-time using **OpenCV**, **Haar Cascade Classifier**, and the **K-Nearest Neighbors (KNN)** algorithm. This project explores core concepts in computer vision and machine learning.

---

## Features

- Real-time face detection via webcam
- Face recognition using KNN
- Image data management for multiple users
- Simple and modular Python implementation

---

## Project Structure

facial-recognition/
├── face_data.py # Captures and stores face images
├── cv.py # Runs the face recognition logic
├── face_dataset/ # Stores image data used for recognition


> **Important:**  
> The project depends on a folder named `face_dataset` to store image data.  
> Make sure this directory exists in the root folder before running the code.  
> It will be used to save and retrieve face images for training/recognition.

---

##  Requirements

- Python 3.x
- OpenCV
- NumPy
- OS (standard library)

Install dependencies with:

pip install opencv-python numpy

