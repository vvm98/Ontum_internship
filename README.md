![ontum_dataset_Analysis](ontum_logo.png)

## 📝 Project Overview

This project analyzes user activity data from the ontum platform. The dataset contains session records, academic context (curriculum/lesson/semester), device and location details, and some user metadata. The goal is to clean the data, impute missing values sensibly, and produce analyses/visualizations that describe platform usage (state-wise, curriculum-wise, language distribution, device/platform trends, etc.).

🚀 Technologies Used • Python 🐍 • Pandas – for data cleaning & manipulation • Matplotlib & Seaborn – for data visualization • Jupyter Notebook – development environment

## 📂 Dataset (summary)

Total rows: 666,748

User Information: user_pseudo_id, id, gender
Session Data: session, sync_date, date, hour, day_of_week
Academic Context: curriculum, grade, lesson_name, semester
System Info: app_mode, custom_curriculum, hostname, host
Location: city, state, country
Device Info: category, mobile_brand_name, operating_system


## 📊 Analysis & Visualizations
•	Null Value Imputation
o	Identified and imputed missing values in curriculum, semester, lang, gender, and city.
o	Applied techniques like constant imputation, conditional replacement, and analysis-based filling.
•	State-wise User Distribution
o	Top states contributing to user activity: Karnataka, West Bengal, Delhi, Maharashtra, and Goa.
o	Remaining states grouped under “Others”.
•	Curriculum Usage
o	Explored relationships between lesson_name and curriculum.
o	Used conditional logic to impute missing curriculum values.
•	Language Distribution
o	Countplots and crosstabs between state and lang show regional language adoption.
•	Device & Platform Trends
o	Breakdown of users across mobile vs desktop.
o	Operating system and mobile brand analysis for understanding tech adoption.


## 📈 Key Insights
✅ Karnataka has the highest user base, dominating platform usage.
✅ Strong association found between lesson_name and semester, helping imputation.
✅ Most missing values could be imputed logically instead of dropping rows → ensured minimal data loss.
✅ Majority of users access via mobile devices, highlighting the importance of mobile optimization.
✅ English is the dominant language, but regional languages appear in specific states.


## 💡 Conclusion
This analysis provides actionable insights into:
•	Improving curriculum tagging accuracy.
•	Optimizing the platform for mobile-first usage.
•	Supporting regional languages alongside English.
•	Leveraging state-wise adoption patterns for targeted interventions.


## 📷 Sample Visualizations
•	📊 Pie Chart: Top 5 States + Others by User Percentage
•	🌍 Countplot: State vs Language Distribution
•	📚 Curriculum vs Lesson Name Mapping
•	📱 Device Category & Mobile Brand Distribution
•	📆 User Activity by Day of Week & Hour



