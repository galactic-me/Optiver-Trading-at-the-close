# Optiver-Trading-at-the-close
Prediction of close prices and analysing stock price movement by studying historical trends using LSTM , Seq2Seq Model

Each trading day on the Nasdaq Stock Exchange concludes with the Nasdaq Closing
Cross auction. This process establishes the official closing prices for securities listed
on the exchange. These closing prices serve as key indicators for investors, analysts
and other market participants in evaluating the performance of individual securities
and the market as a whole. Almost 10% of Nasdaq’s average daily volume occurs in
the closing auction. Providing true price and size discovery, the closing auction
determines benchmark pricing for index funds and other investment strategies.
In the last ten minutes of the Nasdaq exchange trading session, market makers like
Optiver merge traditional order book trading with price auction data. This ability to
consolidate information from both sources is critical for providing the best prices to
all market participants.

A CLOSER LOOK AT THE TERMINOLOGIES:
Auction
Order book
Auction order book
Combined book

Model Training:
A simple baseline is to assume we have no valuable information about the direction
any stock moves, which translates to a predicted value of 0 for all observations. This
baseline is quite hard to beat in the context of financial markets

Model Evaluation:
Our evaluation metric is Mean Absolute Error (MAE).
