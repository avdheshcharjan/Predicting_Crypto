# Predicting Cryptocurrency Prices

## About

This is our Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) which aims to predict cryptocurrency prices of popular cryptocurrencies, scraping data from Yahoo-Finance

## Contributors

- @NotAnAddictz - Data Extraction, Tensorflow, FbProphet
- @weix1233 - FbProphet, Tensorflow
- @avdheshcharjan - Data Visualisation, Data Extraction, FbProphet

## Main Packages Used

- pandas_datareader
- fbprophet
- matplotlib
- tensorflow
- seaborn
- sklearn

## Datasets Used (Scraped from Yahoo Finances)

- AAVE (AAVE)
- BinanceCoin (BNB)
- Bitcoin (BTC)
- ChainLink (LINK)
- Cardano (ADA)
- Ethereum (ETH)
- Solana (SOL)
- Tether (USDT)
- Uniswap (UNI1)

## Defining the Problem

- Are we able to accurately predict the future prices of the various cryptocurrencies?
- Which machine-learning model is more accurate in their prediction?

## Models Used

- Tensorflow LSTM
- FbProphet

## Conclusion

- Changes in cryptocurrency prices are not reliant on other cryptocurrencies
- Cryptocurrencies are generally predictable as long as there is no sudden changes that affects their prices significantly
- Future prediction will have a wider range the further one predicts
- Having a larger (and more recent) dataset will result in higher prediction accuracy
- FbProphet seems to be clearer and more accurate in predicting various cryptocurrencies

## What did we learn

- Scraping datasets using pandas datareader
- FbProphet and its implementation
- Neural Networks, Keras and Tensorflow
- Data Visualisation

## References
- https://github.com/rohan-paul/Cryptocurrency-Kaggle
- https://towardsdatascience.com/cryptocurrency-price-prediction-using-lstms-tensorflow-for-hackers-part-iii-264fcdbccd3f
- https://facebook.github.io/prophet/docs/quick_start.html
