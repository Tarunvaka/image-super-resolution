# Image Super-Resolution Using Autoencoder

This project demonstrates how to use a convolutional autoencoder to enhance image resolution. The model is trained to map low-resolution images to their high-resolution counterparts, leveraging deep learning techniques for efficient super-resolution.

---

## Project Overview

- **Goal**: Develop a model to improve image resolution.
- **Approach**: Utilize a convolutional autoencoder with layers designed for feature extraction, dimensionality reduction, and upsampling.
- **Applications**: Image enhancement for photography, medical imaging, and surveillance.

---

## Features

- **Data Preprocessing**: Tools to create paired low- and high-resolution images for training.
- **Model Architecture**:
  - Convolutional layers for feature extraction.
  - Pooling layers for dimensionality reduction.
  - Upsampling layers for resolution recovery.
- **Training Tools**: Includes callbacks like `EarlyStopping` and `ReduceLROnPlateau` for efficient training.
- **Visualization**: Side-by-side comparison of original, low-res, and enhanced images.

---

## File Structure

- **Notebook**: Contains the complete implementation.
- **Data**: 
  - High-resolution images (`high_res` folder).
  - Generated low-resolution images (`low_res` folder).

---
