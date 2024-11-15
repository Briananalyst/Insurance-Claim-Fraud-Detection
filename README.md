Overview

Fraudulent claims in auto insurance lead to significant financial losses and inefficiencies. This project leverages machine learning techniques to automate the detection of potentially fraudulent claims.

Key features of the project include:

Handling missing values and cleaning the data.
Visualizing data patterns to understand relationships and outliers.
Building predictive models to classify insurance claims as fraudulent or non-fraudulent.

Dataset
The dataset used in this project was sourced from Kaggle, containing key attributes such as:

Policy information (e.g., policy_number, policy_state, policy_deductable)
Customer details (e.g., age, insured_sex, insured_occupation)
Incident specifics (e.g., incident_date, incident_type, incident_severity)
Claim amounts (e.g., injury_claim, property_claim, total_claim_amount)
Target label: fraud_reported (indicating whether a claim is fraudulent).

Technologies Used

Programming Language: Python
Libraries and Frameworks:
pandas for data manipulation
numpy for numerical operations
matplotlib and seaborn for visualization
scikit-learn for machine learning
imbalanced-learn for handling class imbalance

Project Workflow
Data Collection:

The dataset was downloaded from Kaggle and loaded into a pandas DataFrame.
Data Preprocessing:

Missing values were handled using appropriate strategies (e.g., replacing placeholders like ? with NaN and imputing them).
Dates (e.g., policy_bind_date and incident_date) were converted to datetime format, and new features like the number of days between dates were created.
Categorical variables were encoded using techniques like one-hot encoding.
Exploratory Data Analysis (EDA):

Box plots were used to identify outliers.
Correlation analysis and visualizations helped uncover relationships between features and the target variable.
Model Building:

Models like Logistic Regression, Decision Trees, and Gradient Boosting were trained and evaluated.
Class imbalance was addressed using standardscaler.
Feature importance was analyzed to identify key predictors of fraud.
Evaluation:

Metrics like Accuracy, Precision, Recall were used to evaluate model performance.
Model Evaluation
The final model demonstrated strong predictive performance, balancing precision and recall to handle fraud detection effectively.
Key insights from feature importance analysis were documented.
