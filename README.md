# Sentiment Analysis on Tweets  

This project was created as part of an internship application. It demonstrates how Natural Language Processing (NLP) techniques can be used for **sentiment analysis** of tweets. The goal is to classify tweets as **positive** or **negative** using supervised machine learning models.  

## Project Overview  
- Dataset: [NLTK twitter_samples corpus](https://www.nltk.org/howto/twitter.html) (5,000 positive and 5,000 negative tweets).  
- Preprocessing steps: URL removal, punctuation removal, tokenization, stopword removal, and stemming.  
- Feature extraction: **TF-IDF Vectorization**.  
- Models tested: Logistic Regression, Naïve Bayes, Support Vector Machine (SVM), and XGBoost.  
- Best Model: **Logistic Regression** with ~75% accuracy.  
- Deliverables:  
  - Python Notebook (`Fatbardh_Fetoshi_Sentiment_Tweet_Project.ipynb`)  
  - Report (`Sentiment_Project_Report_Fatbardh_Fetoshi.docx`)  

## Repository Structure  
.
├── Fatbardh_Fetoshi_Sentiment_Tweet_Project.ipynb   # Jupyter notebook with code
├── Sentiment_Project_Report_Fatbardh_Fetoshi.docx   # Detailed project report
└── README.md                                        # Project overview and instructions

## How to Run  

1. Clone this repository:
   ```bash
   git clone https://github.com/BardhiFetoshi/sentiment-analysis-tweets.git
   cd sentiment-analysis-tweets
   ```

2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook Fatbardh_Fetoshi_Sentiment_Tweet_Project.ipynb
   ```

4. (Optional) Use the saved model:
   - The Logistic Regression model and TF-IDF vectorizer are saved as `sentiment_model.pkl` and `tfidf_vectorizer.pkl`.  
   - You can load them in Python to classify new tweets.

## Results  
- **Best Model**: Logistic Regression (~75% accuracy).  
- Balanced performance across positive and negative tweets.  
- Lightweight and effective for tweet-level sentiment classification.  

## References  
- Dataset: [NLTK twitter_samples](https://www.nltk.org/howto/twitter.html)  
