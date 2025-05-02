🧠 IBM HR Analytics: Employee Attrition & Performance
This project explores factors contributing to employee attrition using the IBM HR Analytics dataset. Through data cleaning, exploratory analysis, feature engineering, and machine learning, I aim to build predictive models and provide actionable HR insights.

📊 Objectives
Identify key drivers of employee attrition.

Explore the relationship between job roles, satisfaction levels, compensation, and turnover.

Build machine learning models to predict which employees are at risk of leaving.

🛠️ Tools & Technologies
Languages & Libraries: Python, pandas, numpy, matplotlib, seaborn, scikit-learn

Modeling: Logistic Regression, Decision Tree, Random Forest, XGB, etc.

Encoding/Preprocessing: One-Hot Encoding, Standard Scaler

Sampling : SMOTE

Environment: Visual Studio Code

🧪 Key Steps
1. Data Cleaning
Checked for null or duplicate values.

Removed or imputed missing entries.

Converted appropriate columns to categorical or numerical formats.

2. Exploratory Data Analysis (EDA)
Visualized attrition by age, gender, department, job role, income, etc.

Used bar plots, histograms, and heatmaps to spot trends and correlations.

3. Feature Engineering
Transformed categorical variables using one-hot encoding.

Created new features such as years in current role, satisfaction ratios, etc.

4. Modeling
Split dataset into training and test sets.

Trained and compared multiple classification models.

Evaluated using accuracy, precision, recall, F1-score, and ROC-AUC.

5. Key Insights
Employees with low satisfaction and fewer years in current role were more likely to leave.

Overtime and lower income correlated strongly with attrition.

📁 Files
ibm_hr_attrition.ipynb – Main notebook with analysis and modeling.
WA_Fn-UseC_-HR-Employee-Attrition.csv – The dataset from IBM.

📌 Outcome
Achieved 93.5% accuracy on the test set using XGBClassifier with GridSearchCV. These insights can guide HR departments in taking proactive steps to reduce attrition.

🔗 References
IBM HR Analytics Dataset on Kaggle

This project demonstrates the real-world application of data science to human resource challenges.
