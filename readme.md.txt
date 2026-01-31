# Amazon Fine Food Reviews – SQLite Project

## 📌 Overview
This project analyzes Amazon fine food reviews using SQLite
to understand customer ratings, review sentiment, and product popularity.

## 🛠 Tools
- SQLite
- GitHub

## 📂 Dataset
- Amazon Fine Food Reviews (Cleaned)

## 🔍 Analysis Performed
- Total number of reviews
- Average rating
- Rating distribution
- Top reviewed products
- Sentiment classification using ratings

## 📊 Example Query
```sql
SELECT score, COUNT(*)
FROM reviews
GROUP BY score;

*************The Excel/CSV file is not uploaded because its size exceeds GitHub’s 25 MB limit.*****************