![ontum_dataset_Analysis](ontum_logo.png)

📝 Project Overview

This project analyzes user activity data from the ontum platform. The dataset contains session records, academic context (curriculum/lesson/semester), device and location details, and some user metadata. The goal is to clean the data, impute missing values sensibly, and produce analyses/visualizations that describe platform usage (state-wise, curriculum-wise, language distribution, device/platform trends, etc.).

🚀 Technologies Used • Python 🐍 • Pandas – for data cleaning & manipulation • Matplotlib & Seaborn – for data visualization • Jupyter Notebook – development environment

📂 Dataset (summary)

Total rows: 666,748

Column	Non-null count	% non-null	Dtype
user_pseudo_id	666,748	100.00%	float64
sync_date	666,748	100.00%	object
date	666,748	100.00%	object
hour	666,748	100.00%	int64
day_of_week	666,748	100.00%	int64
session	0	0.00%	float64
id	657,433	98.60%	object
curriculum	665,516	99.82%	object
context	666,748	100.00%	object
grade	659,637	98.93%	float64
lesson_name	666,748	100.00%	object
page_num	666,748	100.00%	int64
slide_type	666,748	100.00%	object
type	666,748	100.00%	object
semester	660,699	99.09%	float64
lang	666,495	99.96%	object
subject	661,305	99.24%	object
duration	666,748	100.00%	int64
gender	666,281	99.93%	object
user_type	657,153	98.56%	object
dise	317,006	47.55%	float64
app_version	560,798	84.11%	object
flutter_app_version	0	0.00%	float64
app_mode	0	0.00%	float64
custom_curriculum	0	0.00%	float64
hostname	665,911	99.87%	object
host	666,748	100.00%	object
city	657,690	98.64%	object
state	666,208	99.92%	object
country	666,588	99.98%	object
category	666,748	100.00%	object
mobile_brand_name	664,316	99.64%	object
operating_system	665,911	99.87%	object


