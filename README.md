# **Marketing & Retail Sales Project**


**Project Overview**

This notebook analyzes a consumer behavior dataset to explore how demographic, seasonal, and behavioral factors influence purchasing patterns. I began by loading the dataset and performing exploratory data analysis (EDA) to examine distributions of purchase amounts, popular product categories, and preferred shipping types across different customer segments and locations. I also investigated patterns by gender, season, and region to identify high-value customer groups and spending trends. The overall aim was to uncover insights that could guide targeted marketing strategies and improve profitability.

**Methods & Results**

After the initial EDA, I created customer segments using quantile-based thresholds to classify purchases as "High" or "Not High" spenders. A logistic regression model was built to predict whether a customer falls into the high-spending category, evaluated using a classification report and confusion matrix. I also applied k-means clustering to group customers based on purchasing behavior, revealing distinct patterns in purchase frequency and product preferences. Visualizations such as bar charts, pie charts, and heatmaps helped highlight trends, such as clothing being the most purchased category and certain states (like Montana and Alaska) showing higher customer counts and spending levels.

**Key Outputs**

- Cleaned and prepared retail dataset for analysis
- Visualizations of purchase amounts, category popularity, and shipping preferences
- Quantile-based segmentation into high vs. not high spenders
- Logistic regression model with performance metrics
- K-means clustering to identify distinct customer segments
- Confusion matrix heatmaps for classification evaluation

**Conclusion**

This notebook walks through the process of understanding retail customer behavior using both classification and clustering approaches. The findings show that spending is influenced by a mix of seasonal, demographic, and behavioral factors. These insights can help retailers focus marketing efforts on high-value segments, optimize product offerings, and refine promotional strategies to boost engagement and revenue.
