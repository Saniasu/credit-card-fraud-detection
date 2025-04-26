# Credit Card Fraud Detection

## Objective
This project is about building a machine learning model that can detect fraudulent credit card transactions. I worked on minimizing false positives while making sure the model stays accurate and reliable.

## Dataset
- The dataset is from Kaggle: [Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud).
- It has 284,807 transactions, but only 492 are frauds, making it a highly imbalanced dataset.

## What I Did
- I started with exploring the data to understand it better.
- Then I created some new features like Normalized Transaction Amount and extracted Transaction Hour from the Time feature.
- Since the data was imbalanced, I used SMOTE to handle the imbalance by oversampling the minority class (frauds).
- I trained a Random Forest Classifier to predict whether a transaction is fraud or not.
- Finally, I evaluated the model using confusion matrix, classification report, ROC curve, and ROC-AUC score.

## How to Run
1. Clone this repository.
2. Open the `credit_card_fraud_detection.ipynb` notebook in Google Colab or Jupyter Notebook.
3. Upload the `creditcard.csv` dataset (you can download it from Kaggle).
4. Run all cells step-by-step.

## Results
- The model gave a high ROC-AUC score.
- SMOTE helped to balance the data and improve the detection of frauds.
- I was able to minimize the number of false positives while keeping good accuracy.

## Contact
If you have any questions or feedback, feel free to contact me.
