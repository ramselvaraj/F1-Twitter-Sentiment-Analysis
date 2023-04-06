# Sentiment Analysis on F1 Twitter's Reaction to controversial 2021 Driver's Championship won by Max Verstappen

This project involved scraping and cleaning tweets related to Max Verstappen's win at the Abu Dhabi 2021 Grand Prix and 2021 Driver's Title, and performing sentiment analysis on the resulting dataset. 

## Files

- `replies.csv` - Final dataset built by scraping and cleaning tweets
- `F1TwitterScrape.ipynb` - Scraping for tweets using Tweepy library and Twitter API
- `F1TwitterSentimentAnalysis.ipynb` - Performing sentiment analysis on the dataset; building our own classifiers to see which performs better.
- `LSTMModel.pkl` - LSTM model trained on Sentiment140 Dataset

## Methodology

We used a combination of Python libraries such as Tweepy, Pandas, and NLTK for data scraping, cleaning, and preprocessing. We then trained and tested an LSTM model for sentiment analysis, Finally, we used the best performing classifier to analyze the sentiment of tweets related to Max Verstappen's win.

## Results

The results of our sentiment analysis showed that the majority of tweets related to Max Verstappen's win had a positive sentiment, despite the controversy surrounding the race. Our best performing classifier was an LSTM model trained on the Sentiment140 dataset, which achieved an accuracy of 78%.

## Conclusion

Overall, our project demonstrated the effectiveness of sentiment analysis in understanding public opinion on a particular event or topic. We were able to gain insights into the sentiment of F1 fans towards Max Verstappen's win at the Abu Dhabi 2021 Grand Prix.
