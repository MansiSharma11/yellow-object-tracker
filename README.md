# 🟡 Yellow Object Tracker

A **real-time computer vision project** that detects and tracks **yellow-colored objects** using **OpenCV** and **Python**.  
The program uses **HSV color masking** to identify the target color and draws a **bounding box** around detected objects via your webcam feed.

---

## 📸 Demo
*(Add a screenshot or GIF of the detection in action here)*  
Example:  
![Yellow Object Detection Demo](demo.gif)

---

## 🚀 Features
- 🎯 Detects **yellow objects** in real time
- 📦 Uses **HSV color space** for better accuracy than RGB
- 🖼 Draws **bounding boxes** around detected objects
- ⚡ Lightweight and easy to customize for other colors
- 🔄 Runs directly from your webcam feed

---

## 📂 Project Structure
```
yellow-object-tracker/
│
├── Color_Detection.py   # Main script to run detection
├── util.py              # Utility functions (HSV range calculation)
└── README.md            # Project documentation
```
---

## 🛠 Installation & Setup

### 1️⃣ Clone this repository
```bash
git clone https://github.com/yourusername/yellow-object-tracker.git
cd yellow-object-tracker
```

### 2️⃣ Install dependencies
Make sure you have **Python 3.7+** installed.  
Then install required packages:
```bash
pip install -r requirements.txt
```

### 3️⃣ Run the project
```bash
python Color_Detection.py
```

---

## 🎨 Customization
Want to track a different color?  
Open **`Color_Detection.py`** and change:
```python
yellow = [0, 255, 255]  # BGR values for yellow
```
Replace with the **BGR** value of your desired color.  
You can use [this color picker](https://colorpicker.me/) to get values.

---

## ⌨️ Controls
- **`q`** → Quit the program
