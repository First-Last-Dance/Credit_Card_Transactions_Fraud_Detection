# Credit Card Fraud Detection

## Overview
This project focuses on detecting fraudulent credit card transactions using machine learning techniques. It aims to develop robust algorithms to identify fraudulent transactions while minimizing false positives.


## Project Structure
The project is structured into the following sections:

1. **Dataset**
2. **Data Preprocessing**
3. **Modeling**
4. **Evaluation**
5. **Results**
6. **Conclusion**


## Dataset
The dataset used for this project is available on Kaggle: [Fraud Detection Dataset](https://www.kaggle.com/datasets/kartik2112/fraud-detection).

## Data Preprocessing
The data preprocessing steps include:
- Dropping irrelevant features.
- Creating new features (e.g., customer age).
- Removing redundant location features.
- Identifying and handling outliers.
- Reducing the feature set to avoid the curse of dimensionality and overfitting.

## Modeling
Four machine learning models were tested:
1. Support Vector Machine (SVM)
2. AdaBoost
3. Random Forest
4. Logistic Regression

## Evaluation
The evaluation metrics used are:
- **Accuracy:** Proportion of correctly classified instances.
- **Precision:** Proportion of correctly identified fraudulent transactions.
- **Recall (Sensitivity):** Proportion of truly fraudulent transactions correctly identified.
- **F1 Score:** Harmonic mean of precision and recall.

Due to the imbalanced nature of the dataset (1289160 non-fraudulent vs. 7506 fraudulent transactions), both over-sampling and under-sampling techniques were applied.

## Results
- **Over-Sampling:** Improved the model performance by balancing the data.
- **Under-Sampling:** Also used to balance the data, providing different insights.

The best models for this problem were AdaBoost and Random Forest.

## Conclusion
The project successfully identified methods to reduce redundant information and balance the dataset. AdaBoost and Random Forest models showed the best performance in detecting fraudulent transactions.
