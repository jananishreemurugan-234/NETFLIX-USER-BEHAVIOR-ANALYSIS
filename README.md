# NETFLIX-USER-BEHAVIOR-ANALYSIS
## Data Science & Analytics Internship Project – Tamizhan Skills

## Introduction
This project, Netflix User Behavior Analysis, is developed as part of the Data Science and Analytics Internship at Tamizhan Skills. Streaming platforms like Netflix generate massive amounts of user interaction data, including watch history, ratings, genres, and viewing duration. Analyzing this data helps platforms understand audience preferences, binge-watching patterns, and content performance.
This project applies data analytics techniques to study Netflix user behavior and generate insights that can guide content recommendation strategies and platform improvements.

## Problem Statement
Streaming services need to understand what types of content users prefer, how long they watch, and whether they binge-watch series. Without analyzing user behavior data, platforms cannot effectively personalize recommendations or optimize content investments.

## Objective
The objectives of this project are to:
- Analyze Netflix viewing behavior using historical watch data
- Identify top genres based on total watch hours
- Study watch hours per user and viewing engagement
- Detect binge-watching behavior patterns
- Analyze ratings in relation to genres
- Generate actionable insights to guide content suggestions

This project aligns with Tamizhan Skills internship goals by applying advanced data analytics concepts to a real-world digital platform.

## Dataset Description
The project uses three datasets:
- movies.csv – Movie and series metadata (genre, duration, ratings, Netflix originals)
- users.csv – User subscription and demographic details
- watch_history.csv – User viewing sessions, ratings, devices, and watch duration

These datasets are merged and cleaned to form a comprehensive behavioral dataset.

## Tools & Technologies
- Python
- Pandas & NumPy – Data cleaning and transformation
- Matplotlib & Seaborn – Visualization
- Scikit-learn (StandardScaler) – Feature normalization
- Time-Series & Behavioral Analysis

## Methodology
The analysis workflow implemented in the program code includes:

1.Loading and validating multiple CSV datasets

2.Cleaning missing values and standardizing data types

3.Merging watch history with movie metadata

4.Calculating total watch hours per genre and per user

5.Identifying top genres based on viewing time

6.Analyzing watch hours per user using histograms

7.Detecting binge-watching behavior using time-based session grouping

8.Studying ratings vs genres using boxplots

9.Identifying top titles based on watch hours and viewers

10.Generating CSV outputs and a summarized insight report

## OUTPUT
## Visualizations Included
## Bar Chart – Top genres by total watch hours
<img width="1000" height="600" alt="image" src="https://github.com/user-attachments/assets/8ee910f4-8237-4978-9fe9-76405308800c" />

## Histogram – Distribution of watch hours per user
<img width="800" height="500" alt="image" src="https://github.com/user-attachments/assets/afb5f908-f16d-48f5-8771-cec9f46483b1" />

## Bar Chart – Episodes watched per session (binge behavior)
<img width="800" height="500" alt="image" src="https://github.com/user-attachments/assets/df97505f-4e7b-43c4-b8fb-c9ebd0cfa00b" />

## Box Plot – Ratings distribution across genres
<img width="1200" height="600" alt="image" src="https://github.com/user-attachments/assets/670ae027-8409-42cc-a06b-ef3d6195d44c" />

These visualizations collectively form a user behavior analytics dashboard.

## Conclusion
This project demonstrates how data science and analytics can be used to extract valuable behavioral insights from streaming platform data. Through the Tamizhan Skills Data Science & Analytics Internship, practical experience was gained in multi-dataset integration, behavioral analysis, visualization, and insight generation. The findings from this project can help streaming services enhance user engagement and content recommendation systems.

## Internship Organization
Tamizhan Skills
