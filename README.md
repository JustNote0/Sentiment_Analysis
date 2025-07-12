# 🎬 Sentiment_Analysis — IMDb Review Analyzer

Interactive web application built with **Streamlit**, With just one URL input, this app scrapes the reviews uses asynchronous web scraping **(aiohttp + BeautifulSoup)**, analyzes the sentiment using **TextBlob**, and turns the results into a clean visual report.

---

## 📌 Project Features

- 🔍 **Web Scraping**: Automatically pulls user reviews from a given IMDb movie review page.
- 🧹 **Text Preprocessing**: Cleans text with stopword removal, lemmatization, and normalization.
- 🧠 **Sentiment Analysis**: Uses polarity scoring to classify reviews as Positive, Neutral, or Negative.
- 📊 **Data Visualization**: Pie chart showing sentiment distribution.
- 💾 **Downloadable Outputs**: Export processed reviews as CSV and download sentiment chart as PNG.

---

🗂️ Folder & File Overview

```bash
Sentiment_Analysis/
│
├── app.py              # Main app logic (Streamlit)
├── requirements.txt    # Python libraries
├── packages.txt        # Alternative package list
└── README.md           # Project documentation
```

---

## 🚀 How to Run the App Locally

### 1. Clone this repository

```bash
git clone https://github.com/JustNote0/Sentiment_Analysis.git
cd Sentiment_Analysis
```

### 2. Install the required packages

```bash
pip install -r requirements.txt
```

### 3. Run the app

```bash
streamlit run app.py
```

