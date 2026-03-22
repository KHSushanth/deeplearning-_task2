# deeplearning-_task2

# Deep Learning Models Project (CNN + RNN + GAN)

## Overview
This project focuses on implementing and evaluating multiple deep learning models across different domains such as image classification, sentiment analysis, and generative modeling. The models are developed using PyTorch and tested on real-world datasets.

---

## Objectives
- Implement CNN for image classification (CIFAR-10)
- Apply transfer learning using ResNet18
- Build RNN, LSTM, and GRU for sentiment analysis (IMDB)
- Implement GAN for image generation (Fashion-MNIST)
- Compare performance of different models


## Datasets Used

### CIFAR-10
- 60,000 images (10 classes)
- Used for CNN and ResNet18

### IMDB Dataset
- 50,000 movie reviews
- Binary sentiment classification

### Fashion-MNIST
- 70,000 grayscale images
- Used for GAN

---

## Models Implemented

### 1. CNN (Image Classification)
- Convolution + ReLU + BatchNorm + MaxPooling
- Fully Connected Layers
- Dropout for regularization

### 2. Transfer Learning (ResNet18)
- Pretrained model
- Modified final layer

### 3. RNN, LSTM, GRU
- Embedding layer
- Recurrent layers
- Fully connected output

### 4. GAN
- Generator (noise → image)
- Discriminator (real vs fake)

---

## Technologies Used
- Python
- PyTorch
- Torchvision
- NumPy
- Matplotlib & Seaborn

---

## How to Run

1. Clone the repository
2.  Install dependencies

pip install torch torchvision matplotlib numpy seaborn


3. Run notebook

   
---

## 📈 Results

| Model | Performance |
|------|-----------|
| CNN | ~75–81% accuracy |
| ResNet18 | ~81% accuracy |
| RNN | ~74% accuracy |
| LSTM | ~86% accuracy |
| GRU | ~87% accuracy |
| GAN | Generated realistic images |

---

## Visualizations
- Loss curves
- Accuracy comparison
- Confusion matrix
- Generated images (GAN)

---

## Key Learnings
- CNN is effective for image tasks
- Transfer learning improves accuracy
- LSTM/GRU outperform RNN
- GAN training is unstable but powerful

---

## References
- https://pytorch.org
- https://www.geeksforgeeks.org/deep-learning/
- https://www.tensorflow.org/datasets/catalog/imdb_reviews

---

## Author
 Name :K H Sushanth  
 USN  :NNM23IS083
 College:NMAMIT
