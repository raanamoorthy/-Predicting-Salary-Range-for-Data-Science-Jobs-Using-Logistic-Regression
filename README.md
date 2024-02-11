 Predicting Salary Range for Data Science Jobs Using Logistic Regression

Introduction:
In this project, I conducted an analysis to predict whether a data science job's salary falls within a specific range using logistic regression. The dataset used contains information on various factors such as work year, experience level, employment type, remote work ratio, company size, company location, employee residence, and job title.

Data Overview:

The dataset comprises 607 entries with 10 features.
Features include work year, experience level, employment type, salary in USD, remote work ratio, company size, company location, employee residence, job title, and salary range.
Data Preprocessing:

I performed data cleaning, handling missing values, and removing duplicates.
Outliers were detected and treated using the Interquartile Range (IQR) method to maintain data integrity.
Categorical variables were encoded for modeling purposes.
Exploratory Data Analysis (EDA):

Conducted EDA to understand the distribution and relationships between variables.
Utilized visualizations such as bar plots to visualize categorical variables like work year, experience level, employment type, and company size.
Modeling:

Split the data into training and testing sets with a ratio of 70:30.
Implemented logistic regression as the predictive model due to its effectiveness in binary classification tasks.
Evaluated the model using classification metrics like precision, recall, F1-score, and confusion matrix.

Results:

The logistic regression model achieved high accuracy, precision, recall, and F1-score on the test dataset, indicating robust performance.
Precision, recall, and F1-score were all perfect (1.00) for both salary ranges, indicating no misclassifications.
Conclusion:

The project successfully demonstrated the application of logistic regression in predicting salary range for data science jobs based on various factors.
The model can assist job seekers or recruiters in estimating salary ranges for different data science positions, aiding in decision-making processes.
