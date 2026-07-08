<div align="center">

# 🚀 Edge AI Model Optimization for Image Classification

### Deep Learning • TensorFlow • TensorFlow Lite • Model Compression • Edge Deployment

![Python](https://img.shields.io/badge/Python-3.12-blue?style=for-the-badge&logo=python)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.19-FF6F00?style=for-the-badge&logo=tensorflow)
![TensorFlow Lite](https://img.shields.io/badge/TensorFlow-Lite-orange?style=for-the-badge)
![Keras](https://img.shields.io/badge/Keras-Deep_Learning-D00000?style=for-the-badge&logo=keras)
![Edge AI](https://img.shields.io/badge/Edge-AI-success?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

*A comprehensive study of Edge AI optimization techniques using MobileNetV2 and VGG16 for efficient deployment on resource-constrained devices.*

</div>

---

# 📖 Overview

This project explores **Edge AI optimization techniques** for deep learning image classification using **TensorFlow**, **TensorFlow Lite**, and the **TensorFlow Model Optimization Toolkit**.

Two popular transfer learning architectures, **MobileNetV2** and **VGG16**, were trained on the **Rock-Paper-Scissors** dataset and optimized using multiple deployment-oriented techniques including TensorFlow Lite conversion, INT8 quantization, Float16 quantization, and weight clustering.

The optimized models were evaluated based on **classification accuracy**, **model size**, and **inference latency** to identify the most suitable architecture for deployment on edge devices such as Raspberry Pi, NVIDIA Jetson, and mobile platforms.

---

# ✨ Features

- Transfer Learning using ImageNet pretrained models
- MobileNetV2 and VGG16 implementation
- Data preprocessing and augmentation
- TensorFlow Lite model conversion
- Float16 quantization
- INT8 quantization
- Weight clustering
- Model compression
- Performance benchmarking
- Edge AI deployment analysis

---

# 📂 Dataset

**Dataset:** Rock-Paper-Scissors (TensorFlow Datasets)

| Property | Value |
|-----------|------:|
| Training Images | 2520 |
| Testing Images | 372 |
| Number of Classes | 3 |
| Input Image Size | 128 × 128 |

**Classes**

- ✊ Rock
- ✋ Paper
- ✌️ Scissors

---

# ⚙️ Workflow

```text
Dataset
   │
   ▼
Preprocessing
   │
   ▼
Data Augmentation
   │
   ▼
Transfer Learning
   │
   ▼
Model Training
   │
   ▼
Model Evaluation
   │
   ▼
TensorFlow Lite Conversion
   │
   ▼
Quantization
   │
   ▼
Weight Clustering
   │
   ▼
Performance Comparison
```

---

# 🧠 Models Used

## MobileNetV2

- Lightweight convolutional neural network
- ImageNet pretrained weights
- Fine-tuned using transfer learning
- Optimized for low-latency inference

### Advantages

- Small model size
- Fast inference
- Low computational cost
- Suitable for embedded devices

---

## VGG16

- Deep convolutional neural network
- ImageNet pretrained weights
- Fine-tuned for image classification
- High feature extraction capability

### Advantages

- High classification accuracy
- Robust feature learning
- Strong benchmark architecture

---

# ⚡ Edge AI Optimization Techniques

### TensorFlow Lite Conversion

Converts trained TensorFlow models into lightweight deployment-ready models suitable for embedded platforms.

### Float16 Quantization

- Reduced model size
- Faster inference
- Minimal accuracy degradation

### INT8 Quantization

- 4× model compression
- Reduced memory usage
- Faster CPU inference
- Optimized for edge deployment

### Weight Clustering

- Compresses model weights
- Reduces storage requirements
- Preserves model performance while improving compressibility

---

# 📊 Performance Comparison

| Model | Test Accuracy | Model Size | Inference Time |
|------------------------------|:-------------:|:----------:|:--------------:|
| MobileNetV2 (Float32) | **96.24%** | **8.97 MB** | **0.0043 s** |
| VGG16 (Float32) | **98.39%** | **57.72 MB** | **0.1309 s** |
| MobileNetV2 (INT8 TFLite) | **80.11%** | **2.58 MB** | **0.0043 s** |
| VGG16 (INT8 TFLite) | **98.39%** | **14.29 MB** | **0.1309 s** |
| MobileNetV2 (Weight Clustered) | **96.24%** | **Compressed Weights** | **Comparable to Float32** |

---

# 🏆 Key Findings

- **VGG16** achieved the highest classification accuracy (**98.39%**).
- **MobileNetV2** provided the fastest inference speed and the smallest model size.
- INT8 quantization reduced model size by approximately **3.5×–4×**.
- VGG16 retained its original accuracy after INT8 quantization.
- MobileNetV2 demonstrated superior suitability for real-time Edge AI applications due to its low latency.
- Weight clustering successfully compressed model weights while maintaining model performance.

---

# 💻 Installation

Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/edge-ai-model-optimization.git
```

Navigate to the project directory

```bash
cd edge-ai-model-optimization
```

Install the required packages

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

---

# 📦 Requirements

- Python 3.12
- TensorFlow
- TensorFlow Datasets
- TensorFlow Lite
- TensorFlow Model Optimization Toolkit
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

---

# 🎯 Skills Demonstrated

- Edge AI
- Deep Learning
- Computer Vision
- Transfer Learning
- TensorFlow
- TensorFlow Lite
- Model Optimization
- Model Compression
- Quantization
- Weight Clustering
- Performance Benchmarking

---

# 🚀 Future Work

- Quantization-Aware Training (QAT)
- Raspberry Pi Deployment
- NVIDIA Jetson Deployment
- TensorRT Optimization
- ONNX Conversion
- OpenVINO Optimization
- Edge TPU Deployment
- Real-Time Camera Inference

---

# 👨‍💻 Author

**Parthib Kumar Dey**

*M.Tech Smart Manufacturing*  
Department of Design and Manufacturing  
Indian Institute of Science (IISc), Bangalore

---

## 📜 License

This project is licensed under the **MIT License**.

---

<div align="center">

### ⭐ If you found this project useful, please consider giving it a star!

</div>
