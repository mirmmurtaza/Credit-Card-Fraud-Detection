# Credit Card Fraud Detection

This project involved the development of machine learning models for detecting fraudulent credit card transactions. The data used in the models was anonymized and consisted of numerical columns, with the output indicating whether the transaction was fraudulent or not. The output was highly imbalanced, which means that there were a lot more non-fraudulent transactions than fraudulent ones.

To build the models, the data was first analyzed and visualized to understand its distribution. Transformations were then applied to the data to make it suitable for model building. Sampling techniques such as SMOTE, ADASYN, Random Under Sampling and Random Over Sampling were applied to balance the output.

To select the best model for the task, various algorithms were applied, including Logistic Regression, SVC, and XGboost. Hyper-parameter tuning was also used for cross-validation. The model achieved a Recall score of 94% on the test data, which means that it was able to detect 94% of the actual fraudulent transactions in the dataset.

Overall, this project demonstrates the application of machine learning in detecting fraudulent credit card transactions and showcases various techniques and algorithms that can be used for this task.
