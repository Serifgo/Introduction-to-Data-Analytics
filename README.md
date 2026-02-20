# Introduction-to-Data-Analytics

The project analyzes customer churn of a fictitious telecommunications company using a dataset provided by IBM. The objective is to identify the key factors that lead to customer cancellations and to build predictive machine learning models that support proactive customer retention strategies.

First, an exploratory data analysis is conducted to understand the structure, distributions, and relationships within the dataset. Special focus is placed on the target variable Churn, which indicates whether a customer has left the company.

During the data preparation phase, missing values are handled, irrelevant features are removed, and new derived features such as TotalExtraServices, CustomerEngagementScore, and MultipleServices are created. The dataset is then split into training and test sets.

For model development, a Decision Tree and a Random Forest classifier are implemented. Hyperparameter tuning is performed using GridSearchCV, and the models are evaluated using metrics such as accuracy, precision, recall, F1-score, and confusion matrix. In addition, permutation importance is applied to determine the most influential features affecting churn prediction.

Finally, the models are compared in terms of performance and business applicability. The ultimate goal is to identify customers at risk of churn at an early stage and enable targeted retention measures.

# 1 

[Link to the project: Telco Customer Churn ](https://www.kaggle.com/code/sgoeren24/projekt-telco-customer-churn-v3)

# 2

- **Python** as the programming language for data analysis and modeling

- **Pandas** for data preprocessing and manipulation

- **NumPy** for numerical computations

- **Matplotlib** and **Seaborn** for data visualization and analytical plots

- **Scikit-learn** for implementing and evaluating machine learning models (Decision Tree, Random Forest)

- **Kaggle Notebooks** as the development environment
