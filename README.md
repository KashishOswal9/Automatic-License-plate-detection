# Automatic-License-plate-detection
Number Plate Detection using OCR
In this project, I used Python, OpenCV, and EasyOCR to detect and read number plates from vehicles in both images and videos. A complete image processing and OCR pipeline was developed to localize license plates, extract text, and display it clearly on the output frame.

📌 The Project
The goals/steps of this project are the following:

Detect and isolate the number plate region using contour analysis

Preprocess the cropped region to enhance text readability

Use EasyOCR to extract alphanumeric characters from the number plate

Draw bounding boxes around detected number plates

Overlay the recognized number plate text clearly below the car for better visibility

Save the output as an image or video with annotations

The input images are stored in the current directory. You can test the pipeline on both static images and video clips.

🎬 Sample Output


The text is extracted using OCR and displayed in readable format below the vehicle, solving the issue of poor visibility due to glare, font, or distance.

🧪 The Environment
Windows 10 / Google Colab

Python 3.10.10

OpenCV 4.7.0

EasyOCR 1.6.2

imutils

NumPy

🎯 Conclusion
This project demonstrates how computer vision and OCR can be combined to build an automated number plate detection system. It can be further extended for real-time applications like:

Automated Toll Collection

Parking Management Systems

Traffic Violation Detection

Surveillance and Security

