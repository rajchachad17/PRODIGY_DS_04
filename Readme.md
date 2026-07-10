# PRODIGY_DS_04

## Objective
Analyze and visualize sentiment patterns in social media data to understand public opinion and attitudes toward specific brands, games, and companies, using the Twitter Entity Sentiment dataset.

---

## 📁 Project Structure

```
PRODIGY_DS_04/
│
├── twitter_training.csv                          # Dataset
├── Task_04.ipynb                                 # Main Python notebook
├── assets/                                       # Exported chart images
└── README.md
```

---

## 📂 Dataset

**Source:** Kaggle

**Dataset Link:** https://www.kaggle.com/datasets/jp797498e/twitter-entity-sentiment-analysis

---

## Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- WordCloud
- Jupyter Notebook

---

## Key Tasks Performed
- Loaded and explored the Twitter Entity Sentiment dataset (74,682 tweets across 32 entities, 4 sentiment classes)
- Cleaned the data: dropped rows with missing tweet text and removed exact duplicate rows
- Visualized overall sentiment distribution across Positive, Negative, Neutral, and Irrelevant classes (bar + pie chart)
- Compared sentiment mix across the top 12 most-discussed entities using a 100%-stacked bar chart
- Engineered a custom Net Sentiment Score — `(Positive − Negative) / Total` — to rank all 32 entities by public reception
- Analyzed tweet length distribution by sentiment class (KDE plot)
- Cleaned tweet text (handled contractions, mentions, links, dataset artifacts) and generated word clouds for Positive vs. Negative tweets
- Summarized key insights: which brands/games were received most positively and negatively, and what patterns distinguish positive from negative tweets

---

**Rajvardhan Chachad**  
GitHub: [@rajchachad17](https://github.com/rajchachad17)
