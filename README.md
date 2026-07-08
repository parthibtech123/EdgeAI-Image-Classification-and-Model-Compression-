<div align="center">

# 🚀 Edge AI Model Optimization for Image Classification

### Deep Learning • TensorFlow • TensorFlow Lite • Model Compression • Edge Deployment

<p align="center">

![Python](https://img.shields.io/badge/Python-3.12-blue?style=for-the-badge&logo=python)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.19-FF6F00?style=for-the-badge&logo=tensorflow)
![TensorFlow Lite](https://img.shields.io/badge/TensorFlow-Lite-orange?style=for-the-badge)
![Keras](https://img.shields.io/badge/Keras-Deep_Learning-D00000?style=for-the-badge&logo=keras)
![Edge AI](https://img.shields.io/badge/Edge-AI-success?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

</p>

*A comprehensive study of Edge AI optimization techniques using MobileNetV2 and VGG16 for efficient deployment on resource-constrained devices.*

</div>

---

# 📖 Overview

Edge AI enables machine learning models to execute directly on embedded and edge devices with limited computational resources. This project investigates the impact of several optimization techniques on deep learning image classification models while maintaining competitive accuracy.

Using the **Rock–Paper–Scissors** dataset, two transfer learning architectures—**MobileNetV2** and **VGG16**—were trained and optimized using **TensorFlow Lite** and **TensorFlow Model Optimization Toolkit**. The optimized models were benchmarked based on classification accuracy, model size, and inference latency to evaluate their suitability for deployment on edge platforms.

---

# ✨ Key Features

- ✅ TensorFlow Dataset API
- ✅ Transfer Learning with ImageNet Weights
- ✅ MobileNetV2
- ✅ VGG16
- ✅ Data Augmentation
- ✅ TensorFlow Lite Conversion
- ✅ Float16 Quantization
- ✅ INT8 Quantization
- ✅ Weight Clustering
- ✅ Model Compression
- ✅ Performance Benchmarking
- ✅ Edge AI Deployment Analysis

---

# 🖼 Dataset

## Rock–Paper–Scissors Dataset (TensorFlow Datasets)

| Property | Value |
|-----------|------:|
| Training Images | 2520 |
| Testing Images | 372 |
| Classes | 3 |
| Input Resolution | 128 × 128 |

### Classes

- ✊ Rock
- ✋ Paper
- ✌️ Scissors

---

# 🔄 Project Workflow

```text
Dataset
   │
   ▼
Data Exploration
   │
   ▼
Preprocessing & Augmentation
   │
   ▼
Transfer Learning
   │
   ▼
Model Training
   │
   ▼
Performance Evaluation
   │
   ▼
TensorFlow Lite Conversion
   │
   ▼
Model Quantization
   │
   ▼
Weight Clustering
   │
   ▼
Performance Benchmarking
```

---

# 🧠 Deep Learning Models

## MobileNetV2

- Lightweight CNN
- Transfer Learning
- ImageNet Pretrained
- Fine-tuning
- Global Average Pooling
- Softmax Classification Layer

### Advantages

- Low computational complexity
- Small memory footprint
- Fast inference
- Ideal for embedded devices

---

## VGG16

- Deep CNN Architecture
- Transfer Learning
- ImageNet Pretrained
- Fine-tuning
- Dense Classification Head

### Advantages

- Excellent feature extraction
- High classification accuracy
- Strong benchmark architecture

---

# ⚙️ Edge AI Optimization Techniques

### TensorFlow Lite Conversion

Converts trained TensorFlow models into lightweight deployment-ready models for mobile and embedded platforms.

---

### Float16 Quantization

- Reduced model size
- Faster inference
- Minimal accuracy degradation

---

### INT8 Quantization

- 4× compression
- Lower memory usage
- Optimized CPU inference
- Edge deployment ready

---

### Weight Clustering

- Compresses neural network weights
- Reduces storage requirements
- Preserves model performance while increasing compressibility

---

# 📊 Performance Comparison

| Model | Accuracy | Model Size | Inference Time |
|----------------------|:--------:|:-----------:|:--------------:|
| MobileNetV2 (Float32) | **96.24%** | **8.97 MB** | **0.0043 s** |
| VGG16 (Float32) | **98.39%** | **57.72 MB** | **0.1309 s** |
| MobileNetV2 (INT8) | **80.11%** | **2.58 MB** | **0.0043 s** |
| VGG16 (INT8) | **98.39%** | **14.29 MB** | **0.1309 s** |
| MobileNetV2 (Clustered Dense Layer) | **96.24%** | **Compressed Weights** | **Comparable to Float32** |

---

# 📈 Key Findings

| Observation | Result |
|-------------|--------|
| Highest Accuracy | VGG16 (98.39%) |
| Fastest Inference | MobileNetV2 |
| Smallest Model | MobileNetV2 INT8 |
| Best Compression Ratio | VGG16 INT8 (4×) |
| Best Edge Deployment Choice | MobileNetV2 |
| Best Overall Accuracy | VGG16 |

---

# 📂 Repository Structure

```text
edge-ai-model-optimization/

├── README.md
├── LICENSE
├── requirements.txt
├── .gitignore
│
├── notebooks/
│   └── EdgeAI_Model_Optimization.ipynb
│
├── models/
│   ├── MobileNetV2/
│   └── VGG16/
│
├── figures/
│   ├── dataset_samples.png
│   ├── training_accuracy.png
│   ├── training_loss.png
│   ├── confusion_matrix.png
│   ├── model_size_comparison.png
│   ├── inference_time.png
│   └── quantization_results.png
│
└── results/
    ├── benchmark.csv
    └── performance_summary.csv
```

---

# 📷 Results

## Dataset Samples

<p align="center">
<img src="figures/dataset_samples.png" width="700">
</p>

---

## Training Accuracy

<p align="center">
<img src="figures/training_accuracy.png" width="700">
</p>

---

## Training Loss

<p align="center">
<img src="figures/training_loss.png" width="700">
</p>

---

## Model Size Comparison

<p align="center">
<img src="figures/model_size_comparison.png" width="700">
</p>

---

## Inference Time Comparison

<p align="center">
<img src="figures/inference_time.png" width="700">
</p>

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

Install dependencies

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
- Matplotlib
- Scikit-learn
- Pandas

---

# 🚀 Future Work

- Deploy on Raspberry Pi
- Deploy on NVIDIA Jetson Nano
- TensorRT Optimization
- ONNX Conversion
- OpenVINO Optimization
- Real-Time Camera Inference
- Edge TPU Deployment
- Quantization-Aware Training (QAT)

---

# 🎯 Skills Demonstrated

- Edge AI
- Computer Vision
- Deep Learning
- Transfer Learning
- TensorFlow
- TensorFlow Lite
- Model Compression
- Quantization
- Weight Clustering
- Performance Benchmarking
- Embedded AI

---

# 📚 References

1. TensorFlow Documentation
2. TensorFlow Lite Documentation
3. TensorFlow Model Optimization Toolkit
4. MobileNetV2: Inverted Residuals and Linear Bottlenecks
5. Very Deep Convolutional Networks for Large-Scale Image Recognition (VGG16)

---

# 👨‍💻 Author

**Parthib Kumar Dey**

*M.Tech Smart Manufacturing*  
Department of Design and Manufacturing  
Indian Institute of Science (IISc), Bangalore

---

<div align="center">

⭐ **If you found this project useful, please consider giving it a star!** ⭐

</div>
