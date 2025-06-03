# 🖼️ Image Classification with CNN (Keras & TensorFlow)

This repository contains an image classification project using a **Convolutional Neural Network (CNN)** built with Keras and TensorFlow. The model classifies images based on visual features, employing common deep learning techniques and image preprocessing strategies.

---

## 📁 Project Structure

```
📦 Image-Classification-CNN/
├── explore (2).ipynb         # Jupyter notebook with model training and evaluation
├── README.md                 # Project overview and usage instructions
├── data/                     # Folder to store training and test image data
```

---

## 🖼️ Image Preprocessing

- Image shape: 128x128 RGB
- Augmented via `ImageDataGenerator`
- Split using `train_test_split`

---

## 🧠 Model Architecture

Built with Keras `Sequential` API:
- 👁️ 2D Convolution + MaxPooling layers
- 🚿 Dropout for regularization
- 🔁 BatchNormalization
- 🧠 Dense layers with activation functions
- 🛑 EarlyStopping & ReduceLROnPlateau for training optimization

---

## 🧪 How to Run

### Prerequisites

```bash
pip install tensorflow keras matplotlib numpy pandas scikit-learn
```

### Launch the notebook

```bash
jupyter notebook "explore.ipynb"
```

Ensure the `data/` folder contains properly structured subdirectories for each class of images.

---

## 📚 Libraries Used

- `tensorflow`, `keras`
- `numpy`, `pandas`
- `matplotlib`
- `sklearn`

---

## 🚀 Project Goals

- Classify images using deep learning techniques
- Demonstrate CNN architecture construction and training
- Show visualization of training progress and prediction results

---

## 📬 Contact

Developed as part of a computer vision exploration project. Contributions and forks are welcome!
