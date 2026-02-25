# Detection-and-classification-of-abnormalities-in-lungs-
🫁 Detection and Classification of Abnormalities in Lungs

Welcome to the Lung Abnormality Detection System, a deep learning-based project that automatically detects and classifies lung diseases from chest X-ray images.

This system uses Convolutional Neural Networks (CNN) built with TensorFlow and Keras to provide accurate and fast predictions for medical image analysis.

📌 Project Overview

Early detection of lung diseases is important for effective treatment. Manual analysis of X-ray images can be time-consuming and may depend on the radiologist’s experience.

This project develops an AI-powered solution that analyzes chest X-ray images and classifies them into different categories such as:

✅ Normal

🦠 Pneumonia

🫁 Tuberculosis

🦠 COVID-19

The model is trained using deep learning techniques to improve accuracy and reliability.

🎯 Objectives

Automate the detection of lung diseases

Reduce diagnosis time

Improve classification accuracy using CNN

Support doctors with AI-based assistance

🧠 Model Architecture

The project uses a Convolutional Neural Network (CNN) consisting of:

Input Layer (Resized X-ray images)

Convolution Layers (Feature Extraction)

ReLU Activation Function

Max Pooling Layers

Fully Connected (Dense) Layers

Softmax Output Layer for multi-class classification

TensorFlow is used as the backend framework, and Keras is used for building and training the model.

🔄 Data Preprocessing

Before training, the dataset undergoes the following preprocessing steps:

Image Resizing

Normalization (Scaling pixel values from 0–255 to 0–1)

Data Augmentation (Flipping and Rotation)

Train-Test Split (80% Training, 20% Testing)

These steps improve model performance and reduce overfitting.

📊 Results

Achieves high accuracy in classifying lung diseases

Provides fast predictions

Efficient multi-class classification system

🛠️ Technologies Used

Python

TensorFlow

Keras

NumPy

Matplotlib

OpenCV

Google Colab / Jupyter Notebook
📂 Project Structure
Detection-and-classification-of-abnormalities-in-lungs/
│
├── dataset/
├── model/
├── training_script.py
├── prediction_script.py
├── requirements.txt
└── README.md
🖥️ How to Run the Project

Clone the repository

Install required libraries using:

pip install -r requirements.txt

Run the training script

Upload a chest X-ray image to get prediction

🚀 Future Enhancements

Deploy as a web application

Use Transfer Learning models like ResNet or MobileNet

Increase dataset size for better accuracy

Integrate real-time hospital usage
