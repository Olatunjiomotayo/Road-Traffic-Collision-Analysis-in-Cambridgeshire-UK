# Analysis of Road Traffic Collisions in Cambridgeshire, United Kingdom

## Table of Contents

- [Project Overview](#project-overview)
- [Research Objectives](#research-objectives)
- [Research Questions](#research-questions)
- [Data Source](#data-source)
- [Research Design](#research-design)
- [Research Focus and Answers](#research-focus-and-answers)
    - [Contributing Factors](#contributing-factors)
    - [Result of Machine Learning Models](result-of-machine-learning-models)
    - [Key Stakeholders](#key-stakeholders)
    - [Recommendations](#recommendations)

## Project Overview

Road Traffic Collisions (RTC) poses a huge global menace in urban settings leading to damage of properties, injuries, tragic loss of life, and socio-economic consequences. This project conducts a comprehensive analysis of road accident data in Cambridgeshire focusing on the collision severity across different levels (slight, serious, and fatal), distributions, and statistical analysis to give insight into the contributing factors, the patterns and trends. The study addresses the need for robust Machine Learning (ML) algorithms for effective prediction of road traffic severity. 

This research aim to contribute to the growth of Cambridgeshire and the findings will help several key stakeholders in making informed decisions and implementing practical measures to curb the occurrences and severity of road traffic accidents.


## Research Objectives:

1.	Perform exploratory data analysis to know distribution of each variable and their relationships across the categories of collision severity to get insights on major contributing factors.

2.	Build highly effective ML models, including GBM, LR, RF, SVM and NN that can accurately predict high-risk regions, factors, level of severity and number of casualties for RTCs in Cambridgeshire.

3.	Assess and evaluate the effectiveness of the models with appropriate metrics for forecasting the occurrence and severity of RTCs.

4.	Offer valuable insights and visualisations that can help traffic management authorities in Cambridgeshire to reduce RTCs and provide recommendations to facilitate the development of road safety policies and preventive measures.


## Research Questions:

1.	What are the primary factors contributing to the occurrence of road traffic accidents and severity of collisions in Cambridgeshire?

2.	Which machine learning model is most effective for predicting the severity of road traffic collisions in Cambridgeshire?

3.	Who will benefit from this road traffic collision analysis, and how can it be used to improve road safety and curb accidents in Cambridgeshire?

4.	What recommendations can be made to the department for transportation, local authorities, road safety corps, traffic management, and policymakers to enhance road safety and limit the number of casualties in Cambridgeshire?


## Data Source

This study used a dataset obtained from the Cambridgeshire Insight data repository. The dataset spans from January 1, 2017, to March 31, 2024, and consists of three sheets, each addresses different aspect of the collisions:

- Crashes: Provides a list of the collisions that took place.			
- Vehicles: Provides a list of all the vehicles that were involved in the collisions.	
- Casualties: Provides a list of all the casualties that occurred because of the collisions.


## Research Design:

![image](https://github.com/user-attachments/assets/92e6c3fe-b2dd-40ae-b9b7-18adfc3dc324)


## Research Focus and Answers

### 1.	What are the primary factors contributing to the occurrence of road traffic accidents and severity of collisions in Cambridgeshire?

### Contributing Factors:
i.	Human Factors: 
-	Speed Limit: higher speed limit leads to increased force of impact and collision severity.
-	Driver Fatigue: causes error that can lead to collision.
-	Driving under the influence of alcohol.
-	Driving Recklessly.

ii.	Environmental Factors:
-	Lightening Condition: Inadequate lightening or absence of streetlight at night leads to severe collisions.
-	Weather: Rain, Snow or fog reduce driver’s visibility and road traction.
-	Road Conditions: Roads with poor maintenance can cause accident.
-	Inadequate Road Design.
  
iii.	Vehicular Factors:
-	Vehicle Maintenance: Faulty brakes, bad or degraded tyres can increase the risk of an accident.
-	Vehicle Type: Larger vehicles cause more collision severity.
-	Safety Features: Seat belts, lack of airbags increases the risk of severe collision.

### 2. Which machine learning model is most effective for predicting the severity of road traffic collisions in Cambridgeshire?

### Result of Machine Learning Models

In this project, five machine learning models were built including:
- Gradient Boosting Machine (GBM)
- Multi-Layer Perceptron (MLP)
- Support Vector Machine (SVM)
- Logistic Regression (LR)
- Random Forest (RF).

The performance of the models was evaluated using recall, precision, and F1-score. The models established a strong performance with high accuracy. Random forest classifier performed best with accuracy of 97%, Multi-Layer Perceptron and Gradient Boosting Machine came close with accuracy of 95% and 93% respectively. Support Vector Machine has accuracy of 92% while Logistic Regression has lowest accuracy of 88%.

### 3. Who will benefit from this road traffic collision analysis, and how can it be used to improve road safety and curb accidents?

### Key Stakeholders:

- Department for Transportation
- Local Traffic Management Authorities
- Road Safety Corps
- Cambridgeshire County Council
- Transportation Authorities
- Emergency Services Department
- Public
- Media
- Local Businesses and Logistics Companies

The analysis can be used by the department of Transportation to help create policies that promote road safety. The road safety corps can concentrate its initiatives on high-risk areas and periods, this will reduce traffic collisions through targeted intervention. The local authorities and policy makers can utilise the findings of this study to educate drivers, motorists and residents and regulate their traffic rules and laws, like prospective speed limits, speed camera, road design, use of seatbelts, and procedures for enforcement.

### 4. What recommendations can be made to local authorities, traffic management, and policymakers to enhance road safety and limit the number of casualties in Cambridgeshire?

### Recommendations

Based on the analysis findings, the following recommendations could be made to enhance overall road safety in Cambridgeshire.

1.	Enhanced Speed Limit Enforcement: In the research findings, there is a clear relationship between collision severity and higher speed limit of 60 to 70 mph, this necessitates the need to put tougher speed limit measures in place, especially on routes with higher speed limits.

2.	Targeted Interventions in High-Risk Areas:
The study identified South Cambridge and Huntingdonshire as the local authorities with highest collision occurrences, Friday, single carriageway road type, places with no streetlight at nights have higher risk of collision severity. Targeted measures including installation of speed cameras, road signage, improved streetlight, and traffic control systems could reduce the occurrences and severity of collisions.

3.	Public Awareness Campaigns:
Public awareness efforts could help in the reduction of unsafe driving habits. These programs should highlight the dangers of speeding, bad weather, emphasise the need of using seatbelts, driving in low light, and the dangers of distracted driving.

4.	Vehicle Safety and Technology:
All local authorities should ensure vehicle inspection agencies do due diligence on all vehicles before hitting the road to ensure they meet the safety standards. Likewise, automotive safety technologies including lane departure warning systems and automated emergency braking (AEB) should be embraced to lessen the occurrences and severity of collisions. This could be through public awareness by educating drivers on the advantages of these technologies.
