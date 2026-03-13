# DEPI-Final-Project
Files for final project 

1️⃣ Project Title

Predictive Maintenance for Industrial Machines

2️⃣ Project Overview

This project aims to predict machine failures using machine learning
techniques based on sensor data collected from industrial machines.

Predictive maintenance helps companies reduce downtime,
improve operational efficiency, and lower maintenance costs.

The project includes data preprocessing, exploratory data analysis (EDA),
feature selection, and machine learning models to classify whether
a machine will fail or not.

يهدف هذا المشروع إلى التنبؤ بأعطال الماكينات باستخدام تقنيات
التعلم الآلي اعتمادًا على بيانات الحساسات الخاصة بالماكينات الصناعية.

يساعد التنبؤ بالأعطال في تقليل توقف الإنتاج وتحسين كفاءة العمليات
وتقليل تكاليف الصيانة.

3️⃣ Dataset Description
The dataset used in this project is the AI4I 2020 Predictive Maintenance Dataset.

It contains sensor readings from industrial machines under different
operating conditions and records whether the machine experienced a failure.

Total records: 10,000
Target variable: Machine Failure (0 = No Failure, 1 = Failure)

4️⃣ Features 
Main Features:

• Air Temperature
• Process Temperature
• Rotational Speed
• Torque
• Tool Wear
• Product Quality (L, M, H)

Target Variable:
• Machine Failure

الهدف إنك تتوقع Machine Failure 

5️⃣ Tools Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Jupyter Notebook

6️⃣ Data Cleaning
Data preprocessing steps:

• Removing unnecessary columns (ID columns)
• Encoding categorical variables (Product Quality)
• Checking for missing values
• Feature scaling
• Splitting data into training and testing sets

7️⃣ Exploratory Data Analysis (EDA)

EDA was performed to understand the relationships between
machine operating conditions and failure events.

Key analyses included:

• Distribution of machine failures
• Correlation between features
• Temperature vs Failure
• Torque vs Failure
• Rotational speed analysis

8️⃣ Machine Learning Models

The following machine learning models were used:

• Decision Tree Classifier
• Random Forest Classifier

9️⃣ Model Evaluation

Models were evaluated using:

• Accuracy
• Precision
• Recall
• Confusion Matrix

🔟 Key Insights

• Machine failures are rare compared to normal operations.
• Certain features like torque and process temperature
  are strong indicators of machine failure.
• Random Forest performed better than Decision Tree.

1️⃣ Conclusion
Machine learning can effectively predict machine failures
based on sensor data.

Predictive maintenance allows companies to detect problems
early and reduce unexpected downtime.
