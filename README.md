Port-Level Import Analytics and Trade Intelligence in India
📌 Project Overview
This project analyzes India's import trade data for 2023–2024 to understand import patterns, major trading partners, commodity performance, port activity, and state-wise trade contributions

🎯 Project Objective
Analyze port-wise import performance across India.
Identify top imported commodities based on quantity and import value.
Discover major countries exporting goods to India.
Evaluate state-wise import contribution and trade activity.
Analyze monthly import trends during 2023–2024.

📊 Dataset Overview
Dataset: India Import Trade Dataset (2023–2024)
Number of Records: Import trade transactions across India
Number of Variables: Import-related trade attributes

Key Variables
Country
State
Port
Commodity Description
Quantity
Unit of Measurement
USD Value
Import Value (INR)
Month
Year
Quantity Reported Status
Commodity Category
Trade Value Metrics
🛠️ Tools & Technologies
Python
Pandas
NumPy
Matplotlib
Seaborn
Plotly
Power BI
Google Colab
GitHub
📂 Repository Structure
Interstitial-Lung-Disease-Clinical-Analysis-Python
│
├── Raw_Data
│   └── ILD_Data_2022.xlsx
│
├── Cleaned_Data
│   └── Cleaned_ILD_Data.csv
│
├── PowerBI
│   └── ILD_Dashboard.pbix
│
├── Screenshots
│   ├── Patient_Characteristics_&_Diagnosis_Overview.png
│   ├── Demographic_&_Risk_Factor_Analysis.png
│   └── Clinical_Findings_&_Lung_Function_ Analysis.png
│
├── Clinical_Analysis_of_ILD_Disease.ipynb
├── Clinical Analysis of Interstitial Lung Disease.pptx
└── README.md
🧹 Data Preprocessing
Removed unnecessary columns.
Handled missing values using mean and median imputation.
Created derived columns:
Age Category
BMI Category
Performed exploratory data analysis and correlation analysis.
📈 Dashboards Developed
1. Overview Dashboard
Total Patients
Average Age
Average BMI
Diagnostic Category Distribution
Spirometric Pattern Distribution
Smoking Status Distribution
Gender Distribution
2. Demographic & Risk Factor Analysis Dashboard
Age Category vs Spirometric Pattern
Gender vs Spirometric Pattern
Smoking Status vs Spirometric Pattern
BMI Category vs Spirometric Pattern
3. Clinical & Pulmonary Analysis Dashboard
FVC Distribution Across Diagnostic Categories
FEV1 Distribution Across Diagnostic Categories
Sarcoidosis Stage Distribution
Sarcoidosis Stage vs FVC (%)
Clinical Correlation Matrix
FVC vs FEV1 Analysis
🔍 Key Findings
Sarcoidosis is the most prevalent diagnostic category.
Restrictive spirometric pattern is the dominant respiratory pattern.
Most patients belong to middle-aged and senior age groups.
The majority of patients are non-smokers.
FVC and FEV1 show a strong positive correlation.
Advanced Sarcoidosis stages are associated with reduced FVC and worsening pulmonary function.
Smoking contributes to obstructive impairment but is not the primary determinant of ILD occurrence.
💡 Recommendations & Future Enhancements
Future versions of the project can include:

High-Resolution CT (HRCT) findings
DLCO measurements
Oxygen Saturation (SpO₂)
Six-Minute Walk Test (6MWT)
Autoimmune biomarker data
Environmental and occupational exposure history
Longitudinal follow-up data for predictive modelling
🎯 Project Outcome
The dashboard transforms complex clinical and pulmonary data into actionable insights that help:

Assess patient risk factors
Classify disease subtypes
Monitor pulmonary function decline
Identify disease progression patterns
Support data-driven clinical decision-making
