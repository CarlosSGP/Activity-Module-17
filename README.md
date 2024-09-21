# Activity-Module-17

Comparing Classification Models for Bank Marketing Data: Maximizing Precision and Recall

**Introduction**

This study analyzes direct marketing campaigns of a Portuguese banking institution. The goal is to predict whether or not clients will subscribe (yes/no) to a bank term deposit account. Four classification models were compared: logistic regression, k-nearest neighbors, decision tree, and support vector machine. Standardization was done using a standard scaler and categorical data was label encoded.

**Methodology**

The study optimized for true positives, which indicated precision as the most important score. Recall was also useful because it assessed if the model missed potential clients interested in the term deposit.

**Results**

Logistic regression and k-nearest neighbors had similar results with an accuracy of 0.89, while decision tree slightly underperformed at 0.87 and support vector machine was the most accurate at 0.90. However, decision tree performed best in maximizing precision and recall for the successful deposit account class. The permutation importance analysis revealed that campaign month and duration were the most important features, followed by the number of days the client was last contacted and the method of contact.

_Logistic Regression_

![image](https://github.com/user-attachments/assets/8f53ede6-8858-4ed9-80f7-0806d7367a58)

_K-Nearest Neighbors_

![image](https://github.com/user-attachments/assets/a9ddd87a-fed7-4d04-8fee-3252175501e3)

_Decision Tree_

![image](https://github.com/user-attachments/assets/5ed97bb9-037f-4d9d-9653-aee24886bb42)

_SVM_

![image](https://github.com/user-attachments/assets/281f0279-ecc7-48df-8d34-1cca4bd8d283)

**Conclusion**

The decision tree model is optimal for maximizing precision and recall for the successful deposit account class. Campaign month and duration are the most important features to consider when designing a marketing campaign.
