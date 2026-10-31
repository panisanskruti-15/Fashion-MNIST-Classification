# Fashion MNIST Classification Using Deep Learning

## Project Overview
This project focuses on classifying clothing images using a deep learning neural network built with TensorFlow and Keras.

## Dataset
- Dataset: Fashion MNIST
- Training images: 60,000
- Testing images: 10,000
- Image dimensions: 28 × 28
- Number of classes: 10

## Technologies Used
- Python
- TensorFlow and Keras
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- TensorBoard

## Model Architecture
- Flatten layer
- Dense layer: 512 neurons (ReLU)
- Dense layer: 256 neurons (ReLU)
- Dense layer: 128 neurons (ReLU)
- Output layer: 10 neurons (Softmax)

## Model Performance

| Metric | Result |
|---|---:|
| Training Accuracy | 91.43% |
| Validation Accuracy | 88.99% |
| Test Accuracy | 88.82% |
| Test Loss | 0.3269 |

## Project Workflow
1. Dataset loading and exploration
2. Data preprocessing
3. Neural network construction
4. Model training and TensorBoard visualization
5. Model evaluation
6. Model saving and verification

## Conclusion
The project demonstrates an end-to-end deep learning workflow for image classification using TensorFlow and Keras.
