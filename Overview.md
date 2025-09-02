# Medicinal Plant Identification using Deep Learning
## Overview
This project focuses on the automated identification and retrieval of medicinal plants using deep learning techniques. By combining EfficientB4Net, CBAM, and a Residual Block Decoder, the model achieves 95% accuracy, enabling reliable plant classification for applications in biodiversity preservation, healthcare, and conservation.

## Features
  - Automated Plant Identification: Identifies twenty groups of medicinal plants from the Southern Indian region.
  - Efficient Feature Extraction: Uses EfficientB4Net for compressing and encoding plant features.
  - Noise Reduction: Residual Block Decoder reconstructs input features while eliminating noise.
  - Attention Mechanism: CBAM improves accuracy by focusing on essential channel and spatial features.
  - Image Retrieval: Compares query images with a feature database using similarity measures for precise classification.
  - Real-Time Compatibility: Can integrate with webcam-based plant recognition systems for instant identification.

## Key Components
  - Dataset Collection: SIMP dataset of medicinal plants, collected in unconstrained environmental conditions.
  - Preprocessing Module: Data augmentation and feature refinement using CBAM and residual blocks.
  - Autoencoder Model: EfficientB4Net encoder with residual decoders for feature extraction and reconstruction.
  - Training & Testing Modules: Model trained using TensorFlow/Keras with evaluation metrics such as precision, recall, F1-score, and accuracy.
  - User Interface (Future Scope): Potential mobile/web application for real-time plant recognition with detailed medicinal information.

## Usage
  - Dataset Preparation: Collect and preprocess medicinal plant images from the SIMP dataset or real-time sources.
  - Model Training: Train the autoencoder model in Jupyter Notebook/Google Colab using TensorFlow and GPU acceleration.
  - Testing: Provide a query plant image; the system extracts features and compares them with stored database features.
  - Output: Identifies the plant species with high accuracy and retrieves visually similar images.
  - Future Integration: Deploy as a real-time recognition tool using webcams or mobile devices, supporting farmers, botanists, and healthcare practitioners.
