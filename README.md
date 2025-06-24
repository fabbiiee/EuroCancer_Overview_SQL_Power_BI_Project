# EuroCancer Overview | SQL, Power BI Project.

## Overview
This project analyzes cancer patient data across multiple European countries between June 2014 to  May 2024, offering key insights into demographics, medical history, treatment patterns, and survival outcomes. The primary goal is to uncover patterns that can support healthcare providers, researchers, and policymakers in improving patient care and identifying high-risk groups.

## Data Source
The dataset of this project was sourced from X, formerly known as Twitter, exported in CSV format. It includes patient demographics, cancer diagnostic information, medical history & risk factors, treatment details, survival outcome all pertaining to cancer of some European countries spanning from June 2014 to May 2024. The key variables of the dataset include Patients ID, Age, Gender, Country, Diagnosis Date, Cancer Stage, Family History, Smoking Status, BMI, Cholesterol Level, Treatment Type, End Treatment Date, Survived, Treatment Duration (Days), Age Group, Age Category, Survival Status, Family History Status
Tools used: Firstly, I used SQL to extract, manipulate and analyze the data. I used SQL because of how large the dataset was. Then, I used Power BI for the visualization.

## Data cleaning
The dataset was very large, so SQL was the only tool that came to my mind for data cleaning when I went through the data to understand it, the first step I took was to create a duplicate of the dataset for error recovery, then removed the duplicates, standardized some of the data that needed to be standardized, changed the data type of the date column, removed rows with missing values, but I could also populate missing values all depending on what my client wants.

## Analysis techniques
Understanding the dataset and the goals of the project will always be the first thing to consider as a data analyst, so that was my first technique. Secondly, I used DAX in Power BI to create new columns and measures for effective analysis. Based on the goals of the project, I created two pages which are patient analysis and treatment analysis for analyzing patient data and treatment data respectively. Used a filter to segment patients by gender, identified the following; countries with most cancer cases, cancer stages percentages, BMI and cholesterol level of patients based on their age groups, survival rates based on smoking habits of patients, hereditary cancer history and cancer stages, most used treatment type and survival rate, treatment duration and survival rate, treatment adoption by cancer stages, trends of diagnosed patients over the years, number of survived patients yearly and top countries with the highest survival rate.

## Visualizations used
The following visualizations were used; Cards to display KPIs, Bar charts, Column charts, line charts, tables and lastly a slicer for easy interaction and dynamism.

## Key Insights
This analysis uncovers meaningful trends in cancer rates, survival and risk factors in Europe, turning raw data into actionable insights. Each finding reflects a deeper story behind the numbers, driving smarter decisions in healthcare. The insights are as follows;
-	Malta recorded the highest cancer cases, followed by Ireland, Portugal, France and Sweden. 
-	Out of the 4 stages of cancer, patients suffered mostly from stage III.
-	Cancer was suffered mostly by adults (Aged 25-64).
-	Most patients were passive smokers but patients who never smoked had the highest survival rate.
-	Patients with hereditary cancer history survived more than patients with no hereditary cancer history.
-	Chemotherapy was the most adopted treatment method but surgery had the highest survival rate.
-	The youths (Aged 15-24 years) spent the most days receiving treatment but Children (Aged 0-12 years) had the highest survival rate.
-	Most patients suffered from stage III cancer and chemotherapy was mainly used to treat all stages of cancer except stage I which was mainly treated by surgery.
-	2019 had the most cancer cases but 2014 had the most survived patients. Sadly, 2024 had the most deaths from cancer.
-	Lastly, Estonia led in survival rate across all countries analyzed.

## Challenges and learnings 
I faced some challenges while working on this project and the problems were as follows; incomplete or missing values which was figured out and had the rows deleted during data cleaning, inconsistent formats for dates, the Boolean values were represented as 0/1 instead of yes/no which made it harder to read in visuals but the use of DAX to create new columns helped me to bypass this, had to deal with complex DAX functions, there were too many insights to show on the dashboard hence the need to have two pages.
All these challenges made me a better analyst because I took my time to figure out how to overcome the challenges. The things I learnt are as follows; gained more experience writing calculated measures, learnt to choose the right visuals and also learnt how to analyze large datasets in a better way.


## Conclusion 
This project provided valuable insights into patient survival trends, risk factors, and the impact of hereditary and lifestyle conditions. Through data cleaning with SQL, DAX modeling, and interactive dashboard design in Power BI, I was able to transform raw healthcare data into meaningful visual insights. On the other hand, this project highlighted the importance of data-driven decision making in healthcare.

