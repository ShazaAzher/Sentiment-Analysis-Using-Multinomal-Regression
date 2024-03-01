# Twitter Sentiment Analysis Project

## Overview
This project utilizes the Twitter Tweets Sentiment Dataset for sentiment analysis. The goal is to classify tweets as positive, negative, or neutral using multinomial logistic regression.

## Dataset
The Twitter Tweets Sentiment Dataset comprises 27,481 tweets categorized into 8,582 positive tweets, 7,781 negative tweets, and 11,118 neutral tweets. The dataset includes the following columns:

- **textID:** Unique ID of the tweet.
- **text:** Complete text of the tweet.
- **selected_text:** Word or phrase selected from the tweet that expresses the sentiment.
- **sentiment:** Sentiment of the tweet (positive, negative, or neutral).

## Project Scope
For this project, we have selected 6,000 tweets (2,000 from each sentiment class) to keep model training and testing times manageable. The "textID" and "selected_text" columns have been dropped from the dataset for simplicity.

## Dataset File
The modified dataset file is named **Tweets.csv**.

## Methodology
The sentiment analysis will be performed using multinomial logistic regression, a popular classification algorithm for text data.

## Dependencies
- Python 3
- NumPy
- Pandas
- Scikit-learn

## Usage
1. Clone the repository:
```
git clone https://github.com/your-username/twitter-sentiment-analysis.git
```
2. Navigate to the project directory:
```
cd twitter-sentiment-analysis
```
3. Open and execute the notebook **Twitter_Sentiment_Analysis.ipynb**.

## Results
The notebook provides insights into the sentiment analysis results and evaluates the performance of the multinomial logistic regression model.

## Acknowledgments
- Twitter for providing the dataset.
- Contributors to scikit-learn and other libraries used in this project.
