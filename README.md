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

### Dataset
This project uses X-ray images dataset on kaggle which can be accessed through:
- bone fracture detection using x-rays: https://www.kaggle.com/datasets/vuppalaadithyasairam/bone-fracture-detection-using-xrays/data
- Size: 183 MB
- Classes: Fractured and Non-fractured X-rays

### Model Architecture

Base Model: Xception (pre-trained on ImageNet) \n
Additional layers:

GaussianNoise (0.2)
GlobalAveragePooling2D
Dense layers (256, 128 units)
Batch Normalization
Dropout (0.3)



### Results

Training Accuracy: 96.2%
Validation Accuracy: 98.5%

## Requirements
python
tensorflow==2.x
numpy
pandas
scikit-learn
imbalanced-learn
pillow
opencv-python



Future Improvements

- Add data augmentation techniques
- Implement cross-validation
- Add visualization of results
- Deploy model as web application
