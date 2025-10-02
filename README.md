# Multimodal Emotion Recognition Using CNN and Gradio

## Project Overview

This project implements an emotion recognition system that classifies human emotions from facial images using a Convolutional Neural Network (CNN). It offers an interactive web interface powered by Gradio, enabling users to upload images and get real-time emotion predictions.

---

## Features

- **Dataset Preparation:** Reads and processes facial emotion image datasets with directory-based emotion labels.
- **CNN Model:** Multi-layer CNN architecture for grayscale images to classify emotions such as happy, sad, angry, surprise, neutral, fear, and disgust.
- **Interactive Web UI:** Uses Gradio to allow users to upload images and receive emotion classification results instantly.
- **Model Persistence:** Saves the trained model in the native Keras format for easy deployment and reuse.
- **Flexible Deployment:** Runs seamlessly on Google Colab, Jupyter Notebook, or local environments.

---

## Getting Started

### Prerequisites

- Python 3.8+
- TensorFlow 2.x
- Gradio
- OpenCV (for image preprocessing)
- Other dependencies: numpy, matplotlib, pandas


### Usage

#### 1. Train the CNN Model

Train the model on your facial emotion image dataset organized into emotion subfolders:


#### 2. Launch Gradio App for Prediction

A simple web UI to upload images and predict emotions:


---

## Future Work

- Extend to multimodal fusion by incorporating audio and video.
- Improve CNN with transfer learning from pretrained architectures.
- Real-time webcam emotion detection support.
- Deploy as a standalone web service.

---

## License

This project is licensed under the MIT License - see the LICENSE file for details.
