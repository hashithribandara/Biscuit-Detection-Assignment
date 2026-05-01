# Biscuit-Detection-Assignment
Broken and Intact Biscuit Detection using Image Processing
# 🍪 Broken Biscuit Detection using Image Processing


## 📌 Problem Description
This project detects biscuits in images and classifies them as either **Intact Biscuit** or **Broken Biscuit**.

The system uses **classical image processing techniques** to identify biscuit regions, analyze their shapes, and annotate the results.  
⚠️ Machine Learning and Deep Learning methods were **not used**, as per assignment requirements.

---

## 📂 Dataset
The dataset consists of images containing:
- Round biscuits
- Square biscuits  

All biscuits are placed on a **white A4 sheet** and captured from a **top view**.

Each image includes:
- Multiple biscuits
- A mix of **intact and broken biscuits**
- Different arrangements for variation

📁 Input images are stored in:input images/

---

## 🛠 Tools and Libraries
- Python  
- OpenCV  
- NumPy  
- Jupyter Notebook (Anaconda)

---

## 🧠 Methods Used
The following classical image processing techniques were applied:

- Image resizing  
- Color detection using HSV color space  
- Color thresholding  
- Morphological operations (Opening, Closing)  
- Contour detection  
- Shape analysis using:
  - Circularity  
  - Aspect ratio  
  - Solidity  
  - Extent  
  - Missing area ratio  
- Rotated bounding box analysis (for square biscuits)

---

## ⚙️ Detection Approach
The system performs the following steps:

1. Preprocess the image (resize and color conversion)  
2. Segment biscuit regions using HSV thresholding  
3. Apply morphological operations to remove noise  
4. Detect contours representing biscuits  
5. Extract shape features from each contour  
6. Classify each biscuit as:
   - ✅ Intact Biscuit  
   - ❌ Broken Biscuit  
7. Draw bounding boxes and labels on output images  

---

## ▶️ How to Run

1. Open **Anaconda Prompt**

2. Activate your environment:
```bash
conda activate ee4216
3. Launch Jupyter Notebook:
jupyter notebook
4. Open:
biscuit_detection.ipynb
5. Run all cells
## 📤 Output

The processed images are saved in the `output images` folder.

Each image contains:
- Bounding boxes around detected biscuits
- Labels indicating:
  - Intact Biscuit
  - Broken Biscuit

All biscuits in the image are detected and classified based on their shape.

The output images are clear and easy to understand, showing only the final detection results.
