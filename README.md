# Flipkart Product Review Sentiment Analysis

## Objective

Analyze Flipkart product reviews to understand customer sentiment and identify factors influencing satisfaction, using Excel for data preparation and Power BI for interactive visualization.

## Tools & Technologies

* Advanced Excel (Data Cleaning, Transformation)
* Power BI (Data Modeling, DAX Basics, Dashboarding)
* CSV Dataset
* GitHub (Project Hosting)

## Dataset

* Source: Flipkart product reviews (public dataset)
* Fields used: Product Category, Rating, Review Text, Review Title, Date (if available), Sentiment (derived)

## Data Preparation (Excel)

* Removed duplicates and irrelevant records
* Handled missing values
* Standardized text fields (trim, case normalization)
* Created **Sentiment** column based on review polarity (Positive / Neutral / Negative)
* Exported cleaned data to CSV for Power BI

## Power BI Dashboard

Key visuals:

* Overall sentiment distribution
* Category-wise sentiment analysis
* Rating vs Sentiment comparison
* Top categories with highest negative feedback
* Interactive filters (Category, Rating)

## Key Insights

* Majority of reviews are Positive, indicating overall customer satisfaction.
* Certain categories show higher Negative sentiment, highlighting quality or expectation gaps.
* Low ratings strongly correlate with Negative sentiment, validating sentiment classification.
 
## Files in Repository

* flipkart_sentiment_analysis.pbix – Power BI report
* Flipkart_sentiment_analysis_cleaned_data.csv – Cleaned dataset
* descriptive_analysis.png
* diagnostic_analysis.png
* predictive_analysis.png

## How to Use

1. Download the `.pbix` file
2. Open in Power BI Desktop
3. If prompted, relink the CSV file path
4. Explore dashboard using filters

## Author

Sohayla Khan
GitHub: https://github.com/mangofruit04

