# Food Delivery Reviews Sentiment Analysis

This project performs **sentiment analysis** on customer reviews for a food delivery service. It classifies reviews into **Positive**, **Negative**, or **Neutral**, visualizes the distribution, and provides actionable business recommendations.

---

## 📝 Project Overview

- A Bengaluru-based food delivery startup wants to test its **analytics workflow** before applying it to real customer reviews.
- The workflow:
  1. Loads review data from an Excel file.
  2. Performs sentiment analysis using **TextBlob**.
  3. Categorizes reviews into `Positive`, `Negative`, or `Neutral`.
  4. Generates **pie chart** and **bar chart** visualizations.
  5. Provides **business recommendations** based on sentiment trends.

---

## 📂 Project Files

- `food_reviews.xlsx` – Sample dataset of 1000 customer reviews.
- `sentiment_analysis.py` – Python script to perform sentiment analysis and save results.
- `reviews_sentiment.xlsx` – Output file containing sentiment scores and categories.
- `visualizations.py` – Python script to visualize sentiment distribution.

---

## ⚙️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/food-reviews-sentiment.git
| Review_Text                         | sentiment_score | sentiment_category |
| ----------------------------------- | --------------- | ------------------ |
| Excellent taste and quick delivery. | 0.6667          | Positive           |
| The food arrived cold and late.     | -0.45           | Negative           |
| Bad experience, food was tasteless. | -0.65           | Negative           |
Sentiment distribution example:

Positive: 588

Negative: 373

Neutral: 39

Business Recommendation:

Majority of customers are happy. Maintain quality and expand services.Visualizations

Pie chart – Percentage of Positive, Negative, and Neutral reviews.

Bar chart – Count of reviews in each sentiment category.

🔧 Tools & Libraries Used

Python 3

Pandas – Data manipulation

Openpyxl – Excel file handling

TextBlob – Sentiment analysis

Matplotlib – Data visualization

📈 Business Insights

Positive reviews indicate customer satisfaction and loyalty.

Negative reviews highlight areas for improvement: delivery speed, food freshness, and packaging.

Neutral reviews indicate opportunities for engagement and unique offerings.

📚 References

TextBlob Documentation

Matplotlib Documentation

Pandas Documentation
