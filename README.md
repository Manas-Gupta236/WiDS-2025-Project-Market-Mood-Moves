# WiDS 2025 – Market Mood and Moves

This repository contains the code files and report developed and resources provided as part of the WiDS 2025 Market Mood and Moves project.

## Structure of repository: 
- `week1/` – It has 6 jupyter notebooks which includes basic Python programming, market data extraction and handling/processing and sentiment analysis foundations. It also has a csv file with the stock data. 
- `week2/` – It has a jupyter notebook dealing with addressing long text due to token truncation limit.
- `week3/` - It has 7 jupyter notebooks and 3 csv files. These include time series analysis in stock price prediction and final code snippet integration to make the final model using LSTM. 
- `Mid Term Report/` – This 5-page report outlines the theoretical knowledge gained in the first two weeks of the project.
- `End Term Report/` – This 10-page report outlines the theoretical knowledge gained in the entire duration of the project which is essentially:
 1. data collection, i.e, acquiring news articles and social media posts about target companies using APIs
  2. sentiment analysis where we apply Natural Language Processing models (like FinBERT) to extract positive or negative signals.
  3. Markets must be modeled as sequences, not isolated points as price today only makes sense in the context of past prices, trends and momentum, which is why RNNs/LSTMs are needed instead of standard ML models.
  4. Combining time-aware models with sentiment creates stronger signals- LSTMs capture temporal price patterns, while FinBERT sentiment acts as a leading indicator, together enabling more reliable buy/sell decisions.
     
Resources provided also had several challenges, codes of which were provided, understood and implemented.

- `week 1 reading, week 2 reading and week 2 reading/` are reference PDFs provided during the project in the three weeks.



