
# Hazard-Incident-Analysis
This is an analysis of Hazards in the construction sector (Building) to help know the hazards they are faced with and how to reduce its occurrence to create a safe working enironments for workers.

# Introduction
The dataset was gotten from Kaggle it contained 4847 rows and 28 columns, with categorical and numeric columns.

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

 Analyzed distributions of incident types, severity, and root causes like Environmental and human factors.
 I described my data to derive insights and determine outliers and relationships
 ![image](https://github.com/user-attachments/assets/36a657e1-8821-49f0-8f3f-3e2994bd43ec)
 ![image](https://github.com/user-attachments/assets/008fe8f1-1fbc-4a39-aef9-8f8d4ac117b0)
Transformed the Event_Date column to Date time so i can Extract the days, month, Year
![image](https://github.com/user-attachments/assets/1543a08a-9b3a-42cc-bd9a-fedda464ed01)
![image](https://github.com/user-attachments/assets/d40af0b7-35af-47e4-99d8-3e4bf2fe0d18)
From the Analysis we can see that Wednesday recorded the day with the highest incident and Sunday with the lowest incident
![image](https://github.com/user-attachments/assets/e96f8958-7705-4288-ae50-fe72f128e255)
From the monthly hazard analysis, March had the highest record with June the lowest

 ![image](https://github.com/user-attachments/assets/860708fc-3267-464e-b340-955da6bf7eb2)
![image](https://github.com/user-attachments/assets/239a5336-0101-4f62-bce5-d612b38b26b5)



 
 
3.	Build a predictive model: 
	Use classification models (e.g., Random Forest, Logistic Regression) to predict high-risk incidents based on: 
	Time of day.
	Location characteristics.
	Weather conditions (if available).
	Historical incident data.
	Evaluate model accuracy using metrics like precision, recall, and F1-score.
4.	Automate insights: 
	Generate automated reports summarizing key findings.

From the Analysis we can see that Wednesday recorded the day with the highest incident and Sunday with the lowest incident
From the monthly hazard analysis, March had the highest record with June the lowest
