# Drowsiness-Detection-System
Real-time drowsiness detection using computer vision and deep learning.

#  Drowsiness Detection System using Deep Learning and Computer Vision

##  Project Overview

This project implements a **real-time driver drowsiness detection system** using a **CNN (Convolutional Neural Network)** and **OpenCV** for facial and eye state detection.

The system monitors the driver's eyes through a webcam feed, predicts eye state (open/closed), and triggers an audio alarm if prolonged eye closure (drowsiness) is detected.

---

## ✅ Features

* Real-time webcam monitoring
* Eye state classification using a trained CNN model
* Drowsiness detection based on eye closure duration
* Audio alert using Pygame and Playsound
* Face and eye detection using Haar cascades and dlib facial landmark detection

---

## 📂 Project Structure

```
Drowsiness-Detection-System/
├── drowsiness_detection.py
├── models/
│   └── cnncat2.h5
├── haar cascade files/
│   ├── haarcascade_frontalface_alt.xml
│   ├── haarcascade_lefteye_2splits.xml
│   └── haarcascade_righteye_2splits.xml
├── shape_predictor_68_face_landmarks.dat
├── README.md
└── requirements.txt
```

---

## 🛠️ Technologies Used

* Python 3.8
* TensorFlow / Keras
* OpenCV
* dlib
* NumPy
* Pygame
* Playsound

---

## 📥 Installation and Setup

1. **Clone the repository:**

```bash
git clone https://github.com/krupajshetty/Drowsiness-Detection-System.git
cd Drowsiness-Detection-System
```

2. **Create and activate virtual environment (optional but recommended):**

```bash
python -m venv drowsy_env
.\drowsy_env\Scripts\activate
```

3. **Install dependencies:**

```bash
pip install -r requirements.txt
```

*(Or manually install packages: numpy, opencv-python, dlib, tensorflow==2.5.1, keras==2.4.3, pygame, playsound, etc.)*

4. **Download required model files:**

* **CNN Model:** Place `cnncat2.h5` in `models/` folder
* **Haar Cascades:** Place all XML files in `haar cascade files/`
* **Dlib Shape Predictor:** Place `.dat` file in project root

---

## ▶️ Running the System

```bash
python drowsiness_detection.py
```

Webcam will launch, and the system will start monitoring eye states.

---

## 📸 Output Screenshots
![image](https://github.com/user-attachments/assets/0753e4d2-f69d-47b8-939d-c5b90666ed36)

---

---

## ✅ Future Improvements

* Deploy as a desktop app or web app
* Integrate yawning detection for better accuracy
* Optimize for mobile deployment

---

## 👩‍💻 Author

Krupa J Shetty
[GitHub Profile](https://github.com/krupajshetty)

