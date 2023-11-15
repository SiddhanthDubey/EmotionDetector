# EmotionDetector
# Real-Time Emotion Detector Project

This Git repository contains code and resources for a real-time emotion detector project. The project utilizes a Convolutional Neural Network (CNN) trained on the Face Expression Recognition Dataset available on Kaggle. 

Dataset Link - https://www.kaggle.com/datasets/jonathanoheix/face-expression-recognition-dataset


The primary components of this project include:

    Requirements.txt: This file lists all the dependencies and versions required to run the code successfully. To install the dependencies, use the following command:

    bash

    pip install -r requirements.txt

    Notebook File (train_model.ipynb): The Jupyter Notebook file contains the code used to train the emotion detection model. It leverages a Convolutional Neural Network architecture and is designed to work with the specified dataset.

    Python File (emotion_detector.py): This Python script allows real-time emotion detection using the trained model. It utilizes OpenCV to capture video frames, detect faces, and predict emotions on each frame.

Getting Started

Follow these steps to get started with the real-time emotion detector project:

    Clone the repository:

    bash git clone https://github.com/your-username/emotion-detector.git
    
    cd emotion-detector

Install the dependencies:

    pip install -r requirements.txt

Download the dataset:

Visit Face Expression Recognition Dataset on Kaggle and download the dataset. Extract the contents and place them in a folder named images in the project directory.

Train the model:

Open and run the train_model.ipynb notebook to train the emotion detection model. This will generate a trained model file.

Run the real-time emotion detector:

Execute the following command to run the real-time emotion detection script:

    python realtimedetection.py

    This will activate your webcam and display real-time emotion predictions.

Note

Ensure that your environment has a compatible GPU if you intend to train the model. Additionally, make sure to have OpenCV installed for the real-time emotion detection script to work correctly.

Feel free to explore and modify the code to suit your needs. If you encounter any issues or have suggestions for improvement, please open an issue on the GitHub repository.
