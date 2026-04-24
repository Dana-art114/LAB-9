# LAB-9
This project analyzes a loan dataset to predict whether a loan will be fully paid or not using machine learning models.

First, the data was explored and visualized to understand key patterns, such as the relationship between FICO score and interest rate. Categorical data (the purpose column) was converted into numerical form using dummy variables.

The dataset was then split into training and testing sets. Two models were trained and evaluated:

Decision Tree Classifier
Random Forest Classifier

Both models were assessed using classification reports and confusion matrices.

The results showed that while the Random Forest achieved higher overall accuracy, it performed poorly in identifying loans that were not fully paid (class 1). The Decision Tree, although less accurate overall, was better at detecting this important class.

In conclusion, model evaluation should not rely only on accuracy, especially when dealing with imbalanced data. Metrics like recall are crucial for understanding model performance.
