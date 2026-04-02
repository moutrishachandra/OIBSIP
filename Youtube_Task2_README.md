# OIBSIP
# YouTube Trending Videos Data Cleaning Project

## Objective
The objective of this project is to perform data cleaning on the YouTube trending videos dataset to improve data quality, ensure consistency, and prepare the dataset for accurate analysis and decision-making.

## Tools & Technologies Used
-Python
-Pandas
-Matplotlib
-Seaborn
-VS Code 

## Dataset Description
The dataset contains information about trending YouTube videos in India, including:

-Video ID
-Title and Channel Name
-Category ID
-Views, Likes, Dislikes, Comment Count
-Publish Time and Trending Date
-Video Description

## Steps Performed
### 1. Data Integrity
       Verified dataset structure and column names
       Ensured consistency in data types
### 2. Missing Data Handling
       Identified missing values in the dataset
       Filled missing values in the description column
### 3. Duplicate Removal
       Identified duplicate records
       Removed 4263 duplicate rows to maintain data uniqueness
### 4. Standardization
       Converted date columns (trending_date, publish_time) into proper datetime format
       Ensured numerical columns are correctly formatted
       Maintained consistency across all columns
### 5. Outlier Detection
       Used visualization techniques (boxplots) to detect outliers in numerical columns such as views
       Observed extreme values representing highly popular videos
### 6. Feature Engineering
       Created new features:
       Day
       Month
       Engagement Ratio
       
##  Insights
-The dataset initially contained missing values and duplicate records, which were successfully handled during the data         cleaning process.
-A large number of duplicate entries (4263) were removed, improving the overall data quality and reliability.
 The majority of trending videos belong to category 24 (Entertainment), indicating that entertainment content dominates the    platform.
-Videos such as YouTube Rewind 2017 and major movie trailers received the highest number of views, highlighting the            popularity of large-scale productions.
-A positive relationship exists between views, likes, and comments, suggesting that highly viewed videos tend to generate      higher engagement.
-Engagement varies across videos, indicating that not all popular videos receive proportional user interaction.
-Time-based analysis using day and month features enables better understanding of trending patterns.

## Recommendations
-Content creators should focus more on entertainment-based content, as it consistently attracts higher audience engagement     and dominates trending categories.
-High-impact content such as movie trailers, promotional events, and viral campaigns should be prioritized to maximize reach   and visibility.
-Engagement metrics (likes and comments) should be monitored to improve content quality and audience interaction strategies.
-Posting schedules can be optimized using time-based insights (day and month) to target periods of higher audience activity.
-Data preprocessing and cleaning should always be performed before analysis to ensure accuracy and reliability of insights.
-Future analysis can include sentiment analysis of comments or mapping category IDs to actual category names for deeper        insights.

## Conclusion

This project successfully performed data cleaning on the YouTube trending videos dataset. The dataset was improved by handling missing values, removing duplicates, standardizing formats, and identifying outliers. Additionally, basic analysis provided insights into content trends and engagement patterns. The cleaned dataset is now reliable and ready for further analysis or machine learning applications.
