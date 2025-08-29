# Bank Customer Churn Prediction

This project predicts bank customer churn using a **deep learning model (Artificial Neural Network)**. It includes data preprocessing, feature scaling, and evaluation using metrics like **precision, recall, and F1-score**.

## Dataset

The dataset used is from Kaggle: [Bank Customer Churn Modeling](https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling)

It contains features like:  
- Customer demographics (`Gender`, `Age`, `Geography`)  
- Account information (`CreditScore`, `Balance`, `NumOfProducts`, `HasCrCard`, `IsActiveMember`)  
- Financial details (`EstimatedSalary`)  
- Target variable: `Exited` (1 = churned, 0 = retained)

## Features

- Data preprocessing: Convert categorical variables to numerical (`Gender`, `Geography`, etc.)  
- Scaling: Normalize numeric features for better ANN performance  
- Model: Simple ANN using TensorFlow/Keras  
- Evaluation: Confusion matrix and classification report

## How to Run

1. Clone this repository:  
```bash
git clone <repo-url>
````

2. Install required packages:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn tensorflow
```

3. Run the Jupyter notebook or Python script to train the model and see predictions.

## Results

* Predicts customer churn with high accuracy
* Provides classification report with **precision, recall, and F1-score**
* Helps banks identify customers likely to leave

