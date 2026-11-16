# Credit Card Fraud Detection Using Machine Learning and Deep Learning

## Project Overview
This project focuses on detecting fraudulent credit card transactions using Machine Learning and Deep Learning techniques. It analyzes transaction data and classifies transactions as legitimate or fraudulent.

The project uses an Artificial Neural Network (ANN) to identify potentially fraudulent transactions.

## Technologies Used
- Python
- Google Colab
- Pandas
- NumPy
- Scikit-learn
- TensorFlow / Keras
- Matplotlib

## Dataset
The project uses the Credit Card Fraud Detection dataset containing 284,807 transactions, including:
- 284,315 legitimate transactions
- 492 fraudulent transactions

The dataset contains anonymized transaction features and a target column named `Class`.

- `0` – Legitimate Transaction
- `1` – Fraudulent Transaction

## Implementation

1. Data Loading – Importing and exploring the dataset.
2. Data Preprocessing – Handling features and scaling transaction values.
3. Data Splitting – Dividing data into training and testing sets.
4. ANN Model Development – Building a neural network using TensorFlow/Keras.
5. Model Training – Training the ANN using the Adam optimizer and binary cross-entropy loss.
6. Fraud Prediction – Predicting whether transactions are fraudulent or legitimate.
7. Model Evaluation – Evaluating results using a confusion matrix, precision, recall, and F1-score.

## Deep Learning Architecture

The Artificial Neural Network consists of:
- Input Layer
- Hidden Layer 1 – 32 neurons (ReLU)
- Hidden Layer 2 – 16 neurons (ReLU)
- Output Layer – 1 neuron (Sigmoid)

Class weighting is used to address the imbalance between legitimate and fraudulent transactions.

## Results
The model generates predictions for credit card transactions and evaluates performance using:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

## Objective
The main objective is to demonstrate how Machine Learning and Deep Learning can be applied to financial fraud detection and help identify suspicious transactions.

## Future Scope
- Improve fraud detection performance.
- Experiment with additional Deep Learning architectures.
- Develop a real-time fraud detection system.
- Integrate a user-friendly web interface.

## Author
Developed as an academic project to explore Machine Learning and Deep Learning applications in financial security.
