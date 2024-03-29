# Web-Traffic-Engagement-Analysis

## Overview
This project aims to analyze web traffic engagement data to gain insights into user behavior and optimize ad placement strategies. The dataset includes various features such as 'Daily Time Spent on Site',	'Age',	'Area Income','Daily Internet Usage',	'Ad Topic Line',	'City',	'Gender','Country,,'Timestamp','Clicked on Ad','Ad_code'.



## Notebook
The project is documented in a single Jupyter notebook (web_traffic_engagement_analysis.ipynb) containing the following sections:

## Introduction: Brief overview of the project and objectives.

* Data Exploration: Exploratory Data Analysis (EDA) to understand the dataset and relationships between variables.
* A/B Testing: Analysis of A/B testing results to compare user engagement metrics between different groups.
* Segmentation Analysis: Identification of different segments of users based on demographics or behavior.
* Clustering Analysis: Application of machine learning algorithms such as K-means and DBSCAN for clustering users.
* Machine Learning Modeling: Development and evaluation of machine learning models for predicting user engagement or ad click-through rates.
* Conclusion: Summary of key findings and insights.

## Insights
Here are some key insights from the analysis:

* Ad Engagement Time: Ads clicked within 60 minutes are more successful, suggesting the need for more relevant ads.

* Gender Interaction: Young women engage more, indicating a need for ads tailored to this demographic.

* Optimal Timing: Evening and night show peak engagement, suggesting these times for testing new strategies.

* Ad Similarity: Ads 1002 and 1004 target similar audiences, recommending similar ad types for better engagement.

* Segment Performance: Ads 1001 and 1003 perform well, with potential for improvement in targeting similar ads.

* Statistical Tests: Data is not normally distributed; Mann-Whitney U test shows demographic differences between ads; Pearson's Chi-Squared test lacks evidence of gender-ad clicking association.

* Machine Learning Insights: Logistic Regression shows strong accuracy in predicting ad clicks based on gender, age, time spent, and area income. K-Means and DBSCAN clustering reveal key contributors to engagement, particularly age and area income.

## Setup Instructions
Clone the repository to your local machine.
Install Jupyter Notebook and the required Python packages.
Open the web_traffic_engagement_analysis.ipynb notebook and run each cell sequentially.
