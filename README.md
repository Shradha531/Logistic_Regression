# Housing Price Classification Using Logistic Regression

## 1. Project Overview
This project uses Logistic Regression to classify houses into two categories: Low Price and High Price.

The project uses the Housing.csv dataset. The original numerical house price is converted into a binary classification target using the median house price.

## 2. Dataset
- Dataset: Housing.csv
- Total records: 545
- Original columns: 13
- Target variable: `price_category`

### Target Categories
- 0: Low Price (price less than or equal to the median)
- 1: High Price (price greater than the median)

## 3. Technologies Used
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## 4. Project Workflow
1. Import required libraries.
2. Load the Housing.csv dataset.
3. Perform data exploration.
4. Check missing values and duplicate records.
5. Visualize house price distribution.
6. Create the binary target variable.
7. Encode categorical features.
8. Split data into training and testing sets.
9. Apply feature scaling.
10. Train the Logistic Regression model.
11. Make predictions.
12. Evaluate model performance.

## 5. Model Evaluation
The model is evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

## 6. Conclusion
This project demonstrates how Logistic Regression can be applied to a housing dataset for binary classification. It predicts whether a house belongs to the Low Price or High Price category based on its features.
