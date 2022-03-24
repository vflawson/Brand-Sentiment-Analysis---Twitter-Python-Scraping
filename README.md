# Brand-Sentiment-Analysis---Twitter-Python-Scraping
Twitter tweet scraping for the purposes of brand sentiment analysis

Twitter data scraped without using the Twitter API.

This code allows you to first selection a location (lat & long) and radius of search size. Selecting a keyword, such as "Toyota", will find the tweets that 
contain the word/hashtag in the body of the text.

In addition to the body of the tweet, I also am grabbing the user location, handle, display name, and time of the tweet.

To aid the end goal of NLP-based brand sentiment analysis, I also use the langdetect package to detect the language of the tweet. Additionally,
I removed tweets from the brand's official Twitter handle in order to avoid a positive bias in terms of sentiment.
