# Using AI to generate and Combine Alpha
This project deals with  __Quantative Trading, Generating & Combining alpha for better trading strategies__ .

This project is divided into 3 sections :
1. __NLP on 10k-Financial Statements:__
   - Scraped and Pre-processed 10K-Financial Statements that are the annual reports that publicly traded companies are required to file with the SEC within 60 days of the fiscal year end.
   - Natural Language Processing Analysis on 10-k financial statements to generate an alpha factor.
2. __Analyze Stock Sentiments from StockTwits using Deep Learning:__
    - Built a deep learning model to classify the sentiment of messages from StockTwits (a social network for investors and traders). 
    - Model predicts if any particular message is positive or negative. From this, a signal of the public sentiment for various ticker symbols is generated.
3. __Combining Alpha using Random Forest:__
    - Combined signals on a random forest for enhanced alpha. 
    - While implementing this, solved the problem of overlapping samples.

Dataset
-
Since the project was under Udacity's AI for Trading Nanodegree the dataset was provided by thier partners Quotemedia and Loughran-McDonald sentiment word lists. Moreover, StockTwits and SEC sites were used to fetch data for Stock Sentiment and NLP repectively.

## Installation

```bash
pip install -r requirements.txt
```


## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
