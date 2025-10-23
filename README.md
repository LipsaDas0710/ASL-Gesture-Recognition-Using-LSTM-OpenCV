## 🤟 Real-Time ASL Gesture Recognition (LSTM & OpenCV)

An AI/ML-based system for recognizing American Sign Language (ASL) gestures from a live webcam feed.

This project uses computer vision (OpenCV) to extract facial and hand landmarks, feeding these sequences into a deep learning model (LSTM) for real-time translation of non-verbal signs into text. It provides an initial, intuitive bridge for communication.

## ✨ Features

Real-time Recognition: Detects and translates common ASL signs: "Hello", "Thanks" (or "Thank You"), and "I Love You".
Sequential Learning: Utilizes a Long Short-Term Memory (LSTM) neural network, essential for understanding the temporal dynamics of video-based gestures.
Computer Vision Pipeline: Integrates OpenCV and MediaPipe (for landmarks) for robust video processing and feature extraction.

Model Accuracy: The current trained model achieves a strong baseline performance with an approximate 67% accuracy.

Text Output: Provides immediate textual meaning for detected gestures.

## 💻 Technologies Used

Technology

Purpose

Python

Core implementation language.

OpenCV

Video capture and image pre-processing.

TensorFlow / Keras

Building and training the LSTM deep learning model.

NumPy

High-performance numerical and array operations.

JupyterLab / Notebook

Development environment for data processing and training.

## 💡 Use Cases

Assistive Technology: A foundational tool to help the hearing or speech-impaired communicate simple phrases.

ASL Education: An interactive aid for students to practice and verify the accuracy of their signs in real time.

Base for HRI: A starting point for developing advanced gesture-controlled systems and human-computer interaction (HCI) interfaces.

## 🖼️ Screenshots

1. Real-time Landmark Detection

This image displays the live video feed where the system successfully detects and tracks facial landmarks. These dynamic coordinates are the key features used to train the LSTM model.
![App Screenshot](./WhatsApp%20Image%202025-10-23%20at%2016.33.22_89650ad3.jpg)

2. Data Pre-processing and Shape

A snippet showing the data structuring phase, including the mapping of actions to numerical labels (hello, thanks, iloveyou) and confirming the input array shape ready for the deep learning model.
![App Screenshot](./WhatsApp%20Image%202025-10-23%20at%2017.15.52_c24e6aba.jpg)

3. Model Evaluation and Accuracy

Final model output showing the confusion matrix and the calculated accuracy_score of 0.6705, confirming the model's performance on the validation set.
![App Screenshot](./WhatsApp%20Image%202025-10-23%20at%2017.16.31_820e90f9.jpg)

