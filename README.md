# Plant Disease Detection Using Convolutional Neural Networks



This project leverages Convolutional Neural Networks (CNNs) to classify and detect plant diseases from images. By employing deep learning techniques, we aim to enhance agricultural health monitoring and provide farmers with timely insights.


## Features

- Image classification for 25 different plant diseases.
- Data augmentation techniques for improved model robustness.
- Model saving and loading functionality for future predictions.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/plant-disease-detection.git
   ```
   
2. Navigate to the project directory:
   ```bash
   cd plant-disease-detection
   ```

3. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Dataset

The dataset is organized into training and testing directories, containing images of healthy and diseased plants. Each class is represented in its own subdirectory.

- **Training Set**: `/dataset/train`
- **Testing Set**: `/dataset/test`

Make sure to update the paths in the code to point to your dataset.

## Usage

1. To train the model, run:
   ```bash
   python train_model.py
   ```

2. To make predictions on new images, use:
   ```bash
   python predict.py --image path/to/your/image.jpg
   ```

## Model Architecture

The CNN consists of:
- Multiple convolutional layers for feature extraction.
- Max pooling layers for dimensionality reduction.
- Batch normalization for stability.
- Dropout layers for regularization.
- Dense layers for final classification.

## Results

The model achieves a validation accuracy of approximately X% (replace with your actual result). Detailed metrics are logged during training.
