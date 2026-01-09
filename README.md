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

## KPI performed 
# 1.Reivew_Length Distribution:
A new feature review_length is created to represent the number of charactersin each review.
<img width="695" height="468" alt="Image" src="https://github.com/user-attachments/assets/85c64d14-40e5-4c4c-b1b6-fcb35a1cf57c" />
# 2.Distribution of Rating
Distribution of ratings( Positive , neutral , negative)
<img width="561" height="427" alt="Image" src="https://github.com/user-attachments/assets/7e56d87d-624c-4465-8748-cc535547e3ff" />
# 3.Understanding Sentiment_Score
how scores are distributed 
<img width="552" height="413" alt="Image" src="https://github.com/user-attachments/assets/3416f112-e63b-4902-adba-0ebd41cfda03" />
# 4.Sentiment Distribution 
sentiment distribution of reviews(The majority of customer reviews are neutral, indicating that most customers give moderate feedback. Positive reviews are less frequent, and negative reviews are the fewest. )
<img width="580" height="453" alt="Image" src="https://github.com/user-attachments/assets/b99db9e3-107d-4f5a-961d-42292285f85d" />
# 5.Rating VS Sentiment
It proves that sentiment scores align well with customer ratings, validating the effectiveness of VADER sentiment analysis. 
<img width="567" height="453" alt="Image" src="https://github.com/user-attachments/assets/bfbe88eb-be23-4aed-9d8a-e1b573944c83" />
# 6.Best Performing Product
The top 10 best performing products have the highest average sentiment scores, indicating strong positive customer feedback. These plots help identify products that need improvement versus those that are performing well. 
<img width="1013" height="857" alt="Image" src="https://github.com/user-attachments/assets/d839ca48-cf2f-4f98-9f0b-f0e9e06ff939" />
# 7.Worst Perdorming Product
The top 10 worst performing products have the lowest average sentiment scores, reflecting mostly negative reviews or complaints. These plots help identify products that need improvement versus those that are performing well. 
<img width="1000" height="1251" alt="Image" src="https://github.com/user-attachments/assets/8a5b0773-cdec-4497-a8fa-33b25042cbe6" />
# 8.Complain Rate by Product
The top 10 products with the highest complaint rates were identified using the proportion of negative reviews. The tallest yellow bars indicate products with the most negative customer feedback, highlighting areas that may need improvement 
<img width="949" height="994" alt="Image" src="https://github.com/user-attachments/assets/30ac136c-4b6e-4aee-a783-669d80295b94" />
