# 📱 Social Media Engagement Analytics using Python

## 📌 Project Overview

- This project analyzes social media engagement data to understand user behavior, content performance, and engagement patterns. Using Python-based data analysis and visualization techniques, the project extracts meaningful insights from a dataset of 5000 social media posts.

- The analysis covers data cleaning, feature engineering, statistical analysis, and both static and interactive visualizations.



## 🎯 Objective

- Identify engagement drivers
- Analyze post performance
- Study user behavior patterns
- Optimize content strategy



## 📊 Dataset Description

- Source: Public dataset (GitHub)
- Total Records: 5000
- Total Features: 20

### Key Columns:

- user_id, age, gender, country
- post_type, post_category
- likes, comments, shares
- watch_time_sec, impression_count
- follower_count, is_verified
- sentiment, hashtags
- engagement_rate



## 🛠 Tools & Technologies

- Python
- Pandas (Data Cleaning & Analysis)
- NumPy (Numerical Operations)
- Matplotlib & Seaborn (Static Visualization)
- Plotly (Interactive Visualization)



## 🔧 Data Cleaning & Preprocessing

- Handled missing values using median (numerical) and mode (categorical)
- Converted date column to datetime format
- Removed inconsistencies and standardized categories
- Created new feature: `hashtag_count`
- Converted data types for better analysis



## 🔄 Feature Engineering

- Created **engagement_score** = likes + comments + shares
- Applied log transformation on engagement metrics
- Extracted date from timestamp for trend analysis



## 📈 Key Analysis Performed

- Engagement comparison by post type and category
- Country-wise impressions and engagement
- Sentiment-based engagement analysis
- Correlation between engagement metrics
- Daily engagement trend analysis
- Device-wise engagement behavior



## 📊 Key Insights

- Posts with higher impressions generally receive more likes
- Engagement varies significantly across post types
- Certain countries show higher average engagement levels
- Positive sentiment posts tend to perform better
- Device type impacts engagement behavior
- Hashtag usage contributes to increased engagement
- Engagement trends fluctuate over time



## 📉 Statistical Analysis

- Calculated mean, median, and mode for engagement metrics
- Analyzed distribution using skewness and kurtosis
- Identified variability using standard deviation and variance



## 📊 Visualizations

### Static Visualizations:

- Scatter Plot (Likes vs Impressions)
- Line Chart (Daily Engagement Trend)
- Bar Chart (Posts by Category)
- Pie Chart (Gender Distribution)
- Histogram (Age Distribution)
- Box Plot (Engagement Rate)

### Advanced Visualizations:

- Seaborn Count Plot
- Violin Plot (Followers vs Sentiment)
- Pair Plot (Feature Relationships)
- Heatmap (Correlation Matrix)
- Swarm Plot (Device vs Engagement)

### Interactive Visualizations:

- Plotly Line Chart (Trend Analysis)
- Plotly Bar Chart (Category Analysis)
- Plotly Bubble Chart (Engagement Insights)
- Interactive Scatter Plot


## 📌 Conclusion

This project demonstrates how Python can be used to analyze large-scale social media data and generate actionable insights. The findings help understand user engagement patterns, optimize content strategy, and improve audience targeting.






