# Flower Image Classification using Machine Learning

## Overview

This project compares three machine learning algorithms for flower image classification:

- Gaussian Naive Bayes
- Decision Tree
- Multilayer Perceptron (MLP)

The goal is to evaluate classification performance and analyze the trade-offs between model complexity, accuracy, and computational cost.

## Dataset

- Flowers Recognition Dataset
- 1,220 flower images
- Four classes:
  - Daisy
  - Rose
  - Sunflower
  - Tulip

All images were resized to 224×224 pixels before feature extraction.

## Implemented Models

### Gaussian Naive Bayes
- Color channel statistics
- Mean
- Standard deviation
- Median
- Fast baseline classifier

### Decision Tree
- RGB histogram features
- Mean and standard deviation features
- Interpretable classification model

### Multilayer Perceptron (MLP)
- Two hidden layers (100, 50 neurons)
- Logistic activation function
- Learning rate = 0.001
- Nonlinear feature learning

## Results

| Model | Accuracy |
|---------|---------|
| Naive Bayes | 43% |
| Decision Tree | 43% |
| MLP | 57% |

The MLP achieved the highest classification accuracy and demonstrated better class separation and generalization.

## Technologies Used

- Python
- Google Colab
- Scikit-Learn
- NumPy
- Pandas
- Matplotlib
- OpenCV
- Machine Learning
- Neural Networks

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
## Resources

- Dataset and Project Files: [Google Drive Folder](https://drive.google.com/drive/folders/1vgb2I8IVW6Xp4Mwi505qMi7vufZTtjgP?usp=drive_link))
## Authors

Sara Al Souqi
Sawsana Atari

Birzeit University
