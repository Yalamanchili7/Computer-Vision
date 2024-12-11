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
Installation
Clone this repository to your local machine to get started with the face detection project:

bash
Copy code
git clone https://your-repository-url.git
cd your-repository-folder
Structure
face_detection.py: The Python script for detecting faces in an image.
haarcascade_frontalface_default.xml: XML file for the Haar Cascade classifier used to detect faces.
Usage
Replace the Image.png path in the script with the path to your target image.
Run the script from your command line:
bash
Copy code
python face_detection.py
The script will load the image, perform face detection, and display the image with detected faces highlighted.

How It Works
Load Classifier: The Haar Cascade haarcascade_frontalface_default.xml is loaded using OpenCV's CascadeClassifier.
Image Processing: The image is read and converted to grayscale to simplify the detection process.
Face Detection: OpenCV's detectMultiScale method is used to detect faces. Detected faces are returned as rectangles with coordinates.
Mark Faces: Rectangles are drawn around detected faces on the original image.
Display Results: The image with the detected faces is displayed using Matplotlib.
Contributing
Contributions are welcome! Please fork this repository and open a pull request to add more features, fix bugs, or suggest improvements.

License
This project is released under the MIT License. See the LICENSE file for more details.
### How It Works
Load Classifier: The Haar Cascade haarcascade_frontalface_default.xml is loaded using OpenCV's CascadeClassifier.
Image Processing: The image is read and converted to grayscale to simplify the detection process.
Face Detection: OpenCV's detectMultiScale method is used to detect faces. Detected faces are returned as rectangles with coordinates.
Mark Faces: Rectangles are drawn around detected faces on the original image.
Display Results: The image with the detected faces is displayed using Matplotlib.
