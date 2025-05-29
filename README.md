# 🧠 MNIST Handwritten Digit Classification

This project demonstrates the classification of handwritten digits from the MNIST dataset using a Convolutional Neural Network (CNN). The model takes grayscale images of handwritten digits (0–9) and predicts the corresponding numeric value with high accuracy.

---

## 📊 Dataset

- **MNIST Dataset**: 70,000 images of handwritten digits
  - 60,000 training images
  - 10,000 test images
- Each image is a 28x28 pixel grayscale image.

---

## 🚀 Key Features

- ✅ Built using a powerful CNN architecture
- 📈 Achieves over 99% accuracy on test data
- 🔍 Includes visualization of predictions
- 📚 Clean, readable, and well-structured code
- 🧪 Simple and effective implementation using Keras and TensorFlow

---

## 🛠️ Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Jupyter Notebook

---

## 🧪 Model Architecture

The CNN model consists of the following layers:

1. Convolutional Layer (32 filters, 3x3 kernel)
2. ReLU Activation
3. MaxPooling Layer (2x2)
4. Convolutional Layer (64 filters, 3x3 kernel)
5. ReLU Activation
6. MaxPooling Layer (2x2)
7. Flatten Layer
8. Dense Layer (64 units)
9. Dropout Layer (0.5)
10. Output Layer (10 units with Softmax)

---

## 📈 Results

- Achieved over **99% test accuracy**
- Low validation loss and high generalization capability
- Demonstrated the effectiveness of CNNs for image classification tasks
