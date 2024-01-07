# Credit Card Fraud Detection

![Clustering football player.png](https://github.com/alimirash/Credit-Card-Fraud-Detection/blob/main/dataset-cover.jpg)


This project implements a machine learning model to detect fraudulent credit card transactions.

## Data

The creditcard.csv dataset contains transactions made with credit cards in September 2013 by european cardholders. It contains 31 features, where the last feature ('Class') indicates whether the transaction was fraudulent (1) or not (0).

## Approach

The following steps were taken in this analysis:

1. Data exploration: The data is explored through clustering, visualization, and statistics to understand its properties.

2. Data preprocessing: The data is split into training and test sets for modeling.

3. Modeling: A logistic regression model is trained on the data to classify transactions as fraudulent or not.

4. Evaluation: The model is evaluated on the test set using accuracy, precision, recall, F1 score, and ROC AUC. 

5. Results: The model achieves high performance in detecting fraudulent transactions.

## Files

- `creditcard.csv` - Input dataset 
- `fraud_detection.ipynb` - Jupyter notebook containing the code and analysis

## Usage

To run the code, simply run the cells in order in the Jupyter notebook. The output will include visualizations, metrics, and analysis of the model's performance.

## Conclusion

The logistic regression model is effective at detecting fraudulent credit card transactions based on the given dataset. Further improvements can be made by tuning model hyperparameters and testing additional algorithms.
