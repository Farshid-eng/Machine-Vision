Machine Learning & Deep Learning Models (TensorFlow)
📌 Overview

This repository contains a collection of core Machine Learning and Deep Learning models implemented in TensorFlow, with a focus on understanding model architectures, training logic, and practical usage.

The implementations range from fundamental CNN architectures to autoencoders and transfer learning pipelines, making this repository suitable for learning, experimentation, and portfolio demonstration.

🧠 Implemented Models
🔹 AlexNet

Classic deep convolutional neural network

Demonstrates:

Deep CNN architecture design

Large-kernel convolutions

Dropout for regularization

Useful for understanding early breakthroughs in deep learning

🔹 Convolutional Neural Network (CNN)

Custom CNN implementation from scratch

Covers:

Convolution, pooling, and fully connected layers

Feature extraction vs classification stages

Serves as a baseline for image-based ML tasks

🔹 Autoencoder

Unsupervised learning model for:

Feature learning

Dimensionality reduction

Data reconstruction

Demonstrates encoder–decoder architecture and reconstruction loss

🔹 ResNet – Transfer Learning

Transfer learning using a pretrained ResNet

Includes:

Freezing and fine-tuning layers

Custom classification head

Efficient reuse of pretrained features

Suitable for real-world image classification tasks with limited data

🔹 Transfer Learning (General)

General transfer learning workflow

Covers:

Loading pretrained models

Modifying final layers

Training strategies for convergence and stability

Emphasizes practical ML engineering concepts

🛠️ Technologies Used

Python

TensorFlow / Keras

NumPy

Matplotlib (for visualization where applicable)

📂 Repository Structure

.
├── AlexNet.ipynb
├── CNN.ipynb
├── Autoencoder.ipynb
├── ResNet_Transfer_Learning.ipynb
├── Transfer_Learning.ipynb
└── README.md

🎯 Purpose of This Repository

Build a strong conceptual foundation in deep learning

Understand differences between architectures

Practice transfer learning strategies used in industry

Serve as a portfolio repository for ML / DL roles

🚀 How to Run

Clone the repository:
git clone https://github.com/your-username/your-repo-name.git

Open any notebook:
jupyter notebook

Run cells sequentially to explore each model.

📌 Notes

Focus is on clarity and learning, not hyperparameter optimization

Each notebook is structured to highlight architecture and training logic

Models can be extended for custom datasets and tasks
