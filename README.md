
# Hazard-Incident-Analysis
This is an analysis of Hazards in the construction sector (Building) to help know the hazards they are faced with and how to reduce its occurrence to create a safe working enironments for workers.

# Introduction
The dataset was gotten from Kaggle it contained 4847 rows and 28 columns, with categorical and numeric columns.
Steps for Analysis
1.	Data Cleaning:
o	Check for missing or inconsistent values.
o	Standardize date and categorical data formats.
2.	Exploratory Data Analysis (EDA):
o	Visualize trends (e.g., line plots for time, bar charts for categories).
o	Calculate frequencies and proportions.
3.	Advanced Analysis:
o	Perform text analysis on "Abstract Text" or "Event Keywords" for trends.
o	Correlate factors using statistical or machine learning techniques.
4.	Visualization:
o	Use tools like Matplotlib, Seaborn.


![image](https://github.com/user-attachments/assets/a6745f78-f09a-4a20-b74a-4c26eab25adb)


# Data Exploration
# Tools used fo Analysis : 
Due to the high volume of the data i used Python for analysis and some machine learning models.
•	Purpose: Apply machine learning to predict potential high-risk conditions and automate data analysis.

# 1. Load the dataset using libraries like pandas
![image](https://github.com/user-attachments/assets/7ab56ed2-320a-49a6-8c5f-ccf8a0108ec3)

I imported my Libraries for the analysis so as to explore and understand my dataset.

![image](https://github.com/user-attachments/assets/1052eadc-5d18-4a39-916e-996df3645aec)

# 2.	Perform exploratory data analysis (EDA): 
 I Checked for missing or inconsistent data and also transformed the necessary data 
 ![image](https://github.com/user-attachments/assets/3452ac77-6006-44e7-a1ab-1bbf94294bf2)
 ![image](https://github.com/user-attachments/assets/aad41f1f-48d2-45ae-9349-857f2c74f31f)

 # Analyzed distributions of incident types, severity, and root causes like Environmental and human factors.
 I described my data to derive insights and determine outliers and relationships
 ![image](https://github.com/user-attachments/assets/36a657e1-8821-49f0-8f3f-3e2994bd43ec)
 ![image](https://github.com/user-attachments/assets/008fe8f1-1fbc-4a39-aef9-8f8d4ac117b0)
# Transformed the Event_Date column to Date time so i can Extract the days, month, Year
![image](https://github.com/user-attachments/assets/1543a08a-9b3a-42cc-bd9a-fedda464ed01)
![image](https://github.com/user-attachments/assets/d40af0b7-35af-47e4-99d8-3e4bf2fe0d18)
# From the Analysis we can see that Wednesday recorded the day with the highest incident and Sunday with the lowest incident
![image](https://github.com/user-attachments/assets/e96f8958-7705-4288-ae50-fe72f128e255)
# From the monthly hazard analysis, March had the highest record with June the lowest
![image](https://github.com/user-attachments/assets/136bc6d6-dc92-415c-954a-1da7713e7268)
# performed yearly Hazard between 2015 -2017 and year 2017 had the highest incident record with a total of 2309,  and year 2015 had the least hazards records of 803.
![image](https://github.com/user-attachments/assets/59e05a01-3232-4422-b743-0a01270692f2)
![image](https://github.com/user-attachments/assets/817b311a-d0e8-4aa8-9945-cf8dd260e0e8)
# Performed analysis using scatter plot to show the relationship between th nature of injury and how fatl it is, it was recorded that the fatal incident type was more
![image](https://github.com/user-attachments/assets/4419cbed-7597-4039-aa15-472691d18715)
# Fall from height was the highest event type that lead to death and serious injury of workers on site while Inhalation of substances was the least harmful
 ![image](https://github.com/user-attachments/assets/2f3e8496-6368-4617-a75b-fc872b15f60b)
# analysed the haz-sub column and the degree of injury using the boxplot to show the relationship
![image](https://github.com/user-attachments/assets/2ab21f97-d17c-4529-8ce9-b984925c801e)
# showed the pie chart distribution of fatal incidents
![image](https://github.com/user-attachments/assets/fe6a8ab1-9e2b-4bf4-8c06-a953e9cf9875)
# parts of body mostly affected by hazardous event the head is mostly affected and the neck all of which can lead to death or stroke.
![image](https://github.com/user-attachments/assets/2d572d94-4342-4a9d-8ddd-6fbd026a8969)
# Analysed the human factor that can lead to incidents 
![image](https://github.com/user-attachments/assets/d270473f-b247-4876-8f77-c957e6fbb363)
Misjudgement by workers
inappropriate equipment can lead to a terrible incident



From the Analysis we can see that Wednesday recorded the day with the highest incident and Sunday with the lowest incident
From the monthly hazard analysis, March had the highest record with June the lowest
