# 🎨 Color Matching for Colorblind Users

This repository contains the deep learning model behind a system designed to assist colorblind individuals in selecting visually harmonious outfit combinations.

## 🧠 Project Goal

The model helps suggest outfit color pairings by learning patterns of color compatibility from image data. It's part of a broader effort to make fashion more accessible and inclusive through AI.

## 🧩 Model Overview

- **Architecture**: Variational Autoencoder (VAE)
- **Input**: Preprocessed RGB images of individual clothing items
- **Latent Space**: Encodes key visual/color features to learn harmony representation
- **Output**: Color vector predictions to guide matching with complementary items

## 🏗️ Key Features

- Image preprocessing using OpenCV
- Normalization and resizing to fit the model input
- Encodes visual color patterns into a latent space
- Trained to reconstruct and compare color compatibility between garments

## 🧪 Training Details

- Input size: 128x128 RGB images
- Optimizer: Adam
- Loss: Custom loss based on reconstruction + KL divergence
- Data: Fashion Anchor Cloth Pairs dataset with manual color labeling and matching


