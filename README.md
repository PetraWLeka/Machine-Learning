# Project Overview

This project aims to develop a high-accuracy classification system for distinguishing between screams and non-screams using various machine learning methods. In this project, we employ three main approaches: **Support Vector Machine (SVM), Logistic Regression, and Convolutional Neural Network (CNN)**. SVM and logistic regression are used to analyze Mel Spectrogram and Zero Crossing Rate (ZCR) features from audio signals, while CNN is used to analyze Mel Spectrogram images.

The SVM and logistic regression approaches leverage Mel Spectrogram and ZCR features to identify patterns in the audio signals. Through SVM, we attempt to distinguish between screams and non-screams by finding the optimal decision boundary among these features. Logistic regression, on the other hand, models the probability of a scream based on these features.

Additionally, we use a more advanced approach, CNN, to analyze Mel Spectrogram images. With CNN, we can automatically extract important features from these images and perform classification with a high degree of accuracy.

## Data Source

The data used in this project can be found at: [Kaggle - Raw Audio of Accident and Crime Detection](https://www.kaggle.com/datasets/afisarsy/raw-audio-of-accident-and-crime-detection).

## Project Files

- **pengenal_teriak.ipynb**: The final notebook containing the classification model.
- **Experimental code**: Contains code in the development stage.
- **generate_noise_in_data.ipynb**: Used to add noise to scream data to make it more representative of real-world scenarios.
