# Computer-Vision
Basic Computer Vision Projects
1. Face and Eye Detection

   # OpenCV Face Detection with Haar Cascades

This project implements a simple face detection application using OpenCV and Haar Cascade classifiers. It demonstrates how to use OpenCV to detect faces in static images and mark them with rectangles.

## Prerequisites

Ensure you have the following requirements installed:

- Python 3.x
- OpenCV
- Matplotlib

You can install the necessary Python packages using pip:

```bash
pip install numpy opencv-python matplotlib

## How It Works
Load Classifier: The Haar Cascade haarcascade_frontalface_default.xml is loaded using OpenCV's CascadeClassifier.
Image Processing: The image is read and converted to grayscale to simplify the detection process.
Face Detection: OpenCV's detectMultiScale method is used to detect faces. Detected faces are returned as rectangles with coordinates.
Mark Faces: Rectangles are drawn around detected faces on the original image.
Display Results: The image with the detected faces is displayed using Matplotlib.
