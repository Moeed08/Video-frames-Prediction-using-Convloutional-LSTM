# Video-frames-Prediction-using-Convloutional-LSTM
This repository contains the implementation of a ConvLSTM-based model designed for video frame prediction. The model predicts future frames in a video sequence, which can be used in various applications such as video compression, action recognition, or autonomous driving systems where predicting future frames is critical.

# Key Features:
ConvLSTM Architecture: A combination of Convolutional Neural Networks (CNNs) and Long Short-Term Memory (LSTM) cells, designed to capture both spatial and temporal features of video sequences.
# Multi-layer Setup:
The model is built with multiple ConvLSTM layers to enhance its ability to capture complex spatiotemporal dependencies.
# UCF101 Dataset:
The model is trained and evaluated on the UCF101 Action Recognition dataset, which consists of videos from various action categories.
# Frame Prediction:
The model is capable of predicting future frames given a sequence of input frames, providing a powerful tool for video generation and forecasting.
# Model Overview:
Input: A sequence of video frames.
Output: Predicted future frames of the video sequence.
# Core Architecture: 
ConvLSTM layers for learning spatiotemporal patterns, with hidden states and cell states to manage long-term dependencies.
# Dependencies:
torch (PyTorch)
torchvision
numpy
matplotlib
cv2 (OpenCV)
Other standard Python libraries like os, random, etc.

