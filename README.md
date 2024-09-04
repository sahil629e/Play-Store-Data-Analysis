![--------------------------------------------------------------------------------------------](https://github.com/andreasbm/readme/blob/master/assets/lines/grass.png)

# Google Play Store Apps Analysis

## Problem Statement
The objective of this project is to explore and analyze the Google Play Store apps dataset, which includes information such as category, rating, size, and more. Additionally, a dataset containing customer reviews of Android apps is provided. The goal is to discover key factors that contribute to app engagement and overall success.

### Data Source
- [Dataset](https://drive.google.com/file/d/15SLvsarYG1wRaiZm21cC8XRfiWg0yTc1) - Dataset taken from AlmaBetter

## Features
- **App Category:** Category of the app (e.g., Beauty, Business, Entertainment, Education, etc.).
- **Rating:** User rating of the app out of 5.
- **Reviews:** The number of user reviews received by each app.
- **Size:** Memory size required to install the app.
- **Installs:** The number of times each app has been installed.
- **Type:** Whether the app is free or paid.
- **Price:** The price of the app.
- **Content Rating:** Intended audience for the app (e.g., Everyone, Teens, Mature).
- **Genres:** Sub-category of the app (e.g., Education: Pretend Play).
- **Last Updated:** Date of the most recent update.
- **Current Ver:** Current version of the app.
- **Android Ver:** Oldest version of Android OS supported by the app.

## 🛠️ Built With
![Python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue)
![NumPy](https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![Seaborn](https://img.shields.io/badge/Seaborn-blue?style=for-the-badge&logo=Seaborn)

## Summary and Conclusion
Google Play Store is one of the largest and most popular Android app stores globally. With its extensive collection of apps and a wealth of data, it offers an optimal opportunity for creating effective models and identifying trends and future challenges.

In this EDA project, we utilized two raw datasets from Kaggle: one containing Play Store attributes and another consisting of user reviews. The first dataset encompasses 13 different attributes, while the second dataset provides five additional features for data manipulation and analysis.

### Data Cleaning
To ensure data integrity, we began by performing crucial data cleaning steps. This involved removing duplicate entries and dropping non-essential null values. Due to a large number of null values in the rating column (1645), dropping them entirely would have adversely affected our final results. Therefore, we replaced these null values with the mode of ratings.

### Exploratory Data Analysis (EDA)
After cleaning the data, we conducted exploratory data analysis to gain a comprehensive understanding of our dataset. This involved various analyses, such as examining the number of installations for each category and exploring the correlation between app size, Android version, and the number of installs. We also merged both dataframes to discover correlations between the columns of the two datasets, which yielded fascinating results.

### Key Insights and Conclusions
- Positive correlation between reviews and installs, while price and rating exhibit a negative correlation.
- The "Art and Design" category has the highest number of installs.
- Developing apps within the "Family" and "Lifestyle" categories may result in higher revenue.
- Approximately 61% of users have a positive sentiment, while only around 15% express negative sentiment.
- Free apps account for 92.12% of the dataset, while paid apps constitute 7.81%.
- The "Everyone" content rating category dominates, representing 81.80% of all apps.
- The most prevalent categories on the Play Store are "Family," "Game," and "Tools."
- The "Game" category presents potential opportunities for developers due to its high number of installs.
- Popular genres for app downloads include "Tools," "Entertainment," "Education," "Business," and "Medical."
- The average rating of apps on the Play Store is 4.17, indicating satisfactory overall quality.
- Users prefer lightweight apps and may hesitate to download larger, paid apps.
- Apps with a larger number of reviews tend to be downloaded more frequently.
- Paid apps receive harsher reviews from users.
- A positive correlation exists between installs and rating.
- Developing an app with a high rating requires timely updates and an optimal app size.
- Developing free apps with a content rating suitable for everyone is beneficial.

This project holds immense potential for improving business value and making a positive impact. Numerous other interesting possibilities await further exploration through continued analysis.
