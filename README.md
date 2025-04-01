# 📊 DeepSeek Twitter Analysis

![DeepSeek AI](https://upload.wikimedia.org/wikipedia/commons/thumb/e/ec/DeepSeek_logo.svg/768px-DeepSeek_logo.svg.png)

## 🔍 Overview
This project analyzes **364K tweets** related to **DeepSeek AI** using **Natural Language Processing (NLP) and Latent Dirichlet Allocation (LDA) topic modeling**. The focus is on **English tweets (205K rows)**, engagement metrics, sentiment trends, and key topics.

## 🚀 Features
- **Text Preprocessing**: Tokenization, lemmatization, stopword removal.
- **Data Cleaning**: Standardized `snake_case`, filled missing `author_location` as 'Unknown'.
- **Outlier Removal**: Removed tweets with **zero views**.
- **Topic Modeling**: LDA reveals discussions on **ethics, GPUs, stocks**, and more.
- **Sentiment Analysis**: Understand user perception.
- **Engagement Metrics**: Analyze likes, retweets, and replies.
- **Predictive Modeling**: Identify viral tweets while normalizing skewed data.
- **Data Visualization**: Trends, engagement distribution, and hashtag networks.

## 📂 Dataset
- **Total Tweets**: 364K
- **Filtered English Tweets**: 205K
- **Columns**: `tweet_id`, `author`, `text`, `date`, `likes`, `retweets`, `views`, `author_location`, etc.

## 🛠 Tech Stack
- **Python** 🐍 (pandas, NumPy, scikit-learn, NLTK, spaCy)
- **NLP** 🧠 (TextBlob, Vader Sentiment)
- **Topic Modeling** 📚 (LDA, Gensim)
- **Data Viz** 📊 (Matplotlib, Seaborn, Plotly, WordCloud)

## 📈 Key Insights
- Ethical concerns and AI advancements dominate discussions.
- High engagement correlates with **specific hashtags and mentions**.
- Stock-related tweets tend to be **highly viral**.
- Tweets from **influencers & verified accounts** perform better.

## 📌 Installation & Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/deepseek-twitter-analysis.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the main script:
   ```bash
   python analysis.py
   ```

## 📊 Visualizations
![Engagement Trends](https://www.aimtechnologies.co/wp-content/uploads/2023/06/Social-Sentiment-Tracking.png)

## 📝 Future Work
- Implement **BERT-based** sentiment classification.
- Expand topic modeling to **real-time Twitter data**.
- Fine-tune **predictive models** for better accuracy.

## 🤝 Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request.

## 📜 License
MIT License © 2025 Your Name

---
⭐ **If you found this useful, please star this repo!** ⭐

