# lane-detection-opencv
This project implements a basic lane detection system using classical computer vision techniques. It processes road images to identify lanes lines using grayscale conversion, edge detection (Canny)., region of internest masking, and the Hough Line Transform


# 🚗 Lane Detection with OpenCV

This project implements a basic lane detection system using classical computer vision techniques. It simulates a fundamental component of a self-driving car pipeline — detecting lane lines from road images using edge detection and line estimation.

---

## 📌 Features

- Grayscale conversion
- Canny edge detection
- Region of interest (ROI) masking
- Hough Line Transform for lane detection
- Visual output with detected lane lines overlayed

---

## 🧠 What I Learned

- Basics of image processing using OpenCV
- How Canny edge detection isolates important features
- How to mask an image using NumPy and geometry
- Applying the Hough Transform to detect lines
- Building a simple computer vision pipeline from scratch

---

## 🖼️ Sample Output

| Original Image | Lane Detection |
|----------------|----------------|
| ![original](test_image.jpg) | ![output](output_image.jpg) |

---

## 🚀 Getting Started

### 1. Clone the repo
```bash
git clone https://github.com/yourusername/lane-detection-opencv.git
cd lane-detection-opencv
