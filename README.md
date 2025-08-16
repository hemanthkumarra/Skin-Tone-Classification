# Skin-Tone-ClassificationFace Detection and Skin Tone Classification

This project uses OpenCV and Haar Cascades to detect faces in real-time from a webcam feed and classify skin tone (Black, Brown, White) based on average color values.

Features:

Real-time face detection using Haar Cascade classifier.
Skin tone classification from detected face regions.
Simple classification logic based on RGB color values.
Live webcam feed with bounding boxes and labels.

Requirements:

Install dependencies using:
  pip install opencv-python numpy

Notes

Current classification is a basic threshold-based approach (uses average R value).
Accuracy can be improved using HSV/LAB color spaces or machine learning models.
