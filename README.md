# ✋ Hand Tracking Toolkit

A Python-based computer vision toolkit using **OpenCV** and **Mediapipe** to perform real-time hand tracking, gesture recognition, and volume control using hand gestures.

---

## 📁 Project Structure

```
.
├── HandTracking.py            # Entry script to visualize hand tracking
├── HandTrackingModule.py      # Reusable hand tracking class (uses Mediapipe)
├── VolumeControl.py           # Adjusts system volume via hand gestures
├── utils.py                   # Utility functions (e.g., distance calc)
├── .gitignore                 # Git ignore rules
└── __pycache__/               # Python cache directory
```

---

## 🧠 Features

- 🖐️ **Hand Tracking** with Mediapipe in real time
- 🔊 **Volume Control** using finger distance
- 🧩 Modular structure for easy reuse and scaling
- ⚙️ Utility functions for distance measurement, drawing, etc.

---

## 🚀 Getting Started

### 📦 Requirements

- Python 3.7+
- OpenCV
- Mediapipe
- Numpy
- Pycaw (for controlling system volume on Windows)

### 📥 Install dependencies

```bash
pip install opencv-python mediapipe numpy pycaw
```

---

## ▶️ How to Run

### Hand Tracking Demo

```bash
python HandTracking.py
```

### Volume Control via Hand Gestures

```bash
python VolumeControl.py
```

Use your thumb and index finger to increase/decrease the volume by adjusting their distance.

---

## 🛠️ File Details

- **HandTrackingModule.py**: Contains the `HandDetector` class that handles hand detection, landmark drawing, and landmark position extraction using Mediapipe.
- **utils.py**: Helper methods like calculating distance between points, angle computations, or drawing stylized UI overlays.
- **VolumeControl.py**: Uses finger positions (e.g., thumb & index finger) to control system volume with Pycaw.

---

## 🤝 Contributing

Pull requests are welcome! If you'd like to add new gestures or improve detection, feel free to fork and contribute.
