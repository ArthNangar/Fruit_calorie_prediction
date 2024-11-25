# Fruit Calorie Prediction Using Deep Learning

This repository contains the code and resources for a deep learning project designed to estimate the calorie content of fruits using images. By leveraging Convolutional Neural Networks (CNNs), the system provides fast and accurate calorie predictions for 100-gram portions of various fruits.

---

## **Introduction**

Manually estimating food calories can be tedious and prone to errors. This project automates calorie estimation using images of fruits. The model is trained on a labeled dataset where calorie values are standardized for 100-gram portions of fruits. With this system, users can easily predict the calorie content of fruits through image input, making it particularly useful for health and diet management.

---

## **Features**
- Predicts the calorie content of fruits from images.
- Standardized calorie predictions for 100 grams of fruit.
- Easy-to-use interface for input and results.
- Supports real-time prediction with high accuracy.
- Built using deep learning techniques for effective feature extraction.

---

## **Dataset Structure**

The dataset includes images of various fruits categorized into folders labeled by calorie values. Below is the dataset structure:

dataset/
  ├── train/
      ├── 59/
      │   ├── image1.jpg
      │   ├── image2.jpg
      │   └── ...
      ├── 80/
      │   ├── image1.jpg
      │   ├── image2.jpg
      │   └── ...
      └── ...
  ├── test/
  ├── validation/

Each folder under train represents a specific calorie value per 100 grams of the corresponding fruit.

---

## **Technologies Used**
- Python: Programming language for implementation.
- TensorFlow & Keras: Deep learning frameworks used for building and training the CNN model.
-Google Colab: Platform with T4 GPU for faster model training.
- Gradio UI: Framework for creating a user-friendly web interface.

---

## **Future Scope**
- Expand the dataset to include more fruit types.
- Integrate real-time image capture functionality for predictions.
- Develop a mobile application for on-the-go calorie estimation.
- Incorporate additional features like fruit weight detection for dynamic calorie calculations.

---
