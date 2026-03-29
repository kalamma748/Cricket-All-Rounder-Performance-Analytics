# 🏏 Cricket All-Rounder Analytics & Performance Prediction

A complete end-to-end **Data Science & Machine Learning project** that analyzes cricket all-rounder performance using data scraped from ESPN Cricinfo, builds a predictive model using Random Forest, and visualizes insights through an interactive Power BI dashboard.

---

## 📌 Project Overview

Evaluating cricket all-rounders is complex because they contribute in both **batting and bowling**. This project builds a **data-driven performance scoring system** and predicts player performance using machine learning.

## 🎯 Objectives

- Scrape real-world cricket data from ESPN Cricinfo
- Clean and preprocess raw data
- Perform Exploratory Data Analysis (EDA)
- Build a **Random Forest Machine Learning model**
- Predict all-rounder performance scores
- Create an **interactive Power BI dashboard**

## 🔍 Data Source

- ESPN Cricinfo Stats  
- Data includes:
  - Player Name
  - Matches
  - Runs
  - Batting Average
  - Wickets
  - Bowling Average
  - Centuries
  - 5-wicket hauls
  - Fielding stats

## 🧹 Data Cleaning & Preprocessing

- Replaced missing values (`-`) with NaN  
- Converted columns to numeric types  
- Removed invalid rows  
- Feature engineering: 
  - Average difference  
  - Performance score  

## 📊 Exploratory Data Analysis (EDA)

Key insights:

- Strong correlation between **Runs & Centuries**
- Strong relationship between **Wickets & 5W hauls**
- Performance score depends on:
  - Batting average  
  - Bowling average  

Visualizations:
- Histograms  
- Scatter plots  
- Correlation heatmap  

## 🤖 Machine Learning Model

Model used: **Random Forest Regressor**

### Features
- Batting Average  
- Bowling Average  
- Runs per Match  
- Wickets per Match  
- Total Runs  
- Total Wickets  

### Target
- Performance Score  

## 📈 Model Performance

| Metric | Value |
|------|------|
| R² Score | 0.99 |
| RMSE | ~2.8 |

✅ High accuracy model with excellent prediction capability.

## 📊 Power BI Dashboard

Interactive dashboard includes:

- KPI Cards (Total Players, Avg Stats)
- Top 10 All-Rounders Ranking
- Runs vs Wickets Analysis
- Batting Average Distribution
- Correlation Heatmap
- Player Comparison

## 🚀 Technologies Used

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- Web Scraping (BeautifulSoup, Requests)  
- Power BI  


