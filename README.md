**Titanic Dataset - Exploratory Data Analysis (EDA)**
**📊 A detailed exploratory data analysis on the Titanic dataset to uncover patterns, insights, and survival factors.**


**Project Overview
The Titanic Dataset is one of the most famous datasets in machine learning. This project performs Exploratory Data Analysis (EDA) to:
✔️ Understand the dataset structure 📂
✔️ Handle missing values 🔍
✔️ Perform data visualization 📊
✔️ Identify survival trends 🚢**

Dataset Information
The dataset contains passenger details from the Titanic disaster, with features like:

Feature	Description
PassengerId	Unique ID of the passenger
Survived	0 = No, 1 = Yes
Pclass	Ticket class (1st, 2nd, 3rd)
Name	Passenger name
Sex	Gender (male/female)
Age	Age of the passenger
SibSp	No. of siblings/spouses aboard
Parch	No. of parents/children aboard
Ticket	Ticket number
Fare	Ticket price
Cabin	Cabin number
Embarked	Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

Tech Stack
🔹 Python
🔹 NumPy - Data manipulation
🔹 Pandas - Data cleaning & analysis
🔹 Matplotlib & Seaborn - Data visualization

📊 Exploratory Data Analysis Steps
1️⃣ Data Cleaning & Handling Missing Values
✔️ Identified missing values in Age, Cabin, Embarked
✔️ Used mean/median imputation for Age
✔️ Filled Embarked using the most frequent value
✔️ Dropped Cabin due to too many missing values

2️⃣ Data Visualization
📌 Survival Rate by Gender
📊 Females had a higher survival rate than males.

📌 Survival Rate by Passenger Class
📊 1st class passengers had a better chance of survival.

📌 Survival Rate by Age
📊 Children (Age < 10) had a higher survival rate.

📌 Effect of Fare on Survival
📊 Higher fares increased the chance of survival.

3️⃣ Insights & Key Findings
✔️ Women & children were prioritized for rescue.
✔️ 1st class passengers had better survival rates due to better cabin locations & priority.
✔️ Higher fares correlated with higher survival probability.
______________________________________________________________________________________________________________________________________________________________________________




