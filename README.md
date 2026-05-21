# 🎨 Live Camera Drawing using OpenCV

> A real-time color-tracking drawing application that uses your camera to detect colored objects and paint their trails onto a persistent virtual canvas — no mouse or stylus required.

---

## 📚 Table of Contents

1. [Project Overview](#1-project-overview)
2. [Features](#2-features)
3. [Prerequisities & Dependencies](#3-prerequisities--dependencies)
4. [Project Structure](#4-project-structure)
5. [License](#5-license)

---

## 1. Project Overview

This script transforms a standard camera into an **air-drawing instrument**. By holding a colored object (such as a marker cap, a painted fingertip, or a colored ball) in front of the camera, users can draw freehand strokes on a live video feed. This script tracks up to **four distinct colors simultaneously**, each assigned its own drawing color, and accumulates all drawn points on a persistent canvas that updates in real time.

---

## 2. Features

- ✅ Tracks up to **4 colored objects** simultaneously in real time.
- ✅ Each color leaves a **persistent drawing trail** on the live video frame.
- ✅ Configurable HSV color ranges for any physical object color.
- ✅ Adjustable camera resolution and brightness.
- ✅ Lightweight — runs entirely on CPU with no GPU or Deep Learning required.
- ✅ Single-file script, easy to modify and extend.

---

## 3. Prerequisities & Dependencies

### Python Version

Python **3.7 or higher** is required.

### Installation

```bash
pip install opencv-python numpy
```

For headless environments (no display):

```bash
pip install openvc-python-headless numpy
```

---

### 4. Project Structure

```
live-camera-drawing/
│
├── live_camera_drawing_using_opencv.py   ← Main script (entry point)
└── README.md                             ← This documentation file
```

No dataset, model file, or additional resource is required. Everything runs from a single Python file and your camera.

---

### 5. License

This project is released for educational and experimental use. OpenCV is distributed under the **Apache 2.0 License**. NumPy is distributed under the **BSD License**.