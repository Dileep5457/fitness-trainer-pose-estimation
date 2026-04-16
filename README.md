# 🏋️ AI Gym Trainer using Pose Estimation

An intelligent **AI-powered fitness trainer** that uses computer vision to track exercises, count repetitions, and provide real-time posture feedback — all through your webcam.

---

## 🚀 Overview

This project leverages **pose estimation and computer vision** to act as a virtual gym trainer. It detects human body movements, calculates joint angles, and ensures correct exercise form.

🎯 **Key Idea:** Replace manual fitness tracking with an automated AI-based system.

---

## 🧠 Technologies Used

* **Python**
* OpenCV – Real-time video processing
* MediaPipe – Human pose detection
* NumPy – Mathematical computations

---

## ⚙️ Features

✅ Real-time pose detection
✅ Automatic repetition counting
✅ Exercise form correction feedback
✅ Multiple exercise support
✅ Lightweight and easy to run
✅ Modular and scalable code structure

---

## 🏋️ Supported Exercises

### 💪 Bicep Curl

* Tracks elbow angle
* Counts reps based on arm movement

### 🧍 Squats

* Monitors knee angle
* Ensures proper depth and posture

### 🏋️ Shoulder Press

* Detects arm extension
* Ensures full range of motion

### 🤸 Push-ups

* Tracks elbow bending
* Checks full body alignment

---

## 🧩 Project Structure

```
AI-Gym-Trainer/
│
├── main.py              # Entry point of application
├── trainer.py           # Core logic (pose detection + counting)
├── angle_utils.py       # Angle calculation & smoothing
├── pose_feedback.py     # Posture validation & feedback
├── requirements.txt     # Dependencies
└── README.md
```

---

## 🔄 Workflow

1. Capture video using webcam
2. Detect body landmarks using MediaPipe
3. Calculate joint angles
4. Apply logic to detect exercise stages
5. Count repetitions
6. Provide real-time feedback

---

## 📐 Angle Calculation

Joint angles are calculated using vector mathematics:

$$
\theta = \cos^{-1}\left(\frac{BA \cdot BC}{|BA||BC|}\right)
$$

This helps determine movement stages (e.g., curl up/down).

---

## ▶️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/ai-gym-trainer.git
cd ai-gym-trainer
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Project

```bash
python main.py
```

---

## 💡 Usage

* Select an exercise (e.g., curl, squat)
* Position yourself in front of the webcam
* Perform the exercise
* View real-time counter and feedback on screen

---

## ⚠️ Limitations

* Requires proper lighting
* Sensitive to camera angle
* Works best for a single user
* Limited to predefined exercises

---

## 🚀 Future Enhancements

* AI-based exercise classification (ML model)
* Mobile application integration
* Voice feedback system
* Calorie tracking
* Multi-user detection

---

## 👨‍💻 My Contribution

* Implemented pose detection using MediaPipe
* Designed angle calculation module
* Developed repetition counting logic
* Integrated real-time feedback system

---

## 📌 Applications

* Home fitness training
* Gym assistance systems
* Rehabilitation monitoring
* Sports performance analysis

---

## ⭐ Why This Project?

This project demonstrates practical implementation of:

* Computer Vision
* Real-time AI systems
* Human pose estimation

It solves a real-world problem by making fitness training **accessible, affordable, and automated**.

---

## 📜 License

This project is open-source and available under the MIT License.

---

## 🙌 Acknowledgements

* Google MediaPipe Team
* OpenCV Community

---

## 📬 Contact

For queries or collaboration:

* GitHub: https://github.com/Dileep5457

---
