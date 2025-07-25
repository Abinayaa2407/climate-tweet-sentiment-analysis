# Climate Change Tweet Sentiment Analysis

This project analyzes real-time sentiment in tweets related to climate change using classic NLP techniques and machine learning. It was completed as part of the *Applied Artificial Intelligence* module at Sheffield Hallam University.

---

## 📌 Objectives

- Scrape tweets related to climate change using hashtags like `#globalwarming`, `#carbonemission`, etc.
- Clean and normalize text data for NLP tasks
- Build and evaluate sentiment classification models
- Compare vectorization techniques: Count Vectorizer, TF-IDF, Positive/Negative frequency

---

## 🛠️ Tools & Libraries

- Python
- Pandas, NumPy
- NLTK
- Scikit-learn
- Matplotlib, Seaborn
- Apify (for tweet scraping)

---

## 🧠 Methodology

- **Data Collection**: Web scraping with Apify using keyword filters
- **Text Preprocessing**:
  - Tokenization, punctuation removal, stopword filtering
  - Stemming (Porter, Lancaster, Snowball) – compared for impact
- **Vectorization**:
  - CountVectorizer
  - TF-IDF
  - Positive/Negative word frequency scoring
- **Model**: Logistic Regression
- **Evaluation**: Accuracy scores and confusion matrices

---

## 📈 Results

- **Best Accuracy**: ~74% using Count Vectorizer
- TF-IDF scored ~72%, and Pos/Neg frequency ~63%
- Count Vectorizer outperformed despite being a simpler method
- Word clouds and charts revealed public sentiment patterns

---

## 📂 How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/your-username/climate-tweet-sentiment-analysis.git
   cd climate-tweet-sentiment-analysis

2. Install dependencies:
   ```bash
   pip install -r requirements.txt

3. Run the notebook or script:
   ```bash
   jupyter notebook SentimentAnalysis.ipynb
