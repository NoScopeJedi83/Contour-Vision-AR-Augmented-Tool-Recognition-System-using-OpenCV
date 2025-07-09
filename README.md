# 🧠 ContourVision AR: Augmented Tool Recognition System using OpenCV

**ContourVision AR** is a real-time object detection system built using **YOLOv3** and **OpenCV**, designed for **augmented tool recognition** through webcam input — seamlessly integrated with **Google Colab** and JavaScript. It showcases how deep learning and computer vision can be deployed with minimal setup for smart, real-world use.

> 📌 **Major & Minor Final Year Project**  
> 📝 **Paper Published in International Journal For Multidisciplinary Research (IJFMR)**  
> 🧠 **Technologies:** Python, OpenCV, YOLOv3, Google Colab, JavaScript

---

## 🔍 Features

- 🔎 YOLOv3-based real-time object detection
- 🎥 Web-based webcam capture via JavaScript in Google Colab
- 📦 Bounding boxes with confidence scores on detected tools/objects
- 🖼️ Easy to run — no local installations required
- 🧰 Designed for smart tool recognition use cases

---

## 🚀 Getting Started (Run in Google Colab)

> ✅ No installation required!  
> Just open the notebook and run each cell step by step.

### 🔧 Step-by-Step Execution

#### 📌 Step 1: Install Required Libraries
```python
!pip install -q opencv-python numpy

####📥 Step 2: Download YOLO Files
python
Copy code
!wget -q https://pjreddie.com/media/files/yolov3.weights
!wget -q https://raw.githubusercontent.com/pjreddie/darknet/master/cfg/yolov3.cfg
!wget -q https://raw.githubusercontent.com/pjreddie/darknet/master/data/coco.names
