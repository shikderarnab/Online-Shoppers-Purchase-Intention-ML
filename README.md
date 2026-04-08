"Predicting Online Shoppers’ Purchase Intention Using Machine Learning"

Project Overview:
This project aims to predict whether an online shopper will complete a purchase based on session-level behavioral data.
Several machine learning models are implemented and compared to analyze user behavior and purchasing intention in e-commerce platforms.

The project is developed as part of an academic research/practical work and focuses on model comparison and performance evaluation.

Dataset Description:
- Dataset Name: Online Shoppers Purchasing Intention Dataset  
- Source: UCI Machine Learning Repository  
- Instances: 12,330 user sessions  
- Features: 18 (numerical and categorical)  
- Target Variable: `Revenue` (True = Purchase, False = No Purchase)

The dataset contains session-based features such as page visits, duration, bounce rates, and traffic information.

Methodology:

The following steps were performed in this project:

1. Data loading and basic exploration  
2. Handling categorical variables using label encoding  
3. Feature scaling using StandardScaler  
4. Train-test split (80% training, 20% testing)  
5. Model training using:
   - Logistic Regression
   - Random Forest
   - XGBoost
6. Model evaluation using:
   - Accuracy
   - Precision
   - Recall
   - F1 Score
7. Comparative performance analysis

Machine Learning Models Used:
- Logistic Regression** (Baseline model)
- Random Forest Classifier**
- XGBoost Classifier**

These models were selected to compare linear, ensemble, and boosting-based approaches.

Results and Evaluation:
The models were evaluated using standard classification metrics.
A comparison table is used to identify the best-performing model.

Key evaluation metrics:
- Accuracy
- Precision
- Recall
- F1 Score

Graphical visualizations such as confusion matrices and ROC curves are also included in the notebook.

Technologies Used:
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Matplotlib
- Seaborn

Conclusion:
The experimental results demonstrate that ensemble-based models outperform linear models for predicting online shopping purchase intention.
XGBoost and Random Forest achieve superior performance compared to Logistic Regression.

The findings highlight the effectiveness of machine learning techniques in understanding and predicting user behavior in e-commerce applications.

Future Work
- Hyperparameter tuning for improved performance
- Testing additional models such as Gradient Boosting or Neural Networks
- Handling class imbalance using resampling techniques
- Applying the methodology to larger real-world datasets
