This repository contains my personal study notes about **Inception V1** and **Inception V3** architectures in Deep Learning.

I created this notebook to understand:
- Why older CNN models had problems
- How Inception architecture solved those problems
- Why 1x1 convolution is important
- How Inception V3 became more efficient

The notebook is written in a very simple way with explanations, comparisons, and architecture images.

---

# Topics Covered Step by Step

## 1. Problems in Older CNN Models
- VGG16 parameter problem
- Large convolution filters
- High computation cost
- Channel explosion problem

---

## 2. Understanding Channels
- What RGB channels are
- What feature maps are
- How convolution creates new channels

---

## 3. VGG16 Approach
- Why VGG16 used 3x3 filters
- Advantages of smaller filters
- Limitations of large channel sizes

---

## 4. ResNet50 Approach
- Residual block idea
- Bottleneck concept
- How 1x1 convolution helps reduce channels

---

## 5. 1x1 Convolution
- Dimensionality reduction
- Reducing computation cost
- Mixing channel information efficiently

---

## 6. Inception V1 Architecture
- Multiple filters in parallel
- 1x1, 3x3, 5x5 convolutions together
- Capturing both small and large features
- Inception block concept

---

## 7. Inception V3 Improvements
This notebook also explains how Inception V3 improved Inception V1 using:

### Technique 1
Factorization into smaller convolutions

### Technique 2
Asymmetric convolutions (1x3 and 3x1)

### Technique 3
Auxiliary classifiers for vanishing gradient problem

---

## 8. Inception V3 Architecture
- Input size explanation
- Inception Blocks
- Reduction Blocks
- Global Average Pooling
- Softmax layer

---

## 9. Reduction Blocks
- Spatial dimension reduction
- Efficient computation
- Better feature extraction

---

# Notebook Features

- Simple explanations
- Personalized learning notes
- Architecture understanding
- Image-based visualization
- Easy English and Bengali mixed explanations

---

# Technologies Used

- Python
- Google Colab / Jupyter Notebook
- Matplotlib
- PIL (Python Imaging Library)

---

This notebook is mainly created to:
- Learn Deep Learning architectures
- Understand CNN optimization ideas
- Study Inception models step by step
- Build strong conceptual knowledge

---

