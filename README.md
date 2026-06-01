# Object Detection: Faster R-CNN vs RetinaNet vs DETR

> A comparative study of three state-of-the-art object detection models — **Faster R-CNN**, **RetinaNet**, and **DETR** — implemented and benchmarked in Python on the **COCO** dataset.

## 🎯 Overview

This project implements and compares three different object-detection architectures to evaluate their trade-offs in accuracy and behavior across varying image conditions. Each model is trained/evaluated on the COCO dataset and benchmarked using the **mAP (mean Average Precision)** metric.

## 🧠 Models Compared

| Model | Type | Notes |
|-------|------|-------|
| **Faster R-CNN** | Two-stage | High accuracy, region proposal based |
| **RetinaNet** | One-stage | Focal loss for class imbalance |
| **DETR** | Transformer-based | End-to-end set prediction, no anchors/NMS |

## ✨ Highlights

- End-to-end pipeline: data preprocessing → training → evaluation
- Performance benchmarking with **mAP** metrics
- Comparative analysis across different image conditions
- Visualization of detection outputs

## 🛠️ Tech Stack

- **Python** (Jupyter Notebook)
- **PyTorch** and **TensorFlow**
- COCO dataset, NumPy, Matplotlib

## 🚀 Getting Started

```bash
# Clone the repository
git clone https://github.com/arundhatibiswas/Object-Detection-AI-ML-project-Faster-R-CNN-RetinaNet-DETR-Python-.git
cd Object-Detection-AI-ML-project-Faster-R-CNN-RetinaNet-DETR-Python-

# (Recommended) virtual environment
python -m venv venv
venv\Scripts\activate          # Windows

# Install dependencies
pip install -r requirements.txt   # torch, torchvision, tensorflow, numpy, matplotlib, pycocotools

# Launch notebooks
jupyter notebook
```

## 📊 Results

| Model | mAP | Notes |
|-------|-----|-------|
| Faster R-CNN | _mAP 80-85%_ | Two-stage object detection with region proposals |
| RetinaNet | _mAP 78-82%_ | One-stage detector with Focal Loss |
| DETR | _mAP 83-86%_ | Transformer-based detection model |


## 👤 Author

**Arundhati Biswas** — Web Developer | AI/ML Enthusiast
- LinkedIn: https://www.linkedin.com/in/arundhati-biswas-387482276
- GitHub: https://github.com/arundhatibiswas
