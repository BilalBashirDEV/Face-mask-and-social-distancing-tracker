# 🧠 Social Distancing and Face Mask Detection using AI

This project monitors **social distancing violations** and **face mask compliance** in live or recorded video feeds. It combines **YOLOv3** for person detection, **DBSCAN clustering** for distance violation detection, and a **ResNet50-based Face Mask Classifier** to identify individuals not wearing masks properly. Synthetic data augmentation using facial landmarks and blur effects enhances model robustness under real-world camera conditions.

---

## 🚀 Features

- 👁️ **Person Detection** using YOLOv3 (COCO pretrained)
- 😷 **Face Detection** using DSFD (Dual Shot Face Detector)
- 🧠 **Face Mask Classification** using ResNet50 (Masked/Unmasked/Improper)
- 📏 **Social Distance Violation Detection** via DBSCAN clustering
- 🧩 **Augmentation** using facial landmarks and motion blur for realism
- 💻 **Real-time Processing** via OpenCV and Keras

---

## 🛠️ Tech Stack

- **Languages:** Python (3.7+)
- **Libraries:** NumPy, Matplotlib, Scikit-learn, OpenCV, PIL, Keras, face-detection, face-recognition, tqdm
- **Environment:** Jupyter Notebook / Google Colab (GPU/TPU)
- **Models:** YOLOv3, ResNet50

---

## 📦 Installation

Install dependencies:
```bash
pip install numpy matplotlib sklearn Pillow opencv-python Keras face-detection face-recognition tqdm
