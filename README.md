# ✋ Hand Gesture Calculator

A real-time calculator controlled entirely through hand gestures using **Python**, **OpenCV**, and **MediaPipe**. This project turns your webcam into an interactive input device that reads finger counts and hand positions to build and evaluate mathematical expressions — no keyboard or mouse needed!

---

## 🧠 Project Overview

This application uses your **hand gestures** to perform basic arithmetic calculations. It leverages computer vision and machine learning to:

- Detect hands in real-time
- Count fingers to determine digits (0–9)
- Detect finger pointing to select arithmetic operators
- Use open palms to confirm inputs
- Use closed fists with both hands to evaluate the final result

This is an experimental project to explore how hand gestures can serve as an input method.

---

## 🔍 Features

- ✅ Real-time hand tracking using MediaPipe  
- ✅ Finger counting to input numbers  
- ✅ Operator selection by pointing the finger(`+`, `-`, `*`, `/`)  
- ✅ Expression confirmation with open palm  
- ✅ Evaluation trigger with both fists  
- ✅ Support for reset (`R`), delete (`D`), and decimal input (`.`)  
- ✅ Visual UI feedback using OpenCV overlays

---

## 📸 Demo

Soon to be uploaded....

---

### 📦 Prerequisites

Make sure you have Python 3.7+ , MediaPipe and OpenCV installed.

---

## 🎮 How to Use
### Input Zones:
- Left Box (Input 1): Show fingers (0–5) using left hand

- Right Box (Input 2): Show fingers (0–5) using right hand

### Operator Buttons:
- Point your left index finger at any of the buttons to select:

- +, -, *, / → Math operations

- R → Reset full expression

- D → Delete last character

- . → Add a decimal point

### Confirming Input:

- ✋ Open right palm in the green box to confirm current digit/operator

- ✊ Make fists with both hands to evaluate the full expression

### 🛠️ Customization Ideas:

- Add voice feedback

- Use face mesh or eye blink detection for hands-free confirmation





