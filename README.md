# Play-store-analysis
# HELLO EVERYONE !
In this notebook, I am going to analyze Google Play Store datas.Mobile apps are everywhere. They are easy to create and can be lucrative. Because of these two factors, more and more apps are being developed. In this notebook, we will do a comprehensive analysis of the Android app market by comparing over ten thousand apps in Google Play across different categories. We'll look for insights in the data to devise strategies to drive growth and retention.

Let's take a look at the data, which consists of two files:
playstore data.csv: contains all the details of the applications on Google Play.
# There are 13 features that describe a given app.
user_reviews.csv: contains 100 reviews for each app, most helpful first. 
# The text in each review has been pre-processed and attributed with three new features: Sentiment (Positive, Negative or Neutral), Sentiment Polarity and Sentiment Subjectivity.

# PROBLEM STATEMENTS
# 1). Which apps are the highest earners?

# 2). Top categories on Google Playstore?

# 3). Ratio between paid and free apps

# 4) Distribution of apps based on its size

# 5) Apps with the highest number of positive reviews

# 6) Apps with the highest number of negative reviews.

# 7) Is sentiment_subjectivity proportional to sentiment_polarity?

# 8) Does Last Update date has an effects on rating?

# WHAT IS EXPLORATORY DATA ANALYSIS?
**Exploratory data analysis (EDA)** is used by data scientists to analyze and investigate data sets for patterns, and anomalies (outliers), and form hypotheses based on our understanding of the dataset and summarize their main characteristics, often employing data visualization methods. It is an important step in any Data Analysis or Data Science project. It helps determine how best to manipulate data sources to get the answers you need.

EDA involves generating summary statistics for numerical data in the dataset and creating various graphical representations to understand the data better and make it more attractive and appealing.

The following are the various steps involved in the EDA process:

**Problem Statement** - We shall brainstorm and understand the given data set. We shall study the attributes present in it and try to do a philosophical analysis about their meaning and importance for this problem.

**Hypothesis** - Upon studying the attributes present in the data base, we shall develop some basic hypothesis on which we can work and play with the data to look for the varied results which we can get out of it.

**Univariate Analysis**- It is the simplest form of analyzing the data. In this we would initially pick up a single attribute and study it in and out. It doesn't deal with any sort of co-relation and it's major purpose is to describe. It takes data, summarizes that data and finds patterns in the data.

**Bivariate Analysis** - This analysis is related to cause and the relationship between the two attributes. We will try to understand the dependency of attributes on each other.

**Multivariate Analysis** - This is done when more than two variables have to be analyzed simultaneously.

**Data Cleaning** - We shall clean the dataset and handle the missing data, outliers and categorical variables.

**Testing Hypothesis** - We shall check if our data meets the assumptions required by most of the multivariate techniques.



