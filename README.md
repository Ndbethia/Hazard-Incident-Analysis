
# Hazard-Incident-Analysis
This is apersonal project to practice my skillsets in Data science and Safety. It is an analysis of Hazards in the construction sector (Building) to help know the hazards they are faced with and how to reduce its occurrence to create a safe working environments for workers.
# Introduction
The dataset was gotten from Kaggle it contained 4847 rows and 28 columns, with categorical and numeric columns.
The dataset contains information about occupational safety and health incidents, with columns like:
•	summary_nr: Unique identifier for incidents.
•	Event Date: Date of the incident.
•	Abstract Text: Detailed description of the event.
•	Event Description: A summary of the incident.
•	Event Keywords: Key terms associated with the event.
•	Event type: Type of incident (e.g., "Fall," "Caught in or between").
•	Environmental Factor: Contributing environmental conditions.
•	Human Factor: Contributing human behaviors or errors.
•	Task Assigned: Whether the task was assigned regularly.
•	hazsub, fat_cause, fall_ht: Details about hazardous substances, fatal causes, and fall height.
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
![image](https://github.com/user-attachments/assets/76a0b418-0ba0-4373-ae87-29cc41a0b708)
Misjudgement by workers
inappropriate equipment can lead to a terrible incident
# Construction End use 
Commercial buildings cause majority of the hazards in the construction site while sewer has little impact or potential of causing hazards
![image](https://github.com/user-attachments/assets/6b93bc15-ab4b-4096-a010-dc617a2e1374)

# Transform categorical data to numeric date for machine learning and predictions
![image](https://github.com/user-attachments/assets/4fefb2d7-b05d-4c92-ad0d-b90f2ea2cfea)
![image](https://github.com/user-attachments/assets/496828d9-a67c-4e2d-a073-8fb4331e7f82)

# 3.	Build a predictive model: 
# importing machine learning models
![image](https://github.com/user-attachments/assets/7b774548-6b7c-4afc-bfa9-6bedf4586393)
	Use classification models (e.g., Random Forest, Logistic Regression) to predict high-risk incidents based on: 
	day,month year.
	Location characteristics.
	Historical incident data.
	Evaluate model accuracy using metrics like precision, recall, and F1-score.
# preparing data for modelling
![image](https://github.com/user-attachments/assets/7285874f-3373-4ba2-876a-3a1b35874103)
![image](https://github.com/user-attachments/assets/c331a721-51d4-4f7d-b056-3a4f6b809549)
# splitting, training and testing data
![image](https://github.com/user-attachments/assets/979e4a85-451d-411f-a937-47a1e5fca3c8)
![image](https://github.com/user-attachments/assets/c4a4651b-79f6-4d96-8e4a-aa69cfad1034)
![image](https://github.com/user-attachments/assets/654b8085-7006-4f39-94d5-b99b510b32f2)
# prediction of score
![image](https://github.com/user-attachments/assets/04c2f4fd-b515-474a-aeb8-f510a0d6ef19)
# confussion matrix visual
![image](https://github.com/user-attachments/assets/955e9b71-1671-4ed7-84ae-fc1e00389e34)

# 4.	key insights and Recommendation:
From the Analysis we can see that Wednesday recorded the day with the highest incident and Sunday with the lowest incident
  # Incident Trends Over Time
*The analysis showed that March had the highest record with 717 incidents and June the lowest with 154 incidents.
o	From the Analysis we can see that Wednesday recorded the day with the highest incident of 930 and Sunday with the lowest incident with 206 probably because they work less on weekends and more during the week.
# .	Categorical Analysis
o	What are the most common event types are "Falls(elevation)", "Struck-by", "caught in between', 'shock', with the least "inhalation of substance"Event_type
Fall (from elevation)    1145
Struck-by                1117
Caught in or between     1109
Other                     629
Shock                     189
o	The Human factor that leads to incidents includes:
Materials Handling Equip./Method           625
Work-Surface/Facility-Layout Condition     590
Pinch Point Action                         416
Overhead Moving/Falling Object Action      314
Catch Point/Puncture Action                183

The Human factor that leads to incidents include: 

Misjudgment, Hazardous Situation         1364
Safety Devices Removed/Inoperable        266
Position Inappropriate For Task          215
Mater-Handling Procedure Inappropriate   153
Insufficient /Lack/Engineering Controls  148

# Severity Analysis
o	The degree of severity of these incidents are mostly fatal which may lead to death.

# Industry-Specific Insights
o	the construction end use was more for commercial purpose.
Commercial building                       272
Single family or duplex dwelling          189
Other building                            138
Multi-family dwelling                     125
Highway, road, street                      81
Manufacturing plant                        37

# Preventative Recommendations
-- Staffs and workers should be trained adequately on how to identify hazards and how to avoid and prevent it from happening so as to reduce the risk of death, fallings and other injuries as well as provide a safe working environment. 
-- The use of controls like
Engineering Administrative controls
Administrative controls
PPEs like Helmet, scaffoldings, boots, etc.


