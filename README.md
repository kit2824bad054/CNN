# Cat vs Dog Image Classification

## Project Overview
This project uses a Convolutional Neural Network (CNN) to classify images into two categories: **Cat** and **Dog**.

## Dataset
The project uses 1,500 images:
- Training: 960 images
- Validation: 240 images
- Testing: 300 images

Images are resized to **64 × 64 pixels**.

## Technologies Used
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

## Model
The CNN model includes:
- Data augmentation
- Rescaling
- Convolutional layers
- Max Pooling
- Flatten layer
- Dense layer
- Dropout
- Binary classification output

## Results
The model achieved:
- **Accuracy:** 100%
- **Precision:** 100%
- **Recall:** 100%
- **F1-Score:** 100%
- **ROC-AUC:** 100%

The test set contained **150 Cat images and 150 Dog images**, with all 300 images classified correctly.

## How to Run
1. Open the notebook in Google Colab.
2. Run the cells in order.
3. The dataset is automatically generated if real photos are not available.
4. Train the CNN model.
5. Evaluate the model using the test dataset.

## Conclusion
The project demonstrates how CNNs can be used for effective binary image classification between cats and dogs.
