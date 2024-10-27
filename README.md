# Plant Disease Detection Using Convolutional Neural Networks



This project leverages Convolutional Neural Networks (CNNs) to classify and detect plant diseases from images. By employing deep learning techniques, we aim to enhance agricultural health monitoring and provide farmers with timely insights.


## Features

- Image classification for 25 different plant diseases.
- Data augmentation techniques for improved model robustness.
- Model saving and loading functionality for future predictions.



## Dataset

The dataset is organized into training and testing directories, containing images of healthy and diseased plants. Each class is represented in its own subdirectory.

- **Training Set**: `/dataset/train`
- **Testing Set**: `/dataset/test`

Make sure to update the paths in the code to point to your dataset.



## Model Architecture

The CNN consists of:
- Multiple convolutional layers for feature extraction.
- Max pooling layers for dimensionality reduction.
- Batch normalization for stability.
- Dropout layers for regularization.
- Dense layers for final classification.

## Results

Detailed metrics are logged during training.
