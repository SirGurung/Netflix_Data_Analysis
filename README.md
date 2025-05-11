# Netflix_Data_Analysis

This is my first data analysis project, where I explore a Netflix dataset sourced from Kaggle. The aim of this project is to apply and consolidate the skills I’ve been learning in data analysis with Python, especially drawing from “Python for Data Analysis” by Wes McKinney.

## Project Objectives

Practice data cleaning and transformation using pandas

Perform univariate and bivariate exploratory data analysis (EDA)

Visualize insights using matplotlib and seaborn

Understand trends in Netflix content production over time

Practice version control using Git and GitHub

## Dataset

Source: Kaggle [Netflix Movies and TV Shows dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows)

Overview: The dataset contains information on Netflix titles including:

Title

Country

Release Year

Rating

Type (Movie or TV Show)

Duration

## Data Cleaning and Feature Engineering

Removed null values

Engineered new features by processing country data (e.g., splitting multi-country entries, normalizing values)

Converted date formats for consistency

Filtered data for analysis (e.g., from 2010 onwards for modern trends)

## Exploratory Data Analysis

Some key questions I explored:

What are the most common ratings on Netflix?

How many titles are Movies vs TV Shows?

What’s the average release year of titles?

How are title ratings distributed over time?

Which countries dominate Netflix content?

What trends can be observed from 2010 onwards?

## Tools Used

[Python](https://www.python.org/downloads/)
[Jupyter Notebook](https://jupyter.org/)
[Pandas](https://pandas.pydata.org/)
[Matplotlib](https://matplotlib.org/)
[Seaborn](https://seaborn.pydata.org/)
[Git & GitHub](https://github.com/)

## Key Insights & Business Implications

**Insight:** TV-MA and TV-14 are the most common ratings on Netflix. 

**Actionable Lead:** There is a strong global demand for mature-themed content. Invest in original productions or acquire rights to content within these rating categories.

**Insight:** PG-13 & R rated content is not featured in the TV-show category.

**Actionable Lead:** There is a potential content gap, explore mid-range mature TV show formats that would align with PG-13 or R rated classification. 

**Insight:** In South-East Asia, Thailand has a large proportion of their titles being rated TV-MA compared to other SEA countries. Also Malaysia has no R rated content. 

**Actionable Lead:** Develop region-specific content strategies, for Thailand promote bolder titles and invest in local adult themed productions. Whilst for Malaysia, prioritisation of family-friendly or censored versions of popular global titles. 

**Insight:** The Top 10 countries for producing titles on Netflix includes the United States, India and United Kingdom. 

**Actionable Lead:** These markets are mature but may be approaching content saturation. An opportunity could be to localise and translate content from these top 3 markets into regional languages such as Japanese-subbed US films to broaden reach. 

**Insight:** The number of titles increased sharply after 2013, peaking around 2018, which was followed by a decline in the titles in various categories across Netflix. 

**Actionable Lead:** The decline in titles after 2018 could suggest saturation or a strategic shift towards quality of titles rather than mass acquisition of titles. 







