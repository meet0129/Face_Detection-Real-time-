# 🎯 Real-Time Face Detection using Deep Learning (VGG16 + OpenCV)

A powerful real-time face detection system built with **TensorFlow**, **OpenCV**, and a custom-trained **VGG16** model. It leverages deep learning for accurate face detection from live webcam streams, with support for **data augmentation** using Albumentations and visual insights via Matplotlib. This project is optimized for GPU processing (tested on Nvidia 1650 Ti).

## 🚀 Technologies Used

- **Python 3.x** – Programming language
- **OpenCV** – Image processing & webcam handling
- **UUID** – Unique labeling for dataset generation
- **TensorFlow** – Deep learning framework
- **VGG16** – Pretrained CNN model for face detection
- **Matplotlib** – Visualization of data and training results
- **Albumentations** – Fast and flexible data augmentation
- **Nvidia 1650 Ti** – GPU acceleration for faster training and inference

## 📸 Project Highlights

- Detects faces in real-time from webcam feed
- Custom-trained VGG16 model for robust feature extraction
- Data labeling using `uuid` for unique image IDs
- Real-time detection using `cv2.VideoCapture()`
- Augmentation pipeline with Albumentations for improved model generalization
- Visual monitoring with Matplotlib during training
- Clean, modular code structure
