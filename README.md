# Subreddit Literacy Analysis and Recommendation

This project explores literacy patterns across 10 diverse Reddit communities using linguistic features such as Flesch-Kincaid reading grade level, word count, and average word length. We perform statistical analysis and build a machine learning recommendation engine that suggests suitable subreddits for user comments.

## 🔍 Project Overview

- **Goal**: Analyze literacy levels across subreddits and predict subreddit suitability for a given comment.
- **Data**: Scraped 50,000 comments using the PRAW Reddit API from 10 subreddits.
- **Features**:
  - Flesch-Kincaid Grade Level
  - Word Count
  - Average Word Length
  - Comment Length

## 📊 Methods

- **Preprocessing**: Tokenization, stopword removal, feature engineering.
- **Statistical Analysis**: ANOVA, Tukey's HSD for comparing subreddit means.
- **Modeling**: Random Forest Classifier with GridSearchCV tuning.
- **Recommendation Engine**: Suggests top subreddits for a user comment based on predicted literacy fit.

## 📈 Results

- Academic subreddits (e.g., r/AskAcademia, r/science) scored highest in literacy.
- Meme and youth-focused subreddits (e.g., r/teenagers, r/dankmemes) scored lowest.
- Recommendation engine achieved ~25% accuracy (vs. 10% random baseline).

## 📦 Technologies Used

- Python (Pandas, NumPy, Scikit-learn, TextStat)
- PRAW for Reddit API
- Seaborn & Matplotlib for Visualization
- Statsmodels for ANOVA / Tukey HSD

## 🚀 How to Run

1. Clone the repo  
   `git clone https://github.com/yourusername/reddit-literacy-insights.git`
2. Install dependencies  
   `pip install -r requirements.txt`
3. Run the notebook  
   `jupyter notebook RedditLiteracyAnalysis.ipynb`

## 🤝 Contributors

- Prati Jain 
- Bala Mahendra Pothabathula 
- Robert Malloy   
- Sai Phani Krishna Arumalla 


