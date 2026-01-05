# **Sentiment Analysis of Product Reviews**
## Project Overview

This project performs sentiment analysis on product reviews using the VADER Sentiment Analyzer. The goal is to analyze customer opinions, understand product ratings, identify best and worst-performing products, and find areas with high complaint rates.

# Steps Performed

## 1.Loading the Dataset
-Imported the dataset for analysis.

-Data Cleaning which includes Removed unnecessary columns (e.g., Unnamed columns).

## 2.Initial Data Exploration
-Checked the dataset using head(), tail(), shape, columns, and info()

## 3.Descriptive Statistics
-Used describe() to get summary statistics of numeric columns.

## 4.Missing Value Analysis
-Checked for missing values using isnull() and isnull().sum()

-Confirmed that the dataset has no missing values.

## 5.Product Analysis
-Analyzed product distribution using value_counts() for the top 10 and bottom 10 products.

-Printed the total number of unique products.

-Counted each rating in the dataset.

## 6.Feature Engineering
-Calculated the review length.

-Analyzed the distribution of review lengths.

-Explored the distribution of ratings.

## 7.Sentiment Analysis
-Removed rows with missing review text.

-Converted review text to string format.

-Initialized the VADER Sentiment Analyzer.

-Computed sentiment scores for each review.

-Generated sentiment labels using quantile-based thresholds.

## 8.Text Preprocessing and Cleaning
-Found 123 duplicate reviews and removed them.

-Used re(regular expression) to clean review text for analysis.

-Generated a clean review column for further analysis.

## 9.Exploratory Data Analysis (EDA)
-with help of matplotlib and seaborn

-Analyzed sentiment 

-Plotted rating vs sentiment.

-Identified best and worst performing products.

-Found products with the highest complaint rates.

## 10.Conclusion

This project provides insights into customer opinions, product performance, and complaint trends. It can help businesses make data-driven decisions to improve products and services.

## 10.Limitations

-Only uses VADER for sentiment analysis not a traditional machine learning model 
still so many KPI are left!

-Quantile-based thresholds for sentiment labeling may not be perfect for all datasets.

-Analysis depends on the quality and size of the dataset.
