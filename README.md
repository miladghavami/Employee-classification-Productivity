# employee Productivity Classification
This project focuses on predicting employee productivity levels using real-world working hours data collected across multiple weekdays. The goal is to build robust machine learning models that classify productivity into three levels, addressing class imbalance and optimizing performance through careful preprocessing and model tuning.

# 📊 Project Overview
Objective: Predict productivity class (0, 1, 2) of employees based on their working hours data.

Data Sources: Datasets from different weekdays (Tuesday, Thursday, Friday) containing features such as working hours and activity logs.

Problem Type: Multi-class classification

# 🛠️ Technologies Used
Programming Language: Python

Libraries & Tools:
Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, GridSearchCV, SMOTE

# 📈 Workflow Summary
Data Preprocessing

Handled missing values and outliers.

Performed feature scaling and encoding.

Addressed class imbalance using resampling (undersampling/SMOTE).

Model Building

Trained and compared Logistic Regression, Random Forest, and XGBoost classifiers.

Performed hyperparameter tuning using GridSearchCV.

Evaluation

Used metrics such as Accuracy, F1 Score, Precision, and Recall.

Compared performance across macro and weighted averages to assess fairness.

Generated classification reports for validation and test sets.

# 🏆 Results
Best Models: XGBoost & Random Forest

Test Accuracy: 97.7%

Weighted F1 Score: 98.5%

Key Insight: XGBoost and Random Forest models demonstrated strong recall on minority classes while maintaining high accuracy on the majority class.

# 📌 Key Takeaways
Balanced class distribution significantly improved model fairness.

XGBoost offered consistent performance even with class imbalance.

Precision/Recall trade-offs helped identify opportunities for further improvement, especially for underrepresented productivity levels.

# 🚀 Future Work
Implement advanced resampling or cost-sensitive learning.

Extend analysis with time-series features or productivity trends over weeks.

Deploy model as an API or integrate into a dashboard for real-time monitoring.

