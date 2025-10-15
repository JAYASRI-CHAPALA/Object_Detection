# 🛠 Object Detection Project

[![Python](https://img.shields.io/badge/python-3.11-blue.svg)](https://www.python.org/)
[![Streamlit](https://img.shields.io/badge/streamlit-v1.30.0-orange.svg)](https://streamlit.io/)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)

## 🔍 Overview

This project implements **real-time object detection** using **YOLO** and **MobileNet SSD** models. Detect multiple objects in **images** or **videos** with **bounding boxes**, **class labels**, and **confidence scores**.

## ✨ Features

* 🖼️ Detect objects in images or live webcam feed
* 🤖 Supports **YOLO** and **MobileNet SSD** models
* 🌐 Interactive **Streamlit web interface**
* ⚙️ Adjustable **confidence** and **IoU thresholds**

## 🚀 Installation

1. Clone the repository:

```bash
git clone https://github.com/JAYASRI-CHAPALA/Object-Detection.git
cd Object-Detection
```

2. Create & activate a virtual environment:

```bash
python -m venv streamlitenv
# Activate based on your OS
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

## 🎯 Usage

Run the Streamlit app:

```bash
streamlit run ob3/main_app.py
```

* Upload images or use webcam for detection
* Select **model** and adjust **parameters** interactively

## 📦 Dependencies

* Python 3.11
* OpenCV
* TensorFlow / PyTorch
* Streamlit
* Pillow

## 💡 How It Works

1. Load the selected model (YOLO or SSD).
2. Preprocess input image/video.
3. Perform object detection and compute bounding boxes.
4. Apply **Non-Maximum Suppression (NMS)** to remove overlapping boxes.
5. Display results on **Streamlit interface**.

## 📄 License

MIT License

## 🌟 Connect

* GitHub: [JAYASRI-CHAPALA](https://github.com/JAYASRI-CHAPALA)
* LinkedIn: [Your Profile](https://www.linkedin.com/)
