# CapstoneProject_EDA_InfosysSpringBoard_Internship

##Adult Census Income Analysis & Earning Potential Prediction

**Project Overview**

This project focuses on exploratory data analysis (EDA), data preprocessing, visualization, and machine learning modeling using the Adult Census Income Dataset.
The objective is to analyze demographic and work-related attributes and predict the earning potential (whether income exceeds a certain threshold)of a person.

**Objectives**

•	Understand the structure and distribution of the Adult Census dataset
•	Perform data cleaning and preprocessing
•	Analyze relationships between features and target(earning potential)
•	Handle missing values and outliers
•	Convert categorical features into numerical format
•	Train and evaluate machine learning models
•	Draw meaningful insights from the data

**Dataset Description**

Dataset Name: Adult Census Income Dataset
Source: Infosys Spring Board(Exploratory Data Analysis Capstone Project)
Type: Structured tabular data

Features Used:
age, workclass, fnlwgt, education, education-num, marital-status, occupation, relationship, race, sex, capital-gain, capital-loss, hours-per-week, native-country

Target Variable:
earning_potential (<=50K → Lower income group , >50K → Higher income group)

**Technologies & Libraries**

Programming Language: Python

Libraries Used:
NumPy
Pandas
Matplotlib
Seaborn
Scikit-learn

Environment: Jupyter Notebook

**Data Preprocessing**

Loaded dataset using Pandas

Checked data types and dataset structure

Identified missing values (?) and replaced them with NaN

Handled missing values using statistical methods

Converted categorical variables into numerical values

Feature scaling for numeric columns

Outlier detection using boxplots

Train-test data splitting

**Exploratory Data Analysis (EDA)**

•	Distribution of age, working hours, and education

•	Income distribution across gender, education, and occupation

•	Boxplots to identify outliers

•	Correlation analysis between numerical features

•	Visualization of earning potential vs working hours

**Machine Learning Model**

Random Forest 

Models were trained using processed data and evaluated using standard classification metrics.

Model Evaluation Metrics:
Accuracy
Precision
Recall
F1-score

**Key Insights**

•	Earning potential rises sharply with higher education levels. Individuals with more education year earn significantly more, showing that education strongly influences income. Lower education levels corresponds to low wages.
•	Earning potential increases steadily from age 20 to 40, peaks around 40 to 50 and slightly declines after 50. Younger individuals earn less due to lesser experience.
•	High earners typically work more hours, while low earners show more variability and many outliers working long hours without higher pay. This suggests that income depends not only on work hours but also on job type, education,and skill level.
