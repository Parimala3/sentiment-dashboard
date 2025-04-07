# sentiment-dashboard
Interactive Sentiment Analysis Dashboard using Streamlit
# 📊 Social Media Sentiment Analyzer Dashboard

An interactive Streamlit-based dashboard for analyzing sentiment from social media text data (tweets, posts, comments). Upload your own dataset or explore pre-analyzed data visually.

---

## 📌 Features

- 📂 Upload custom CSV files
- 🧹 Clean and process text data
- 🧠 Classify sentiment using TextBlob
- 📊 Visualize sentiment distribution
- ☁️ Generate WordCloud from text
- 📈 Analyze trends over time (if date column available)
- 💬 Filter posts by sentiment

---

## 🚀 Live Demo

Try it now: [https://yourusername.streamlit.app](https://yourusername.streamlit.app)

---

## 🧠 How It Works

1. Upload a CSV file with a column containing text data
2. The app cleans the text (removes links, symbols, etc.)
3. Sentiment analysis is performed using TextBlob
4. Visual insights are shown with charts and WordClouds

---

## 🛠 Tech Stack

| Layer         | Tools Used                         |
|---------------|------------------------------------|
| 🧠 Sentiment   | `TextBlob`, `Pandas`, `NLTK`        |
| 📊 Visualization | `Matplotlib`, `Seaborn`, `WordCloud` |
| 🌐 Frontend    | `Streamlit`                        |
| 🗃 Data        | CSV files (sample & uploadable)    |

---

## 🗂 Sample Dataset Format

| text                        | date       |
|-----------------------------|------------|
| "I love this product!"      | 2024-06-01 |
| "Worst service ever 😤"     | 2024-06-02 |

---

## 📥 Run Locally

```bash
git clone https://github.com/yourusername/sentiment-dashboard.git
cd sentiment-dashboard
pip install -r requirements.txt
streamlit run app.py
