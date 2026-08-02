# Bellabeat Smart Device Usage Analysis

## Project Overview

This case study analyzes Fitbit smart device usage data to identify
trends in physical activity, sleep behavior, and calorie expenditure.

The project was completed as part of the Google Data Analytics
Professional Certificate capstone.

The objective was to translate smart-device usage trends into
actionable recommendations that could support Bellabeat's
marketing strategy.

## Business Questions

1. What are some trends in smart device usage?
2. How could these trends apply to Bellabeat customers?
3. How could these trends influence Bellabeat's marketing strategy?

## Tools Used

- Microsoft Excel — Data cleaning and preparation
- Tableau — Data analysis, visualization, and dashboard development

## Dataset

The analysis uses Fitbit Fitness Tracker Data containing information
about users' daily activity, steps, calories, and sleep.

The primary datasets used were:

- dailyActivity_merged
- sleepDay_merged

The weight dataset was excluded from the final analysis because of
insufficient data.

## Data Preparation

The data preparation process included:

- Checking for duplicate records
- Identifying missing values
- Standardizing date formats
- Verifying data types
- Evaluating incomplete datasets
- Preparing activity and sleep data for Tableau
- Creating relationships between activity and sleep data

## Analysis

The analysis focused on:

- Daily step patterns
- Daily calorie expenditure
- Activity intensity
- Activity patterns by weekday
- Sleep duration by weekday
- Relationship between daily steps and calories
- Relationship between sleep duration and daily activity

## Tableau Dashboard

### User Activity Analysis

<img width="1165" height="680" alt="activity_dashboard" src="https://github.com/user-attachments/assets/95bb8f9a-4106-4f1f-a31b-bc5b9542e54f" />


### Sleep & Wellness Analysis

<img width="1185" height="678" alt="sleep_wellness_dashboard" src="https://github.com/user-attachments/assets/3e745270-ba09-4532-9073-49a39f0d0499" />


## Interactive Dashboard

View the interactive Tableau dashboard here:

https://public.tableau.com/views/Bellabeat_Case_Study_17857109906250/SleepWellnessDashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

## Key Findings

- Users spend a substantial portion of their day in sedentary activity.
- Daily activity levels vary across different days of the week.
- Higher daily step counts are associated with greater calorie expenditure.
- Average sleep duration varies moderately throughout the week.
- Sleep duration shows little apparent relationship with daily step count
  in this dataset.

## Recommendations

1. Bellabeat could use personalized movement reminders and activity goals
   to encourage users to reduce sedentary time.

2. Activity and sleep data could be used to provide personalized wellness
   insights and recommendations through the Bellabeat app.

3. Bellabeat could develop targeted wellness campaigns based on user
   activity patterns and promote features related to activity, sleep,
   and overall wellness.

## Limitations

- The dataset contains a relatively small sample of users.
- The observation period is short.
- The data was collected in 2016.
- Demographic information is limited.
- Some Fitbit datasets contain substantial missing information.

## Project Files

- [📁 Data](./data/) — Cleaned datasets used for analysis
- [📁 Tableau](./tableau/) — Tableau packaged workbook
- [📁 Images](./images/) — Dashboard screenshots
- [📁 Report](./report/) — Full case study report

## Author

Neelanjana J Kumar

Google Data Analytics Professional Certificate
