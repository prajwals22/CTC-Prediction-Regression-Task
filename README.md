# CTC-Prediction-Regression-Task
### Machine Learning Project

Problem statement Create a machine learning model that will help the company in determining the salary of newly hired employees using the given data.

Objective:
Develop a machine learning model to predict the salary of newly hired employees based on various factors such as education, experience, previous salary, and job role. This will help TechWorks Consulting offer fair and competitive compensation.

Key Points:
Company Background: TechWorks Consulting specializes in IT talent acquisition and placement. The company handles large-scale hiring projects and aims to offer competitive salaries based on market trends and employee skills.

Data:
The dataset contains features such as College Tier, City (metro/non-metro), Role (Manager/Executive), Previous CTC, Job Change, Graduation Marks, Experience in Months, and CTC (salary).

Machine Learning Task:
The task involves building a regression model to predict employee salary using historical data. Features like college tier, job role, and city need to be converted into numerical values for the model.

Approach:
Data Preprocessing: Convert categorical data (College Tier, City, Role) into numerical variables (e.g., one-hot encoding or label encoding). Handle missing values and outliers to ensure data quality. Normalize/scale data to bring all features within the same range, preventing bias from one feature dominating the model.

Model Selection:
Explore multiple regression models such as Linear Regression, Lasso, Ridge, and Decision Trees. Evaluate model performance using metrics like Mean Squared Error (MSE), R-squared, and Adjusted R-squared.

Feature Selection:
Perform feature engineering to select the most important factors that impact salary predictions, such as education, job role, experience, and previous salary.

Model Evaluation:
Use statistical methods to evaluate the significance of model coefficients. Compare model performances based on accuracy and interpretability to choose the best one.

Model Improvement:
Fine-tune the best-performing model using techniques like cross-validation or hyperparameter tuning to enhance its accuracy. Monitor the model for potential overfitting by using regularization techniques such as Lasso and Ridge.

Outcome:
Deliver a well-documented Jupyter Notebook detailing the step-by-step approach, model training, evaluation, and the rationale behind the model selection. Provide insights on improving the model’s performance further, such as adding new features or trying more advanced models like XGBoost.
