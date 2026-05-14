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
Boxplot
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
