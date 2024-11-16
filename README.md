# XRayDeep
A deep learning model built using TensorFlow/Keras to detect bone fractures in X-ray images. The model uses a modified Xception architecture with custom layers for binary classification of fracture/non-fracture cases.
## Overview
A deep learning model built using TensorFlow/Keras to detect bone fractures in X-ray images. The model uses a modified Xception architecture with custom layers for binary classification of fracture/non-fracture cases.

## Features
- Binary classification of X-ray images (fracture/normal)
- Data preprocessing and augmentation
- Balanced dataset handling
- Transfer learning using Xception architecture
- Custom model architecture with regularization

## Requirements
python
tensorflow==2.x
numpy
pandas
scikit-learn
imbalanced-learn
pillow
opencv-python

Model Architecture

Base Model: Xception (pre-trained on ImageNet)
Additional layers:

GaussianNoise (0.2)
GlobalAveragePooling2D
Dense layers (256, 128 units)
Batch Normalization
Dropout (0.3)



Results

Training Accuracy: XX%
Validation Accuracy: XX%
Test Accuracy: XX%

Future Improvements

- Add data augmentation techniques
- Implement cross-validation
- Add visualization of results
- Deploy model as web application
