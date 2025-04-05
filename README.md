
---

# Face Detection with Haar Cascade using Python

This project is a basic implementation of a **Face Detector** using **Haar Cascade Classifiers** in **Python (Jupyter Notebook)**. It includes detection of **faces**, **eyes**, and **smiles** from static images or live video streams using OpenCV.

## Project Status

🚧  **Status** : `Completed!`

## Project Overview

- Language: **Python**
- Tools: **Jupyter Notebook**
- Technique: **Haar Cascade Classifier**
- Focused Detection:  
  ✅ Face  
  ✅ Eyes  
  ✅ Smiles

## Project Flow

1. Load Haar Cascade Classifier XML files.
2. Read and process image or video frame.
3. Convert to grayscale.
4. Detect face, eyes, and smile using respective cascade classifiers.
5. Annotate the detections using matplotlib for visualization.

## Libraries Used

```python
import numpy as np
import cv2
import matplotlib.pyplot as plt
import matplotlib.patches as mpatches
plt.rcParams['figure.figsize'] = [15, 30]
```

##  Tools / Classifiers Used

You can download and use the following Haar Cascade XML classifiers:

```bash
# Face detector
!wget "https://raw.githubusercontent.com/opencv/opencv/master/data/haarcascades/haarcascade_frontalface_default.xml" -O haarcascade_frontalface_default.xml

# Eye detector
!wget "https://raw.githubusercontent.com/opencv/opencv/master/data/haarcascades/haarcascade_eye.xml" -O haarcascade_eye.xml

# Smile detector
!wget "https://raw.githubusercontent.com/opencv/opencv/master/data/haarcascades/haarcascade_smile.xml" -O haarcascade_smile.xml
```

## How to Run

You can either:
- Run the notebook **altogether**, or
- **Block-run** each section of the notebook for step-by-step visualization and analysis.

## Output Example

The script will output:
- Detected faces marked with rectangles.
- Detected eyes and smiles within the face area.
- Optional live video capture detection if webcam is enabled.

---

> **Note:** Make sure OpenCV (`cv2`) is installed and the XML files are present in your working directory before running the code.

---
