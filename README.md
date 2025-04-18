# 🏃‍♂️ Fitbit Fitness Tracker Data Analysis

This project explores and analyzes physical activity data collected from Fitbit fitness trackers, with a focus on gaining actionable health insights and imagining how such data can be applied in hospital and inpatient care settings.

## 📊 Project Overview

Using a dataset of daily Fitbit user activity, this notebook performs a structured analysis to uncover behavioral patterns and correlations between physical activity and calories burned. The project follows the SMART framework (Specific, Measurable, Achievable, Relevant, Time-bound) and includes data visualization, correlation analysis, and real-world healthcare applications.

## 📁 Dataset

- **Source**: Google x Coursera Fitbit Fitness Tracker Dataset
- **File Used**: `dailyActivity_merged.csv`
- **Columns**: `TotalSteps`, `TotalDistance`, `Calories`, `VeryActiveMinutes`, `SedentaryMinutes`, etc.

## 📌 Objectives

- Explore daily physical activity patterns
- Visualize the relationship between steps taken and calories burned
- Analyze correlations between activity metrics
- Extract insights to inform personal and clinical health strategies

## 🧠 Key Insights

- **Steps & Calories**: Users averaging more than 10,000 steps per day tend to burn significantly more calories.
- **Active Minutes**: There’s a strong positive correlation between very active minutes and calories burned.
- **Sedentary Behavior**: Sedentary minutes show an inverse relationship with calories burned.

## 📈 Visualizations

- **Scatter Plot**: Shows the relationship between `TotalSteps` and `Calories` burned.
- **Bar Charts**: Compares activity intensity levels among users.
- **Correlation Matrix**: Highlights the strongest relationships among variables (e.g., between active minutes and calories).

## 🏥 Real-World Healthcare Applications

This project explores how hospitals and inpatient facilities might use wearable fitness trackers:

- **Inpatient Monitoring**: Hospitals can track steps, active minutes, and sedentary behavior to assess mobility and recovery progress.
- **Fall Risk Assessment**: Monitoring sedentary trends may help predict declines in mobility or detect early signs of frailty.
- **Personalized Care**: Data-driven insights can be used by care teams to recommend personalized activity goals.
- **Rehabilitation Programs**: Fitness data can help monitor patient adherence to post-surgical rehab protocols.

## 📌 Conclusion

Through this project, we explored key activity trends and their correlations using Fitbit data. We demonstrated how wearables can support personalized coaching and offer real-time monitoring benefits in healthcare environments. Future analysis could expand into:

- **Heart rate and sleep pattern analysis**
- **Comparing weekday vs weekend behavior**
- **Integrating electronic health record (EHR) data with wearable metrics**

## 📂 File List

- `fitbit_analysis_hospital_usecase.ipynb`: Main Jupyter Notebook
- `dailyActivity_merged.csv`: Raw dataset used in the analysis

---

## 🚀 Author

Michael Lam  
📍 Application Analyst | Healthcare IT | Data Analytics  
https://github.com/Michaellam001

---

## 📄 MIT License

This project is for educational purposes. Dataset provided by Coursera and Google.

