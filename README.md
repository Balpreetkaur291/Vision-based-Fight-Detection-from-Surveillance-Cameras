# Vision-based-Fight-Detection-from-Surveillance-Cameras
Detection of Fight from  Surveillance Cameras

This project aims to detect fights in videos using a deep learning model. The approach combines Convolutional Neural Networks (CNN) for feature extraction and Long Short-Term Memory (LSTM) networks to analyze sequences of video frames, making it suitable for video-based event detection tasks.

## Project Overview

## Model Architecture

The model follows this architecture:

1. **VGG19 (pre-trained on ImageNet)**: 
   - VGG19 is used to extract features from each individual video frame. The model is pre-trained on the ImageNet dataset, allowing it to leverage learned weights for feature extraction.

2. **LSTM Layer**: 
   - The network uses a Long Short-Term Memory (LSTM) layer to capture temporal patterns across the sequence of frames. The LSTM helps in understanding the dynamic movement and patterns in the video.

3. **Fully Connected Layers**: 
   - After feature extraction and sequence modeling, the model includes fully connected (dense) layers. These layers are used for classification, followed by a sigmoid output layer to output binary predictions (either "fight" or "non-fight").


