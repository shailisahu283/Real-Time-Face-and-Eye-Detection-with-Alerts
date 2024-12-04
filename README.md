# **📸 AI-Driven Driver Monitoring System: Real-Time Face and Eye Detection with Alerts**  
A Python-based system using OpenCV to detect faces and eyes in real time, track blinks, monitor face positions, and provide continuous feedback. 🚨 Alerts are triggered for prolonged eye closure, face absence, or off-center face positions.  

---

## **📑 Table of Contents**  
1. [✨ Features](#features)  
2. [📂 System Architecture](#system-architecture)  
3. [🛠️ Project Workflow](#project-workflow)  
4. [⚙️ Setup Instructions](#setup-instructions)  
5. [▶️ Usage](#usage)  
6. [🔗 Project Links](#project-links)  
7. [🌟 Output Examples](#output-examples)  
8. [🤝 Contributing](#contributing)  
9. [📜 License](#license)  
10. [👤 Author](#author)  

---

## **✨ Features**  
- **🎥 Real-Time Detection:** Uses webcam feed to detect faces and eyes in real time.  
- **👁️ Blink Tracking:** Counts blinks and analyzes eye closure duration.  
- **📍 Face Position Monitoring:** Detects if the face is centered, left, or right relative to the frame.  
- **⚠️ Alert Mechanism:**  
  - Triggers alerts for prolonged eye closure beyond a threshold.  
  - Detects face absence for a predefined duration.  
  - Alerts for prolonged left or right face positions.  
- **🖼️ Visual Feedback:**  
  - Displays blink count and face position.  
  - Provides on-screen alert indicators.  

---

## **📂 System Architecture**  
### **Input**  
- 🎥 Webcam video stream or preloaded images.  

### **Processing**  
- 🖤 Grayscale frame preprocessing.  
- 🧠 Face and eye detection using Haar Cascade Classifiers.  
- 📊 Blink and position analysis using threshold-based logic.  

### **Output**  
- ✅ Real-time overlays displaying:  
  - Blink count.  
  - Face position.  
  - Alerts for critical conditions.  

---

## **🛠️ Project Workflow**  
1. **📥 Input:**  
   Captures real-time video frames from the webcam.  

2. **⚙️ Processing:**  
   - Detects faces and eyes in the frame.  
   - Tracks blink events and face positions.  
   - Implements alert logic based on thresholds.  

3. **📤 Output:**  
   Displays processed frames with:  
   - Blink count overlays.  
   - Face position indicators.  
   - Real-time alert feedback.  

---

## **⚙️ Setup Instructions**  
### **Prerequisites**  
- 🐍 Python 3.x  
- 🖥️ OpenCV Library  
- 🔢 NumPy  

### **Installation Steps**  
1. Install Python and required libraries:  
   ```bash
   pip install opencv-python-headless numpy
   ```  
2. Download the pre-trained model for image-based detection:  
   - Dataset: `shape_predictor_68_face_landmarks.dat`  
   - [📥 Download Link](http://dlib.net/files/shape_predictor_68_face_landmarks.dat.bz2)  

---

## **▶️ Usage**  
1. Run the script in a Python environment or open the Google Colab notebook.  
2. 🎥 Allow webcam access when prompted.  
3. 🚀 Observe real-time feedback and alerts displayed on the video stream.  

---

## **🔗 Project Links**  
- **🔴 Real-Time Detection:** [Colab Notebook](https://colab.research.google.com/drive/1tjo-YXL7jvLfSJRJ6r38-nQLeZDPYIks?usp=sharing)  
- **🖼️ Image-Based Detection:** [Colab Notebook](https://colab.research.google.com/drive/1P95uk-lRKsATCuXK4_LKEhRlaRtt424W?usp=sharing)  

---

## **🌟 Output Examples**  
🎨 Below are some examples of the system in action:  

### **1. Real-Time Detection:**  
![Screenshot 2024-11-17 223357](https://github.com/user-attachments/assets/e0883ac8-b979-406b-b90e-cfcb64f86190)

### **2. Alerts for Critical Events:**  
![Screenshot 2024-11-17 223457](https://github.com/user-attachments/assets/3beda625-07d6-4abe-ab28-8d8245b7ea34)


### **3. Visual Feedback with Overlays:**  
![Screenshot 2024-11-17 223521](https://github.com/user-attachments/assets/b9481721-ea7e-424f-ab3a-c34783136321)
 

---

## **🤝 Contributing**  
Contributions are welcome! 🙌  
- Fork this repository.  
- Make your changes or add features.  
- Submit a pull request for review.  

---

## **📜 License**  
This project is licensed under the [MIT License](LICENSE).  

---

## **👤 Author**  
**Shaili Sahu**  
📧 Reach out at [shailisahu283@gmail.com](mailto:shailisahu283@gmail.com) for questions or feedback!  

