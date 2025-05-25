# ✈️ Sentiment Analysis of Tweets about US Airlines

This project is a **Streamlit dashboard** that performs **sentiment analysis** on tweets related to major US airlines. The app provides interactive visualizations and insights based on tweet data, allowing users to explore how people feel about different airlines on Twitter.

---

## 🔍 Features

- **Random Tweet Display**: View a random tweet filtered by sentiment (positive, neutral, negative).
- **Sentiment Distribution**: Visualize tweet sentiments using histograms or pie charts.
- **Tweet Location by Hour**: Map where tweets were sent from based on the time of day.
- **Airline-Specific Sentiment Breakdown**: Compare sentiments across different airlines.
- **Word Cloud**: Generate a word cloud of frequent terms for each sentiment type.

---

## 📁 Dataset

The app uses a dataset named `Tweets.csv`, which should include:
- `airline_sentiment`: The sentiment label (positive, neutral, negative)
- `tweet_created`: Timestamp of the tweet
- `airline`: Airline name
- `text`: Content of the tweet

Make sure `Tweets.csv` is in the root folder of your project.

---

**Clone the repo**
```bash
git clone https://github.com/lumi62/Interactive-Dashboard-with-Streamlit-Python
cd Interactive-Dashboard-with-Streamlit-Python

