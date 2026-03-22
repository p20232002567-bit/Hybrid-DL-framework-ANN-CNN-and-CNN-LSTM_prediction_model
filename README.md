🎓 Student Performance & Risk Prediction System

📌 Overview

This project focuses on analyzing student academic data to predict performance and identify at-risk students using data-driven techniques. By integrating multiple datasets (student info, activity, and assessment), the system enables early intervention strategies for improving academic outcomes.
________________________________________
📂 Dataset Description

The project uses three primary datasets:

1. StudentInfo-anonymized.csv

Contains demographic and background information:

•	reg_no

•	gender

•	email

•	No_prev_attempts

•	disability

2. StudentActivity-anonymized.csv

Tracks student engagement:

•	reg_no

•	reg_date

•	attendanceRate

•	studyHours

3. StudentAssessment-anonymized.csv 

Includes academic performance:

•	reg_no

•	semester

•	course1_marks → course5_marks

•	currentCGPA

•	previousCGPA

•	totalcredithours

•	high_edu

•	next_semester_CGPA

•	next_semester_grade

•	recommendation
________________________________________
🔗 Data Preprocessing & Merging

The datasets are merged using the common key: reg_no

Key Steps:

1.	Clean column names

2.	Aggregate activity data (mean attendance & study hours)

3.	Merge datasets

4.	Remove duplicates

5.	Final dataset shape: (1670, 21)
________________________________________
⚙️ Installation

pip install pandas numpy matplotlib seaborn scikit-learn
________________________________________
🎯 Objectives

•	Identify at-risk students (Dropout / High Risk)

•	Analyze impact of:

o	Attendance

o	Semester

o	Credit hours

o	Course marks

o	Study hours

o	Current performance

o	Previous performance

•	Support early academic intervention systems
________________________________________
🧠 Machine Learning Scope

•	Classification:

o	Dropout prediction

o	Risk categorization

•	Techniques:

o	LSTM

o	CNN

o	DeepLSTM

o	BiLSTM

o	ASSIST

o	Deep Learning (CNN + LSTM)

o	Deep Learning (ANN + CNN)

•	Evaluation Metrics:

o	Accuracy

o	Precision, Recall, F1-score, Confusion matrix

o	AUC-ROC
________________________________________
📈 Results

•	Balanced dataset used for fair evaluation

•	Improved prediction using combined behavioral + academic features

•	Visual insights show strong correlation between:

o	Study hours and CGPA

o	Attendance and risk level
________________________________________
👨‍💻 Author

Rizwan et. al

Research Focus: AI in Education, Student Performance Prediction, Learning Analytics
________________________________________
📜 License
This project is for academic and research purposes.

