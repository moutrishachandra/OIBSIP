# OIBSIP
# Google Play Store Data Cleaning & Analysis Project

## Objective
The objective of this project is to clean, process, and analyze Google Play Store app data along with user reviews to identify patterns in app performance, user behavior, and sentiment trends. This helps in understanding market dynamics and improving decision-making.

## Tools & Technologies Used
-Python
-Pandas
-Matplotlib
-Seaborn
-VS Code

## Dataset Description
This project uses two datasets:

### 1. Apps Dataset
Contains information about applications:

-App Name
-Category
-Rating
-Reviews
-Size
-Installs
-Type (Free/Paid)
-Price
### 2. User Reviews Dataset
Contains user feedback:

-App Name
-Translated Review
-Sentiment (Positive, Negative, Neutral)
-Sentiment Polarity
-Sentiment Subjectivity

## Steps Performed
### 1. Data Preparation
-Loaded both datasets
-Handled missing values
-Cleaned columns like Size, Installs, and Price
-Converted data types for accuracy
### 2. Data Merging
-Combined apps and user reviews datasets using the common column App
-Created a unified dataset for analysis
### 3. Category Exploration
-Analyzed distribution of apps across categories
-Identified top categories with highest number of apps
### 4. Metrics Analysis
-Studied app ratings, installs, and pricing patterns
-Analyzed relationships between rating and installs
-Evaluated distribution of app prices
### 5. Sentiment Analysis
-Analyzed user sentiments (Positive, Negative, Neutral)
-Counted sentiment distribution across apps
-Identified overall user feedback trends
### 6. Data Visualization
-Bar charts for category distribution
-Histograms for ratings and price
-Scatter plots for rating vs installs
-Count plots for sentiment and app type
-Heatmap for correlation analysis

## Insights
-A few categories dominate the Play Store, indicating uneven distribution of apps.
-Free applications are significantly more common than paid applications.
-App ratings do not always correlate with higher installs.
-The majority of user sentiments are positive, showing overall user satisfaction.
-Some applications receive significantly higher engagement compared to others.
-The dataset initially contained inconsistencies which were successfully cleaned and standardized.

## Recommendations
-Developers should focus on high-demand categories to increase visibility and downloads.
-Offering free or freemium applications can help attract a larger user base.
-Improving app quality and user experience can lead to better ratings and engagement.
-Regular monitoring of user reviews and sentiment can help in identifying issues and improving apps.
-Data cleaning and preprocessing should always be performed before analysis to ensure reliable results.
-Future work can include advanced sentiment analysis or machine learning models for prediction.

 ## Conclusion
This project successfully performed data cleaning and analysis on Google Play Store datasets. By combining app data with user reviews, meaningful insights were generated regarding app popularity, user preferences, and sentiment trends. The findings can assist developers and businesses in making data-driven decisions to improve app performance and user satisfaction
