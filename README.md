# Real-Time-Face-and-Eye-Detection-with-Alerts
A Python-based real-time face and eye detection system utilizing OpenCV to analyze video streams, track blinks, and monitor face positions. This system triggers alerts for prolonged eye closure, face absence, or off-center positions, ensuring continuous real-time feedback.

# Features
Detects faces and eyes in real-time using a webcam feed.
Tracks blinks and computes the number of blink events.
Determines face positions (Left, Middle, Right) relative to the frame.
Generates alerts for:
Prolonged eye closure beyond a threshold.
Face absence for a predefined duration.
Staying in Left or Right positions for extended periods.
Visual feedback through overlays displaying:
Blink counts.
Face position.
Alert buttons for critical conditions.
# Project Link
Check out the live code implementation on Google Colab in real-time Detection: [Project Code Link](https://colab.research.google.com/drive/1tjo-YXL7jvLfSJRJ6r38-nQLeZDPYIks?usp=sharing)
Check out the live code implementation on Google Colab using image as input for Detection the person's eye and position : [Project Code Link](https://colab.research.google.com/drive/1P95uk-lRKsATCuXK4_LKEhRlaRtt424W?usp=sharing)


# System Architecture
Input: Webcam video stream.
Processing:
Frame preprocessing (grayscale conversion).
Face and eye detection using Haar Cascade Classifiers.
Blink and position analysis.
Output: Frames with overlays showing alerts and feedback.
Alert Logic: Threshold checks for prolonged eye closure, face absence, and off-center positions.
# Setup Instructions
Prerequisites
Python 3.x
OpenCV Library
NumPy
# Installation
Clone the repository or download the code.

git clone https://github.com/your-repository-link.git
Install the required Python libraries.

pip install opencv-python numpy
Run the code using Google Colab (recommended) or a local Python environment.

# Usage
Launch the script in your preferred Python environment or open the Google Colab link.
Allow access to your webcam when prompted.
Observe real-time feedback and alerts directly on the video stream.
# Project Workflow
Input: Captures real-time video frames from the webcam.
Processing: Detects faces and eyes, tracks blink events, and determines face position.
Output: Displays processed frames with overlays for blink count, position, and alerts.
# Contributing
Feel free to fork this repository and submit pull requests for improvements or new features.

# License
This project is licensed under the MIT License.

# Author
Shaili Sahu

For questions or feedback, reach out to me at shailisahu283@gmail.com.
