# Posturize: Real-Time Posture & Push-up Tracker

**Posturize** is a real-time posture correction and fitness tracking tool that leverages computer vision and AI to ensure you're maintaining the right posture while sitting, standing, or doing push-ups. Whether you're at your desk or at the gym, Posturize helps you track your reps and correct your form instantly.

---

## 🚀 Features

- 🧍 **Posture Recognition**  
  Detects slouching, improper leg position, and poor alignment.

- 🪑 **Sitting Posture Detection**  
  Identifies if you're sitting and evaluates your back posture.

- 🏋️ **Push-up Detection**  
  Tracks push-up reps using elbow angles.

- 📈 **Posture Accuracy Score**  
  Shows percentage accuracy of your form in real-time.

- 🔁 **Live Feedback Overlay**  
  Displays posture feedback and push-up count directly on the webcam feed.

---

## 📂 Folder Structure

```
Posturize/
├── main.py              # Main script for posture & push-up tracking
├── requirements.txt     # Python dependencies
└── README.md            # Project documentation
```

---

## 🧠 Tech Stack
- **Python 3.8+**
- **OpenCV** – For real-time webcam capture and UI overlay.
- **MediaPipe** – For pose landmark detection.
- **NumPy** – For angle calculation and mathematical processing.

---

## ⚙️ Installation

1. **Clone the repository**:
```bash
git clone https://github.com/yourusername/Posturize.git
cd Posturize
```

2. **Install dependencies**:
```bash
pip install -r requirements.txt
```

3. **Run the tracker**:
```bash
python main.py
```

4. **Press `q` to quit the camera window.**

---

## 📋 How It Works

- **Back Angle** is calculated using shoulder, hip, and knee points.
- **Sitting** is detected when the hip is lower than the shoulder.
- **Push-ups** are counted based on elbow angle transitions.
- **Accuracy** drops when posture falls outside the healthy range.

---

## 🎯 Use Cases
- Desk job posture awareness
- Fitness training & form correction
- Physiotherapy and rehab assistance

---

## ✅ Future Improvements
- Add support for squats and planks
- Create a Streamlit dashboard
- Generate posture correction reports
- Audio alerts for posture deviation

---

Made with ❤️ by Harshith YVS
