EMPLOYEE ATTRIRION PREDICTION USING LOGISTIC REGREESION 
 This projects puilds a logistic regreesion model to predict wether an employee is likely to leave the coumpsny , 
 the goal is to help the HR department identify high_risk employees and take proactive actions to improve retention
 -- Exploratory Data Analysis:- (EDA)

In the EDA phase : several analyses and visualizations were performed to understand the data:

Attrition Distribution: Showed that most employees stayed, and a smaller portion left.

Department Analysis: Compared attrition rates across departments like Sales

Age and Income Trends: Revealed that younger and lower-income employees are more likely to leave.

Correlation Heatmap: Identified relationships between numeric features and attrition.

EDA helped highlight patterns and potential risk factors contributing to employee turnover.

 Feature Engineering:-

To prepare the dataset for modeling:

Converted the target column (“Attrition”) to numeric (Yes → 1, No → 0).

Encoded categorical variables using "one-hot encoding" so they can be used by the model

Scaled numerical features with "StandardScaler" to improve model stability and performance

These steps ensured that the data is in the right format for machine learning.

** Model Building:-**

A Logistic Regression model was trained after splitting the data into training and testing sets (80% - 20%).
The model learned which patterns and features indicate whether an employee is at high risk of leaving.

** Model Evaluation:-**

The model was evaluated using accuracy and classification metrics and confusion_matrix

Final Accuracy: Around 85%
This means the model can correctly predict most cases and performs well for a baseline classification model.

   Key Features Affecting Attrition :-

Based on the analysis and model behavior, the most influential factors contributing to employee attrition were:

--OverTime: Employees working overtime leave more often.

--MonthlyIncome: Lower-income employees have higher attrition.

--JobSatisfaction: Lower satisfaction increases attrition.

--YearsAtCompany: Employees with fewer years at the company tend to leave more.

--Age: Younger employees are more likely to leave.

These insights help HR teams identify at-risk employees and take preventive actions.

to run the model locally
-clone the repositpry 
-install the required libraries
-download the attrition employee file
-read the path or the file name using pandas
-run the file LOG_REG 

DATASET SOURCE 
the employee attrition " dataset was taken from kaggle
