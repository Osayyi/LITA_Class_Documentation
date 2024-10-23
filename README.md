# LITA_Class_Documentation
This is where I documented my first project while learning Data Analysis with The Incubator Hub

### Project Title: Student Performance Factors
[Project Overview](#project-overview)

[Dataset](#dataset)

[Data Sources](#data-sources)

[Tools Used](#tools-used)

[Data Cleaning and Preparations](#data-cleaning-and-preparations)

[Exploratory Data Analysis](#exploratory-data-analysis)

[Data Analysis](#data-analysis)

[Data Visualization](#data-visualization)

 
### Project Overview:
---
*Objective*:
The goal of this project is to analyze various factors influencing student performance (measured by exam scores). By cleaning, transforming, and visualizing the data, we aim to uncover patterns and insights into the key drivers of student success.

### Dataset:
The dataset includes the following features related to student performance:

 - *Hours_Studied*: Time dedicated to studying.
 - *Attendance*: Percentage of classes attended.
 - *Parental_Involvement*: Level of parental engagement in education.
 - *Access_to_Resources*: Availability of educational resources.
 - *Extracurricular_Activities*: Involvement in activities beyond academics.
 - *Sleep_Hours*: Number of hours of sleep.
 - *Previous_Scores*: Past academic performance.
 - *Motivation_Level*: Level of motivation (self-reported or observed).
 - *Internet_Access*: Availability of internet at home.
 - *Tutoring_Sessions*: Number of tutoring sessions attended.
 - *Family_Income*: Socio-economic background.
 - *Teacher_Quality*: Perceived quality of teachers.
- *School_Type*: Type of school (public/private).
 - *Peer_Influence*: Influence of peers on academic behavior.
 - *Physical_Activity*: Hours spent in physical activity per week.
 - *Learning_Disabilities*: Presence of any learning disabilities.
 - *Parental_Education_Level*: Highest education level of parents.
 - *Distance_from_Home*: Distance between home and school.
 - *Gender*: Student's gender.
 - *Exam_Score*: Final exam score.
 
### Data Sources
---
The primary source of Data used here is StudentPerformanceFactors.csv and this is an open source data that can be freely downloaded from an open source online such as kaggle or any other data repository site.

### Tools Used
---
- Microsoft Excel [Download Here](https://www.microsoft.com)
   1. For Data Cleaning
   2. Analysis
   3. For Data visualization
      
- SQL - Structured Query Language
   1. for Quring of Data

- Github
    1. for Portfolio Building
  
- PowerBi [Download Here](https://www.PowerBi.com)
    1. for Data Visualization

  ### Data Cleaning and Preparations
  ---
  *Key Steps in the Project*:
 1.  Data loading and Inspection

 2.  Handling missing variables in columns like "Teacher_Quality," "Parental_Education_Level," and "Distance_from_Home."

 3.  Data cleaning and formatting

 4.  Data Analysis:
     - Analyzing the impact of family background (income, parental education) on performance.
     - Investigating relationships between various factors like "Hours_Studied" and "Exam Scores."
 5. Data Visualization:
 - Creating bar charts, histograms, or scatter plots to illustrate key relationships.
   *Example visualizations*:
 - Bar chart showing the average exam score by hours studied.
 - A comparison of exam scores based on teacher quality or parental involvement.

  ### Exploratory Data Analysis
  ---
EDA involves exploring of data to answer questions about data. To perform exploratory data analysis (EDA) on the dataset, I will; examine the data structure, check for missing values,and visualize key variables to understand their distributions and relationships. This will help identify patterns, trends, and potential issues in the data. Let's proceed with the EDA steps.
- what variables impact the performance of students the most
- what changes can be made to improve their performance
  
### Data Analysis
---
This is where we include some basic lines of code or queries or even some of the DAX expressions used during your analysis;

```SQL
SELECT * FROM TABLE Students
WHERE CONDITION = TRUE
```

### Data Visualization

1. Bar Chart (Average Exam Score by Hours Studied):
This visualization can show how studying more (or less) impacts the average exam score.

2. Scatter Plot (Sleep Hours vs. Exam Score):
This will help illustrate if there's a relationship between sleep and performance.

3. Pivot Table (Exam Score by School Type and Teacher Quality):
A pivot table can summarize how different school types and teacher quality influence student performance.

![Screenshot (6)](https://github.com/user-attachments/assets/9ff269cc-37c6-47c5-9352-8ff109b4fde2)

![Screenshot (5)](https://github.com/user-attachments/assets/1bd70fc1-5b9b-474a-bd7f-09846ca9c135)

![__results___11_0](https://github.com/user-attachments/assets/9a546dce-f8be-4bb5-bfe6-758cd08cc2e5)

![__results___11_1](https://github.com/user-attachments/assets/ff98d4d7-9993-4d2c-b6a1-d39c0e8e3872)

![__results___11_2](https://github.com/user-attachments/assets/d68e30e4-de49-460f-a273-7a636ab42b30)

😄

🥇

|Heading 1|Heading 2|Heading 3|
|---------|---------|---------|
|Table 1|Table 2|Table 3|
