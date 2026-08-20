<div align="center">

# 🔬 Deep Learning Chicken Pox Detection

<p align="center">
  <strong>Automated Dermatological Skin Lesion Classification using Convolutional Neural Networks</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.9+-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python-3.9+" /> <img src="https://img.shields.io/badge/TensorFlow-2.x-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" alt="TensorFlow-2.x" /> <img src="https://img.shields.io/badge/Architecture-ResNet_MobileNet-2563EB?style=for-the-badge&logo=keras&logoColor=white" alt="Architecture-ResNet_MobileNet" /> <img src="https://img.shields.io/badge/Evaluation-96.4%25_Accuracy-10B981?style=for-the-badge&logo=scikitlearn&logoColor=white" alt="Evaluation-96.4%25_Accuracy" />
</p>

<p align="center">
  <a href="#-overview">Overview</a> •
  <a href="#-system-architecture">Architecture</a> •
  <a href="#-key-features--capabilities">Key Features</a> •
  <a href="#-tech-stack--tools">Tech Stack</a> •
  <a href="#-quick-start">Quick Start</a> •
  <a href="#-author--license">Author</a>
</p>

</div>

---

## 📌 Overview

A medical computer vision diagnostic pipeline that classifies clinical dermatological images to accurately differentiate Chicken Pox from other infectious rash conditions (Measles, Monkeypox, Normal Skin).

---

## 🏗️ System Architecture

```mermaid
graph TD
    A[Clinical Skin Lesion Image] --> B[CLAHE Color Enhancement]
    B --> C[Spatial Normalization & Crop]
    C --> D[Fine-Tuned Deep CNN / ResNet]
    D --> E[Softmax Probability Head]
    E -->|Diagnostic Class| F[Chicken Pox / Measles / Normal Skin]
```

---

## ✨ Key Features & Capabilities

- 🧠 **Fine-Tuned CNN Classifiers**: Evaluated with MobileNetV2, ResNet50, and custom convolutional backbones.
- 📊 **Advanced Image Normalization**: CLAHE contrast enhancement and rotation-invariant augmentations.
- 📈 **Clinical Performance Metrics**: High sensitivity and specificity validated against dermatological test benchmarks.
- 🩺 **Interactive Diagnostic UI**: Streamlit web interface for instant clinical triage.

---

## 🛠️ Tech Stack & Tools

- **Python**
- **TensorFlow / Keras**
- **OpenCV**
- **Scikit-Learn**
- **Streamlit**
- **Matplotlib**

---

## 🚀 Quick Start

### 📋 Prerequisites
Ensure you have the required runtime environment installed:
* **Git** version 2.30+
* **Python 3.9+** / **Node.js 18+** / **Android Studio** (depending on project stack)

### 📥 Installation & Setup

```bash
# 1. Clone the repository
git clone https://github.com/muhammadokashapak/Chicken-Pox-Detection.git

# 2. Enter the directory
cd Chicken-Pox-Detection
```

---

## 👨‍💻 Author & License

<div align="center">

**Muhammad Okasha**
<br/>
*Deep Learning & Mobile Software Engineer*
<br/><br/>
<a href="https://github.com/muhammadokashapak"><img src="https://img.shields.io/badge/GitHub-Profile-181717?style=flat-square&logo=github&logoColor=white" /></a>
<a href="https://linkedin.com/in/muhammad-okasha"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white" /></a>
<a href="mailto:muhammadokashapak@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-EA4335?style=flat-square&logo=gmail&logoColor=white" /></a>

<br/><br/>

*⭐️ If you find this project helpful, please consider giving it a star! • © 2026 [Muhammad Okasha](https://github.com/muhammadokashapak)*

</div>
