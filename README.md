ECG Signal Classification Project

     Overview

This project focuses on classifying ECG signals using a combination of signal processing techniques and machine learning models. The goal is to accurately differentiate between different types of heartbeats based on the provided ECG data.

     Project Structure

data/: Contains the ECG datasets used for training and testing.
models/: Stores the trained machine learning models.
src/: Includes the Python scripts for feature extraction, model training, and evaluation.
README.md: Provides an overview of the project, its structure, and instructions on how to run the code.
Dependencies

 To run this project, you need to install the following dependencies:

Python 3.x
NumPy
Pandas
Scipy
scikit-learn
TensorFlow
PyWavelets

     Data Preparation

Loading the Data: The ECG data is loaded from the data/ directory.
Preprocessing: The data is preprocessed to handle missing values, and labels are standardized.
Feature Extraction: Features are extracted from the ECG signals using FFT (Fast Fourier Transform) and SWT (Stationary Wavelet Transform).
Model Training

The following models are trained on the extracted features:

Convolutional Neural Network (CNN)
Long Short-Term Memory (LSTM)
Bidirectional LSTM (BiLSTM)
Each model is evaluated on the test data, and accuracy and classification reports are generated.

     How to Run

Prepare the environment:
Ensure all dependencies are installed.
Load your ECG dataset into the data/ directory.
Run the feature extraction:
The feature extraction scripts are located in the src/ directory. Execute these scripts to extract features from the raw ECG signals.
Train the models:
Run the model training scripts in the src/ directory. The trained models will be saved in the models/ directory.
Evaluate the models:
Evaluate the trained models on the test dataset. The results will be printed in the terminal and can be saved for further analysis.
Results

The models' performance is evaluated using accuracy and detailed classification reports. The results are used to assess which model performs best for ECG signal classification.

     Future Work

Experiment with different signal processing techniques for feature extraction.
Optimize model hyperparameters using advanced techniques such as Bayesian Optimization.
Test the models on larger and more diverse datasets to improve generalization.
