# Bank Customer Churn Prediction

This project predicts **bank customer churn** using a **deep learning model (Artificial Neural Network - ANN)**. It covers data preprocessing, feature scaling, model training, and performance evaluation using **precision, recall, and F1-score**.

## Dataset

The dataset is from Kaggle: [Bank Customer Churn Modeling](https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling)

It includes the following features:

* **Customer demographics**: `Gender`, `Age`, `Geography`
* **Account information**: `CreditScore`, `Balance`, `NumOfProducts`, `HasCrCard`, `IsActiveMember`
* **Financial details**: `EstimatedSalary`
* **Target variable**: `Exited` (1 = churned, 0 = retained)

## Project Features

* **Data Preprocessing**: Encode categorical variables (`Gender`, `Geography`) into numerical form
* **Feature Scaling**: Normalize numerical variables for stable ANN training
* **Modeling**: Build a feed-forward ANN using TensorFlow/Keras
* **Evaluation**: Assess performance with confusion matrix and classification report

## How to Run

1. Clone this repository:

   ```bash
   git clone <repo-url>
   ```

2. Install required packages:

   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn tensorflow
   ```

3. Run the Jupyter notebook or Python script to train the model and generate predictions.

## Results

* Achieves strong accuracy in predicting customer churn
* Provides detailed metrics: **precision, recall, F1-score**
* Enables banks to identify customers with high churn risk

## License

This project is released under the MIT License.
