# Introduction
This project aims to explore the factors that influence high school students' academic performance. 
By analyzing various demographic and behavioral attributes, I seek to identify patterns and correlations that can provide insights into improving student outcomes.

# Background
I’ve always been curious about the factors that influence academic performance.
As a lifelong student, I enjoy investigating these factors using my technical skills and the knowledge gained during my university studies. 
My interest in this area stems from my own experience in education, 
which has inspired me to better understand what contributes to success in the classroom.



# Dataset
The data used in this analysis comes from the  https://www.kaggle.com/datasets/rabieelkharoua/students-performance-dataset. 

The dataset contains 16 columns and 2,324 rows documenting students' academic performance, along with attributes such as ethnicity, age, study habits, extracurricular activities, and parental support.

The dataset description is sourced from the original material.

"This dataset contains comprehensive information on 2,392 high school students, detailing their demographics, study habits, parental involvement, extracurricular activities,
and academic performance. The target variable, GradeClass, classifies students' grades into distinct categories, providing a robust dataset for educational research, 
predictive modeling, and statistical analysis.

## Study Habits
•	StudyTimeWeekly: Weekly study time in hours, ranging from 0 to 20.

•	Absences: Number of absences during the school year, ranging from 0 to 30.

•	GPA: Grade Point Average on a scale from 2.0 to 4.0, influenced by study habits, parental involvement, and extracurricular activities.


## The questions I wanted to answer through my exploratory analysis
1.	How does students' performance vary across different ethnicities and age groups?
2.	Does the number of study hours per week have an impact on academic performance?
3.	How do absences during the school year affect students' academic performance?

## Tools I used
•	Excel: Pivot tables and pivot charts for data exploration.

•	Data Visualization: Pie charts, bar charts, combo charts, histograms, scatter plots, and KPIs.

•	Statistical Analysis: Simple linear regression for understanding relationships between variables.

# Key Findings


## Academic performance seems to vary across students' age and ethnicity

![image](https://github.com/user-attachments/assets/4f77ffbc-de27-466d-814d-814a78e2d067)

![image](https://github.com/user-attachments/assets/78d8d1a5-9d21-4ea5-94d1-24b48d05a6ec)



•	Students' performance appears to increase from ages 15 to 17 but drops at age 18.

•	Among ethnic groups, African Americans and the "Other" category show slightly higher average GPAs (1.95) than other groups. Caucasians have the lowest average GPA (1.88).



## More study hours per week can lead to higher average GPA.
![image](https://github.com/user-attachments/assets/9ec87e7b-f7f3-43be-b1c5-d37799f2b3ed)

•	There is a positive relationship between study hours and GPA. 

The more hours students spend studying each week, the higher their GPA tends to be.

•	Simple linear regression suggests that for every additional hour spent studying per week, a student's GPA could increase by approximately 0.64 points, assuming other factors remain constant.



## More class attendences can lead to higher average GPA.
![image](https://github.com/user-attachments/assets/2751d23f-63ca-4190-af04-55d565cfc08d)

•	The relationship between class absences and GPA is negative.

The more classes a student misses, the lower their GPA tends to be.

•	For every additional class missed, a student's GPA is expected to decrease by 0.12 points, assuming other factors remain constant.

# Conclusion
The analysis reveals several insights:

•	Ethnic Group Performance: Caucasians represent 50% of the student body, but their average GPA is lower compared to other ethnic groups.

•	Age Trends: As students grow older, they tend to perform better academically, with the exception of 18-year-olds.

•	Study and Attendance: Students who spend more time studying and regularly attend classes tend to achieve higher GPAs.

•	Grade Distribution: 50% of students received an "F" grade, while only 4.4% earned an "A."

# Future Steps
To build on this analysis, I plan to investigate additional factors such as:

•	The impact of extracurricular activities

•	The role of music and volunteering

•	Parental involvement and its effect on academic outcomes

This study provides a foundation for understanding the key factors that influence student success and can inform future strategies for improving academic achievement.
