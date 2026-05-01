# Biscuit-Detection-Assignment
Broken and Intact Biscuit Detection using Image Processing
# 🍪 Broken Biscuit Detection using Image Processing

## 📌 Project Description
This project detects whether biscuits are **intact or broken** using classical image processing techniques. The system processes images of biscuits placed on a white background and automatically identifies each biscuit.

---

## 🛠 Tools and Libraries
- Python
- OpenCV
- NumPy

---

## 🧠 Methods Used
The following classical image processing techniques were used:

- Image resizing
- Grayscale conversion
- HSV color segmentation
- Adaptive thresholding
- Edge detection (Canny)
- Morphological operations (Open, Close)
- Contour detection
- Shape analysis (circularity, solidity, extent)

---

## 🔍 Detection Logic

Each biscuit is classified using:

- **Circularity** → Detect round biscuits  
- **Aspect Ratio** → Detect square biscuits  
- **Solidity** → Detect broken edges  
- **Extent** → Shape fullness  
- **Missing Area Ratio** → Broken parts  

---

## 🖼 Input Images
Images were captured using:
- Top view
- White A4 background
- Good lighting
- Mixed broken and intact biscuits

---

## 📤 Output
Each biscuit is:
- Detected using contours
- Labeled as:
  - ✅ Intact Biscuit
  - ❌ Broken Biscuit
- Annotated with bounding boxes

---

## ▶️ How to Run

1. Install dependencies:
```bash
pip install opencv-python numpy matplotlib
