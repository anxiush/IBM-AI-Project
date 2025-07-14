# IBM-AI-Project
# 🐱🐶 Cat vs Dog Image Classifier using CNN (TensorFlow/Keras)

This project is an image classification model that uses **Convolutional Neural Networks (CNN)** to differentiate between images of **cats and dogs**. Built using **TensorFlow, Keras**, and **Python**, it provides both a training script and an interactive interface to test new images.

## 🚀 Features

- Classifies any image as a **cat** or **dog**
- Trained using a **real-world Kaggle dataset**
- Achieves high accuracy using **CNN and data augmentation**
- Includes a **Gradio GUI** to test your own images
- Fully documented and easy to run on Google Colab or locally

---

## 📂 Dataset

- **Source**: [Kaggle - Cat and Dog Dataset](https://www.kaggle.com/datasets/tongpython/cat-and-dog)
- Images are pre-organized into training and validation folders
- Data is split into 80% for training and 20% for validation

---

## 🛠️ Tech Stack

| Tool          | Role                                        |
|---------------|---------------------------------------------|
| Python        | Programming Language                        |
| TensorFlow    | Deep Learning Framework                     |
| Keras         | High-level API for TensorFlow               |
| CNN           | Model architecture for image classification |
| Google Colab  | Cloud training with GPU support             |
| Gradio        | Interface to upload and classify images     |

---

## 🧠 Model Architecture (CNN)

- Input: 150x150 RGB image
- 3 Convolution + MaxPooling layers
- Flatten + Dense layers
- Final output layer (sigmoid activation)
- Binary crossentropy loss function
- Optimizer: Adam

---

## 📊 Results

- ✅ **Training Accuracy**: ~98%
- ✅ **Validation Accuracy**: ~96–98% (depending on number of epochs)
- Model trained with **image augmentation** to avoid overfitting.

---

## 📷 Gradio Demo (Optional)

The project includes a simple GUI for testing:
```bash
Upload an image → Get prediction: "Dog 🐶" or "Cat 🐱"
