🌙 Sleep Health & Lifestyle Analysis (EDA)
📌 Project Overview
In today’s fast-paced environment, poor sleep quality and sleep disorders are becoming increasingly common, impacting productivity, mental well-being, and overall health.

This project performs an Exploratory Data Analysis (EDA) on the Sleep Health and Lifestyle Dataset to uncover key insights into how daily habits, work environments, and physiological metrics correlate with sleep quality and the prevalence of sleep disorders.

🎯 Key Objectives
Occupational Impact: Analyze how different professions affect stress levels and average sleep duration.

Lifestyle Factors: Examine the relationship between daily physical activity (daily steps, physical activity level) and sleep quality.

Health Risk Factors: Evaluate how physiological indicators (BMI category, Blood Pressure, Heart Rate) correlate with sleep disorders such as Sleep Apnea and Insomnia.

Demographic Analysis: Discover patterns in sleep behavior across different genders and age groups.

Feature,Description
Person ID,Unique identifier for each individual
Gender,Male / Female
Age,Age in years
Occupation,Professional field/job title
Sleep Duration,Average hours of sleep per day
Quality of Sleep,Subjective rating (scale: 1–10)
Physical Activity Level,Daily active minutes
Stress Level,Subjective rating (scale: 1–10)
BMI Category,"Weight classification (Underweight, Normal, Overweight, Obese)"
Blood Pressure,Systolic/Diastolic reading (mmHg)
Heart Rate,Resting heart rate (BPM)
Daily Steps,Average step count per day
Sleep Disorder,"Condition presence (None, Insomnia, Sleep Apnea)"

🛠️ Tech Stack & Libraries Used
Language: Python

Data Manipulation: pandas, numpy

Data Visualization: matplotlib, seaborn

Statistical Analysis: scipy / statistics

Environment: Jupyter Notebook / JupyterLab

🔍 Analytical Workflow
Data Cleaning & Preprocessing:

Handled missing values (e.g., standardizing missing values in Sleep Disorder to 'None').

Parsed combined values like Blood Pressure into numerical Systolic and Diastolic components.

Cleaned string categories in BMI Category (e.g., merging 'Normal' and 'Normal Weight').

Univariate Analysis:

Distribution of numerical metrics (sleep duration, heart rate, daily steps) using histograms and density plots.

Frequency counts of categorical metrics (occupations, sleep disorders, BMI).

Bivariate & Multivariate Analysis:

Correlation heatmaps to map linear dependencies across variables.

Box plots and scatter plots comparing sleep quality against physical activity levels and stress ratings across occupations.

Key Insights & Findings:

Summarized actionable findings regarding high-stress occupations, optimal step counts, and high-risk indicators for sleep disorders.

📁 Repository Structure
Plaintext
├── data/
│   └── Sleep_health_and_lifestyle_dataset.csv
├── notebooks/
│   └── Sleep_health_and_lifestyle_EDA.ipynb
├── README.md
└── requirements.txt

