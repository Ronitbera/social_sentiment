# 📌 Social Media Sentiment Analysis — Data Analyst Project

## 👨‍💻 Role: Data Analyst  
## 🛠 Tech Stack: Python, Pandas, Matplotlib, Seaborn, TextBlob, Scikit-learn  

---

## 📖 Project Overview
This project performs sentiment analysis on social media posts from **Twitter** and **Instagram** to understand user opinions, trending topics, and platform-wise sentiment patterns.

Key tasks completed:

- Data Cleaning  
- Exploratory Data Analysis  
- Sentiment Analysis using NLP  
- Keyword Extraction (TF-IDF)  
- Visualization & Insights  
- Recommendations for business decisions  

---

## 🎯 Objectives
- Determine overall sentiment (Positive / Neutral / Negative)  
- Compare sentiment between platforms  
- Identify trending topics  
- Visualize sentiment variation over time  
- Provide insights for marketing & customer teams  

---

## 📂 Dataset Description
The dataset includes **500 social media posts** with the following columns:

| Column | Description |
|--------|-------------|
| post_id | Unique post identifier |
| platform | Twitter / Instagram |
| created_at | Date & time of the post |
| username | User who posted |
| tweet_text | Text content |
| likes | Number of likes |
| retweets | Number of retweets |

---

## 🧹 Data Cleaning Steps
- Removed duplicates  
- Filled missing text values  
- Converted timestamps to datetime format  
- Converted text to lowercase  
- Removed special characters & extra spaces  
- Ensured all text fields are string type  

---

## 🧠 Sentiment Analysis
Sentiment was calculated using **TextBlob**, generating:

- **Polarity Score:** from −1.0 (negative) to +1.0 (positive)  
- **Sentiment Category:**  
  - > 0.1 → Positive  
  - < -0.1 → Negative  
  - Otherwise → Neutral  

---

## 📊 Visualizations

### 1️⃣ Sentiment Distribution  
Pie chart showing positive, neutral, and negative sentiment percentages.

### 2️⃣ Sentiment by Platform  
Stacked bar chart showing sentiment comparison between Twitter and Instagram.

### 3️⃣ Top Keywords (TF-IDF)  
Bar chart showing the top keywords discussed by users.

### 4️⃣ Daily Sentiment Trend  
Line chart showing sentiment polarity changes across days.

---

## 🔍 Key Insights
- Instagram users show **more positive sentiment** than Twitter users.  
- Majority of posts are **Neutral**, indicating factual conversations.  
- Top discussion themes include: **delivery, service, pricing, quality**.  
- Sentiment improves over time, indicating better customer response.  

---

## 📌 Recommendations
- Improve customer support around delivery & service.  
- Increase Instagram engagement campaigns (higher positivity).  
- Track negative sentiment spikes using automated alerts.  
- Convert positive user posts into testimonials.  

---
## 📁 Project Structure

├── dataset.csv
├── analysis.py
├── visuals/
│   ├── sentiment_pie.png
│   ├── sentiment_by_platform.png
│   ├── top_keywords.png
│   └── daily_sentiment_trend.png
└── README.md


## 📁 Project Structure
