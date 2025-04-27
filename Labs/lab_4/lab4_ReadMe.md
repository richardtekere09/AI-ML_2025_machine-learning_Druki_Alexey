# 📚 Laboratory Work №4: Image Recognition Using ResNet (CIFAR-10 Dataset)

## Introduction
This laboratory work is devoted to gaining practical skills in image recognition using convolutional neural networks (CNNs), with a particular focus on the ResNet (Residual Network) architecture implemented in the Keras library.

The work involves using the CIFAR-10 dataset, which contains 60,000 color images of 10 different classes (airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck).

---

## Objective
- To learn how to build and train convolutional neural networks using the Keras API.
- To understand and apply the ResNet architecture for image classification tasks.
- To evaluate the performance of the neural network model on a real-world dataset.
- To switch running environment for CPU to GPU 

---

## Tasks
1. Import and prepare the CIFAR-10 dataset.
2. Normalize the image data.
3. Build a ResNet-based CNN model.
4. Train the neural network model.
5. Evaluate the model on the test data.
6. Analyze classification performance using metrics and visualization.
7. Draw conclusions based on the obtained results.

---

## Tools and Libraries
- Python 3.x
- TensorFlow 2.x (Keras API)
- Matplotlib
- NumPy

---

## Structure of the Work
- **Data Preprocessing:** Downloading, normalizing the images.
- **Model Architecture:** Building a neural network based on ResNet principles.
- **Training Process:** Monitoring training and validation accuracy and loss.
- **Evaluation:** Using confusion matrices, classification reports, and visual examples of predictions.
- **Conclusion:** Analysis of model performance and further improvements.

---

## Dataset Details
- **Training Set:** 50,000 images (32×32 pixels, 3 channels)
- **Test Set:** 10,000 images (32×32 pixels, 3 channels)
- **Classes:** 10 object categories.

---

## How to Run
1. Install all dependencies:
   ```bash
   pip install tensorflow matplotlib numpy
