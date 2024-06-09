# Machine Learning Workflow

## Introduction

This project aims to classify wine types using machine learning algorithms. The workflow includes data exploration, preprocessing, feature engineering, model training, evaluation, and comparison of different classifiers.

## Prerequisites

Before you begin, ensure you have met the following requirements:
- You have installed [Python 3.x](https://www.python.org/downloads/) / [Anaconda](https://www.anaconda.com/download)
- You have a working internet connection

## Installation

To clone and run this repository on your local machine, follow these steps:

1. Clone the repository
   ```bash
   git clone https://github.com/Lambodol76/Machine-Learning-Assignment-2.git
   cd Machine-Learning-Assignment-2

2. Open it in Anaconda's Jupiter Notebook / VSCode.


### 1. Data Exploration
- Load the wine dataset and understand its structure.
- Display statistics and visualize the data.
<img width="500" alt="Screenshot 2024-06-09 at 3 47 49" src="https://github.com/Lambodol76/Machine-Learning-Assignment-2/assets/78098754/64081b69-4bbe-475d-8e7c-b9abac80f7fb">
<img width="450" alt="Screenshot 2024-06-09 at 3 48 41" src="https://github.com/Lambodol76/Machine-Learning-Assignment-2/assets/78098754/9a6dd870-286d-4808-ba70-3adb83f7c60c">

### 2. Preprocessing + Feature Engineering
- Scale the train and test sets.
- Apply Min-Max Scaling, Standardization, and Quantization.

<img width="750" alt="Screenshot 2024-06-09 at 3 51 56" src="https://github.com/Lambodol76/Machine-Learning-Assignment-2/assets/78098754/7463b32d-b9a3-411a-b2b7-62aad7ee76f6">


### 3. Model Building and Training + Model Evaluation
- Build a model using K-NN, Naive Bayes, Decision Trees and Neural Networks.
<img width="750" alt="Screenshot 2024-06-09 at 3 54 16" src="https://github.com/Lambodol76/Machine-Learning-Assignment-2/assets/78098754/fdc12ff5-0929-46b5-93e4-39df53c79708">
<img width="894" alt="Screenshot 2024-06-09 at 4 01 37" src="https://github.com/Lambodol76/Machine-Learning-Assignment-2/assets/78098754/7efaa96c-c3b7-4ca8-8254-d3ca57074b1a">
<img width="761" alt="Screenshot 2024-06-09 at 3 58 43" src="https://github.com/Lambodol76/Machine-Learning-Assignment-2/assets/78098754/157c21f3-3045-41dc-bd78-9384c201e05e">
<img width="259" alt="Screenshot 2024-06-09 at 3 58 51" src="https://github.com/Lambodol76/Machine-Learning-Assignment-2/assets/78098754/a0ae2cf3-642c-4521-8748-47397d85be32">
<br>
<img width="416" alt="Screenshot 2024-06-09 at 3 58 59" src="https://github.com/Lambodol76/Machine-Learning-Assignment-2/assets/78098754/84dfccdb-0841-45b8-9107-e091e5d5abbd">

### 4. Hyperparameter Tuning
<img width="750" alt="Screenshot 2024-06-09 at 4 05 22" src="https://github.com/Lambodol76/Machine-Learning-Assignment-2/assets/78098754/b5775bfc-8aab-4ef4-8de8-5cc983c67717">
<img width="453" alt="Screenshot 2024-06-09 at 4 06 01" src="https://github.com/Lambodol76/Machine-Learning-Assignment-2/assets/78098754/f1157dc7-2a5a-4d3a-a5ab-1feabb60e290">

### Conclusion

This project demonstrates the complete workflow for classifying wine types using multiple machine learning algorithms, including data exploration, feature engineering, model training, and evaluation. The best model is chosen based on the highest F1 Score using grid search with cross-validation.

