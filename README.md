# Computer Vision & Deep Learning Workshop – Pixels Student Activity (Helwan Engineering)

This repository contains the materials and notebook used in a **Computer Vision Workshop** organized by **Pixels Student Activity – Helwan University, Faculty of Engineering**.  
The session introduces both **classical computer vision (OpenCV)** and **deep learning-based methods**, with hands-on experiments in Google Colab.

---

# Overview

The workshop is designed to give students a practical introduction to how computers "see" and process images, starting from basic image operations to advanced object detection using pretrained deep learning models.

---

# Topics Covered

# **1. DL vs OpenCV**
- Understanding the difference between traditional computer vision (OpenCV) and deep learning.
- When to use classic algorithms vs neural networks.
- Real-world examples comparing both approaches.

# **2. Introduction to OpenCV**
- What is OpenCV and its importance in computer vision.
- Installing and setting up OpenCV in Google Colab.
- Reading, displaying, and saving images.

# **3. Basic Operations**
- Image resizing, cropping, flipping, and rotation.
- Accessing and modifying pixel values.
- Drawing shapes and text on images.

# **4. Color Spaces**
- RGB, BGR, Grayscale, and HSV color models.
- Converting between color spaces.
- Practical use cases of HSV for color detection.

# **5. Filters & Edge Detection**
- Applying smoothing filters (average, Gaussian, median, bilateral).
- Sharpening and detecting edges (Sobel, Laplacian, Canny).
- Visualizing differences between filter effects.

# **6. Face Detection**
- Using Haar Cascade Classifier for detecting faces in images and live video.
- Understanding how Haar features work.
- Real-time face detection demo using webcam.

# **7. Object Tracking & Masking**
- Color-based object detection using HSV masking.
- Tracking moving objects frame by frame.
- Practical example with color-based segmentation.

# **8. Drawing in Live Video**
- Capturing video from webcam using OpenCV.
- Drawing shapes and trails on live frames.
- Building interactive video-based applications.

# **9. LAB: Color Object Tracker**
- Hands-on mini-project where students implement a **color tracker**.
- The object is detected and followed in real-time using color segmentation.

# **10. Pretrained Models & DNN Module**
- Introduction to **Deep Neural Network (DNN)** module in OpenCV.
- Using **MobileNet-SSD** pretrained model for real-time object detection.
- Running inference on images and webcam feeds.

## Presentation Materials

The following resources were used during the workshop:

| Type | File | Description |
|------|------|-------------|
| 📑 PDF Slides | [Computer_Vision_Pixels_Slides.pdf](Presentation/Computer_Vision_Pixels_Slides.pdf) | The slides used during the workshop session. |
| 🎞️ PowerPoint | [Computer_Vision_Pixels_Slides.pptx](Presentation/Computer_Vision_Pixels_Slides.pptx) | Editable PowerPoint version of the presentation. |

---

# Requirements

To run the notebook locally, install the following libraries:
```bash
pip install opencv-python numpy matplotlib
```bash
pip install opencv-python numpy matplotlib
