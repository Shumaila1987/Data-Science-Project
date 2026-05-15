# Data-Science-Projects
This repository contains my completed data science internship tasks including data exploration, visualization, and machine learning classification models.
# Task 1: Exploratory Data Analysis(Iris Dataset)
## Objective
To understand the structure of the Iris dataset and explore relationships between features using visualizations.
## Approach
Loaded dataset using pandas
Checked shape, columns, and summary statistics
Performed data visualization:
Scatter plots
Histograms
Pairplot for feature relationships
and Boxplotsfor data distribution
## Results
Clear separation observed between species based on petal features
Setosa species was easily distinguishable from others
## Insights
Petal length and petal width are strong indicators for classification
Some features are highly correlated
# Task 2: Loan Default Prediction(Loan_default_prediction dataset)
## Objective
To predict whether a loan applicant will default based on financial and personal data.
## Approach
Data cleaning and handling missing values
Encoding categorical variables
Visualization
Feature scaling
Model training using classification algorithm(LogisticRegression)
## Results
The dataset was preprocessed by encoding categorical variables and applying feature scaling using StandardScaler. A Logistic Regression model was trained to predict loan default risk. Stratified sampling was used during the train-test split to maintain class distribution, which improved model performance.
The final model achieved an accuracy of 78.5%, indicating that the model correctly predicts the loan default status for the majority of cases. Evaluation using a confusion matrix and classification report showed that the model performs reasonably well in identifying both defaulters and non-defaulters.
## Insights
Income and loan amount and employment staus are strong predictors of loan default
# Task 3: Churn Prediction(Churn_modelling_dataset)
## Objective
To predict customer churn and identify key factors influencing customer retention.
## Approach
Data preprocessing and encoding
Train-test split
Model training (Random Forest)
Pipeline and hyperparameter tuning were performed to get better results
Evaluation using accuracy, confusion metrix ROC-AUC, classification report
## Results
The Random Forest model achieved an accuracy of 83.75% and a ROC-AUC score of 0.86, showing good overall performance in predicting customer exit behavior. The confusion matrix indicates that most customers were classified correctly, including 1405 non-exited and 270 exited customers. The classification report shows strong performance for non-exited customers and moderate performance for exited customers, with the model correctly identifying about 66% of customers who exited the bank.
## Insights
The key factors affecting customer exit behavior, such as age, balance, or account activity.
Class imbalance affected model performance usin SMOTE
# Task 4: Predicting Insurance Claim Amount
This project is part of a data science internship. The goal is to predict medical insurance charges based on personal attributes such as age, BMI, smoking status, and region using machine learning models.
## Objective
To build and evaluate regression models that accurately predict insurance costs and identify the best performing approach.
## Workflow
1. Exploratory Data Analysis (EDA)
Data visualization of age, BMI, and smoking impact on charges
Identified strong influence of smoking on insurance cost
2. Data Preprocessing
Encoding categorical variables
Outlier detection and removal
Model used:
Gradient Boosting Regressor
4. Model Improvement Techniques
Outlier removal
Log transformation of target variable
Hyperparameter tuning using GridSearchCV
## Model Comparison Results
Method
MAE
RMSE
Outlier Removal 
2158
4044
Log Transformation
1898
4175
GridSearchCV
2435
4180
## Best Model
The Gradient Boosting Regressor with Outlier Removal achieved the best overall performance with the lowest RMSE (4044), making it the most suitable model for this dataset.
## Key Insights
Smoking status has the highest impact on insurance charges
Outlier removal significantly improved model performance
Log transformation reduced average error but increased large error sensitivity
GridSearchCV did not provide significant improvement in this case
## Result
This project demonstrates a complete machine learning workflow including data preprocessing, model training, evaluation, and optimization. The best performing model was achieved after outlier removal.
# Task 5(Personal Loan Acceptance Prediction)
The project followed a complete machine learning pipeline:
Performed exploratory data analysis (EDA) to understand customer behavior
Visualized key features such as age, job, marital status, and balance
Applied data preprocessing including encoding categorical variables and feature scaling
Detected and removed outliers to improve model performance
Trained a Logistic Regression model for classification
Evaluated the model using accuracy score and confusion matrix
## Results
After removing outliers, model performance improved significantly, achieving an accuracy of 79.5% with better classification of both positive and negative cases.
## Key Insights
Contact duration was the most important feature in predicting loan acceptance
Timing of contact (month and day) also had strong influence
Financial and demographic factors such as balance and age had moderate impact
Data cleaning (especially outlier removal) improved model performance
## Conclusion
This project demonstrates a complete machine learning workflow from data exploration to model evaluation. It also highlights how preprocessing techniques like outlier removal can significantly improve classification performance and provide meaningful business insights for targeted marketing strategies.
## Tools Used
Python
Pandas, NumPy
Matplotlib, Seaborn
Scikit-learn
Jupyter Notebook
# Conclusion
This internship helped strengthen my understanding of data preprocessing, visualization, and machine learning model building for real-world datasets.
# Name
Shumaila Liaqat
