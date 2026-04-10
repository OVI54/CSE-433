# Problem Set 2

Objective
1.The objective of this project is to predict whether a customer will subscribe to a term deposit.

Dataset
2.The dataset used is the Bank Marketing Dataset (bank-full.csv).

Methodology
1.Data preprocessing (handling categorical and numerical features)
2.One-hot encoding for categorical variables
3.Standard scaling for numerical features
4.Logistic Regression model used for classification

Code Explanation
1.Data loaded using pandas
2.Preprocessing done using ColumnTransformer
3.Model built using Pipeline
4.Model trained and evaluated using classification metrics and ROC-AUC

Results / Findings
1.The model achieved a good ROC-AUC score
2.Important features were identified using model coefficients

Conclusion
1.Logistic Regression performs reasonably well for this classification problem.
