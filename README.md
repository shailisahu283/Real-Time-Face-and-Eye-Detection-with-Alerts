# Real-Time-Face-and-Eye-Detection-with-Alerts
A Python-based real-time face and eye detection system utilizing OpenCV to analyze video streams, track blinks, and monitor face positions. This system triggers alerts for prolonged eye closure, face absence, or off-center positions, ensuring continuous real-time feedback.

# Features
Detects faces and eyes in real-time using a webcam feed.<br/>
Tracks blinks and computes the number of blink events.<br/>
Determines face positions (Left, Middle, Right) relative to the frame.<br/>
Generates alerts for:<br/>
Prolonged eye closure beyond a threshold.<br/>
Face absence for a predefined duration.<br/>
Staying in Left or Right positions for extended periods.<br/>
Visual feedback through overlays displaying:<br/>
Blink counts.<br/>
Face position.<br/>
Alert buttons for critical conditions.<br/>
# Project Link
Check out the live code implementation on Google Colab in real-time Detection: [Project Code Link](https://colab.research.google.com/drive/1tjo-YXL7jvLfSJRJ6r38-nQLeZDPYIks?usp=sharing)<br/>
Check out the live code implementation on Google Colab using image as input for Detection the person's eye and position : [Project Code Link](https://colab.research.google.com/drive/1P95uk-lRKsATCuXK4_LKEhRlaRtt424W?usp=sharing)<br/>


# System Architecture
Input: Webcam video stream.<br/>
Processing:<br/>
Frame preprocessing (grayscale conversion).<br/>
Face and eye detection using Haar Cascade Classifiers.<br/>
Blink and position analysis.<br/>
Output: Frames with overlays showing alerts and feedback.<br/>
Alert Logic: Threshold checks for prolonged eye closure, face absence, and off-center positions.<br/>
# Setup Instructions
Prerequisites<br/>
Python 3.x<br/>
OpenCV Library<br/>
NumPy<br/>
# Installation

Install the required Data Set For using image as input for Detection the person's eye and position.<br/>
Data set name : shape_predictor_68_face_landmarks.dat<br/>

# Usage
Launch the script in your preferred Python environment or open the Google Colab link.<br/>
Allow access to your webcam when prompted.<br/>
Observe real-time feedback and alerts directly on the video stream.<br/>
# Project Workflow
Input: Captures real-time video frames from the webcam.<br/>
Processing: Detects faces and eyes, tracks blink events, and determines face position.<br/>
Output: Displays processed frames with overlays for blink count, position, and alerts.<br/>
# Contributing
Feel free to fork this repository and submit pull requests for improvements or new features.<br/>

# License
This project is licensed under the MIT License.<br/>

# Author
Shaili Sahu<br/>

For questions or feedback, reach out to me at shailisahu283@gmail.com.<br/>
