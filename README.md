# 3-Sem_project_openCV-and-python

# 🎨 OpenCV Air Drawing – Virtual Paint

## 📌 About the Project

**OpenCV Air Drawing – Virtual Paint** is a real-time drawing application developed using Python and OpenCV. It allows users to draw on the screen using a colored object, such as a blue marker, detected through a webcam.

The application tracks the movement of the colored object and converts its movement into digital drawings. Users can select different drawing colors and clear the canvas whenever they want.

This project was created to learn and practice computer vision, color detection, and real-time object tracking using OpenCV.

## ✨ Features

- 📷 **Real-Time Webcam Detection:** Detects a colored object using the webcam.
- 🎨 **Multiple Drawing Colors:** Supports blue, green, red, and yellow drawing colors.
- ✍️ **Air Drawing:** Draw or write anything by moving a colored object in front of the camera.
- 🧹 **Clear Canvas:** Erase the drawing using the CLEAR button.
- 🎯 **Color Detection:** Uses HSV color space and adjustable trackbars to detect the target color.
- 🖥️ **Live Drawing Window:** Displays the webcam feed and drawing canvas in real time.
- 🔍 **Image Processing:** Uses erosion, dilation, and morphological operations to improve color detection.

## 🛠️ Technologies Used

- **Python** – Main programming language
- **OpenCV (cv2)** – Image processing, webcam access, and object tracking
- **NumPy** – Array operations and image processing
- **Collections (deque)** – Stores drawing points for smooth line rendering

## ⚙️ Requirements

- Python 3.x
- OpenCV
- NumPy
- A working webcam
- A blue-colored marker or another object matching the selected HSV color range

## 📥 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/kunalkhode26-lab/opencv-air-drawing.git
```

### 2. Open the Project Folder

```bash
cd opencv-air-drawing
```

### 3. Install the Required Libraries

```bash
pip install opencv-python numpy
```

## ▶️ How to Run

Run the Python script from your terminal:

```bash
python air_drawing.py
```

Replace `air_drawing.py` with the actual name of your Python file if it is different.

## 🖌️ How to Use

1. Connect your webcam and run the program.
2. Hold a blue marker or a colored object in front of the camera.
3. Adjust the HSV trackbars in the **Color
