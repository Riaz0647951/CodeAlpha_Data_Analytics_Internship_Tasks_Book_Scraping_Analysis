# CodeAlpha_Data_Analytics_Internship_Tasks_Book_Scraping_Analysis

# Project Summary
This project involved a complete data analysis lifecycle, starting with Web Scraping (Task 1) to create a custom dataset of book titles, prices, and ratings. This data was then subjected to Exploratory Data Analysis (EDA) (Task 2) for cleaning and statistical analysis, culminating in these Visualizations (Task 3) to present key business insights.

# Key Visualizations & Findings
# 1. Distribution of Book Ratings
Finding: The book catalog exhibits a relatively balanced distribution across all star ratings, with a slight bias towards the lowest rating.

The 1-Star rating is the most frequent category, indicating that a significant portion of the catalog has books rated poorly by customers.

The counts for 2-Star, 3-Star, 4-Star, and 5-Star ratings are all closely grouped, suggesting that while the catalog has many high-rated books, it also has a notable number of lower-rated titles.

# 2. Frequency and Outliers of Book Prices
Finding: Book prices are widely distributed without a strong central cluster, and the box plot confirms the absence of extreme outliers in the dataset.

Frequency Distribution: The price frequency is somewhat uniform, ranging from approximately £10 to £60. This suggests the catalog includes a diverse mix of book values rather than focusing heavily on one price point.

Box Plot: The box plot shows that the middle 50% of book prices (the interquartile range) is between roughly £20 and £48. Crucially, the absence of dots above or below the whiskers indicates that there are no extreme price outliers in this particular data segment (all prices fall within the expected range, which is unusual for raw web-scraped data and suggests clean data capture).

# 3. Average Book Price by Star Rating
Finding: There is no significant correlation between a book's average price and its star rating.

The average prices for 1-Star, 2-Star, 3-Star, 4-Star, and 5-Star books all hover closely around the £35 mark.

The small error bars (indicating the variability or confidence interval) reinforce that the mean prices for all ratings are statistically similar.

Insight: This suggests that customers are not necessarily paying more for higher-rated books, or conversely, a higher price does not guarantee a better rating. Rating appears to be independent of price in this catalog.
