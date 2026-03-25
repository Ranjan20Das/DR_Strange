# 🌀 Doctor Strange Hand Gesture Control

A real-time computer vision project that detects hand gestures and creates a **Doctor Strange-style magic circle effect** using webcam input.

---

##Live demo

 if you want to see the demo download the raw video file provided in the repo, to see the output

## 🚀 Features

* ✋ Real-time hand tracking
* 🔥 Gesture-based activation
* ⚡ Energy line visualization
* 🌀 Rotating magic circle overlay
* 🎥 Live webcam processing

---

## 🛠️ Tech Stack

* Python
* OpenCV
* MediaPipe
* NumPy

---

## 📁 Project Structure

```
Doctor-Strange-Hand-Gesture/
│
├── main.py
├── requirements.txt
├── magic_circles/
│   ├── magic_circle_1.png
│   ├── magic_circle_2.png
│
└── README.md
```

---

## ⚙️ Requirements

* Python **3.8 – 3.11** (Recommended: 3.10)
* Webcam

---

## 📦 Installation

```bash
git clone https://github.com/your-username/Doctor-Strange-Hand-Gesture.git
cd Doctor-Strange-Hand-Gesture
pip install -r requirements.txt
```

---

## ▶️ Run the Project



```bash
python main.py
```

Press **Q** to exit.

---

## 🧠 How It Works

* Uses **MediaPipe** to detect 21 hand landmarks
* Calculates distances between key points
* Determines gesture based on ratio
* Triggers:

  * Energy lines ✨
  * Magic circle 🌀

---

## 🎯 Gesture Logic

| Gesture           | Action       |
| ----------------- | ------------ |
| Fingers semi-open | Energy lines |
| Hand wide open    | Magic circle |

---

## ⚠️ Notes

* Make sure the `magic_circles` images exist
* Works best in good lighting
* Requires webcam access

---



---

## 🚀 Future Improvements

* 🔊 Add sound effects
* 🎮 More gesture controls
* 🌐 Web version (Flask / React)
* 📱 Mobile support

---

## 👨‍💻 Author

**Ranjan Das**

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!
