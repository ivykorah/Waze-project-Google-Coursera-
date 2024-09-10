# Waze-project-Google-Coursera-


This project is the capstone for Course 2 of the Google Data Analytics Python Certification. It focuses on understanding and preparing data for exploratory data analysis (EDA) to support the development of a churn prediction model for the Waze app.


## **Project Overview**
Waze, a popular navigation app, relies on its community of users and partners to make driving safer and more efficient. As part of Waze's growth strategy, the company aims to reduce user churn—those who uninstall or stop using the app. High retention rates suggest users are satisfied and continue using the app over time. This project focuses on analyzing user data to predict and reduce monthly churn, helping Waze enhance user retention and drive business growth.

The key questions addressed in this project are:
- Who are the users most likely to churn?
- Why do users churn?
- When do users churn?
  

## **Objectives**
Waze’s data team is at the initial stages of its churn project. This project includes the following tasks:
- Construct a dataframe from the churn dataset.
- Review the data types of each column.
- Generate descriptive statistics to understand the dataset better.
- Prepare the data for further analysis.
  

## **Dataset Overview**
The dataset consists of **14,999 rows** and **13 columns**, each representing unique user interactions. Below is a breakdown of the dataset:

- **ID** (int) - Sequential user identifier.
- **label** (obj) - Binary target variable indicating if a user has churned (“retained” or “churned”).
- **sessions** (int) - Number of times a user opened the app in a month.
- **drives** (int) - Number of driving occurrences where a user drove at least 1 km.
- **device** (obj) - Type of device used for the session.
- **total_sessions** (float) - Estimated total sessions since user onboarded.
- **n_days_after_onboarding** (int) - Days since a user first signed up.
- **total_navigations_fav1** (int) - Total navigations to favorite place 1.
- **total_navigations_fav2** (int) - Total navigations to favorite place 2.
- **driven_km_drives** (float) - Total kilometers driven during the month.
- **duration_minutes_drives** (float) - Total driving time (minutes) in the month.
- **activity_days** (int) - Number of days the user opened the app.
- **driving_days** (int) - Number of days the user drove at least 1 km.


## **Assignment Goals**
The main tasks of this project are to:
- Build and organize the dataset into a dataframe.
- Perform basic data cleaning and transformation.
- Prepare the dataset for exploratory data analysis (EDA).
- Update the team on progress and provide insights to support future modeling efforts.




