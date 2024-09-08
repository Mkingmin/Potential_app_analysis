# Overview
The company is planning to develop an ad-supported mobile app, but needs to conduct thorough analysis to identify the most promising type of app that can deliver the highest ROI.
<br><br> As a Business Analyst, analyze historical performance data of multiple apps on Google Play and App Store, and provide optimal recommendations to support the company's business objectives.
# Objectives
The primary objective of these analyses is to identify mobile app profiles that attract the most users.
<br><br> Since the company is planning to develop an ad-supported mobile app, which allows users to download and use the app for free, revenue is generated from in-app ads. Therefore, the more downloads and usage, the more ad views and consequently, the higher the revenue.
# Dataset
With the purpose of completing this project to practice problem-solving skills from case studies and improve data analysis techniques, I did not spend too much time, effort, and money to collect the massive real-world dataset of over 2 million active apps on the App Store and Google Play (data as of 2018 according to [Statista](https://www.statista.com/statistics/276623/number-of-apps-available-in-leading-app-stores/)). Instead, the dataset used for analysis is a sample dataset with similar characteristics to the requirements needed for the project.
<br><br> Two sample datasets from Kaggle posts by Lavanya and Ramanathan, containing performance data of over 7,000+ apps on Google Play and App Store, are suitable for conducting the analyses in this project. I would like to express my sincere gratitude to both of them.
# Exploratory Data Analysis (EDA)
## Data cleaning
- Handling missing data
- Removing wrong data and duplicate values
- Removing Non-English apps
- Isolating free apps
## Most popular apps by Genre
With the goal of identifying mobile app profiles that can attract a large number of downloads on both Google Play and App Store platforms, conduct an analysis of user interest in each app category through the following steps:
- Create a frequency table by Genre and Category to observe which genres and categories the majority of apps on both platforms belong to
- Analyze the download volume (or ratings) of each Genre to assess user interest by Genre
## Insights
From the above analysis, the following meaningful insights are revealed:
- Adventure appears to be popular on both Google Play and App Store, promising to provide many insights to explore, but the current dataset is insufficient for analysis. It is recommended to continue analysis when the dataset is updated.
- The majority of apps on the App Store are for-fun apps, with 58% of apps belonging to the Game genre.
- FAMILY is a rich category with diverse topics to explore, which has a large number of downloads on Google Play
- Casual is a genre with impressive downloads, mainly consisting of time-killing games, games for all ages, reflecting users' demand for entertainment and quick relaxation during work hours. However, these games mainly focus on puzzle games and voice interaction. Therefore, there is still room to explore diverse time-killing game topics for all ages.
- Book & Reference is one of the most popular genres. The types of apps in this genre are not yet diverse, with only a few notable and popular apps. There is still an opportunity to explore more features in this genre.
## Recommendation
In this project, we analyzed data about the App Store and Google Play mobile apps with the goal of recommending an app profile that can attract more and more users to download on both platforms.
<br><br> With the potential interest of users in Book & Reference genre and Casual genre in both Google Play and App Store, developing an ad-supported mobile app that combines the features of a reading app and a casual game *for all ages*, focusing on puzzle challenges related to book content, language practice, programming, or finance could yield a promising profit for our company.
