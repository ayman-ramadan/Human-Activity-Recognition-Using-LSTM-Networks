# Human Activity Recognition Using Deep Learning

This project implements a deep learning model to classify human physical activities (such as walking, sitting, and jogging) based on sensor data collected from smartphones. The objective is to predict the correct activity using accelerometer and gyroscope time series data.

## Project Overview

- **Goal:** Accurately classify human activities using a supervised deep learning model.
- **Dataset:** Human Activity Recognition dataset containing multivariate time series from smartphone sensors, with over 10,000 labeled samples.
- **Classes:** Includes activities like walking, walking upstairs, walking downstairs, sitting, standing, and lying down.
- **Model Architecture:** A 1D Convolutional Neural Network (CNN) or LSTM-based model (as used in the notebook) was designed for temporal pattern recognition.

## Key Features

- **Data Preprocessing:** Normalized and reshaped multi-sensor time series data; labels encoded for classification.
- **Model Development:** Implemented an LSTM architecture with dropout layers to prevent overfitting.
- **Evaluation:** Achieved an accuracy of over **92%** on the test set, with precision, recall, and F1-score computed for all classes.
- **Visualization:** Confusion matrix and loss/accuracy graphs for model analysis.

## Tools & Technologies

- Python
- Pandas, NumPy
- TensorFlow, Keras
- Matplotlib, Seaborn
- Scikit-learn

