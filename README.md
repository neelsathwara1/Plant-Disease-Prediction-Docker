# Plant-Disease-Prediction-Docker
This project leverages Machine Learning (ML), Deep Learning (DL), Streamlit, and Docker to create a user-friendly web application that predicts plant diseases from images of plant leaves. The model helps farmers and agricultural experts detect diseases at an early stage, improving crop management and yield.

## Features
- Machine Learning & Deep Learning Models: Utilizes CNN (Convolutional Neural Networks) and other ML algorithms to classify plant diseases from images.
- User Interface with Streamlit: A web application where users can upload plant leaf images and get real-time predictions about the disease.
- Docker for Containerization: The project is Dockerized to ensure ease of deployment and scalability across different environments.
- Pre-trained Model Integration: The app uses pre-trained models for accurate and fast predictions, reducing the need for high computational power.

## Technologies Used
Machine Learning: Used for preprocessing and feature extraction.
Deep Learning: Built CNN models using frameworks like TensorFlow/Keras for image classification.
Streamlit: Provides a simple UI to upload images and display predictions.
Docker: Containerized the app for easy deployment and environment consistency.
Python: The core language for development, utilizing libraries like TensorFlow, OpenCV, Pandas, and NumPy.

## Prerequisites
Docker should be installed on your system.
Python 3.x with the required dependencies (if running locally without Docker).

## Usage
Upload an image of a plant leaf using the provided file uploader.
The model will process the image and display the predicted disease and confidence score.
For each prediction, the app will also provide basic information about the disease.
