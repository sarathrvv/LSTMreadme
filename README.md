# Stock price prediction using ML
# # //Introduction
The project&#39;s purpose is to forecast future price fluctuations for a certain stock. Prices from
previous days, as well as financial news articles relevant to the company of interest, are used to
produce these predictions. Given insufficient information, price swings arising from a mixed
reaction of general market attitude, the company&#39;s financial news, the company&#39;s and the
industry&#39;s future prospects, and occasionally murmurs concerning the company&#39;s previous
performance are difficult to rationalize correctly. In order to predict future stock prices using
past prices and news headlines, a number of supervised learning algorithms were investigated.
This concept is based on the observation that stock prices frequently rebound after huge losses
or self-correct after successive increases, and that unexpected news or analyst remarks
frequently have a significant impact on stock prices.
# # # //Dataset and visualizations
10 years dataset of the everyday stock prices were used in this project. The company chosen
was Apple. The chart below shows a simple visualization of the data after the cleaning and
preprocessing is done.
We also obtained news headline data for Apple stock prices in order to assess the utility of
financial news in properly forecasting stock prices. Because the news data was noisy, several
preprocessing processes were required to remove duplicates, create the dictionary, and match
the news data to price movements on specified days.
# # # # //Results
The LSTM model yielded a loss of " " percent. This model&#39;s training and test errors
were both large, indicating that it will almost certainly never be competent enough to forecast
stock prices. This also implies that the algorithm detects little pattern in the next day&#39;s price
change in comparison to the previous day&#39;s price change. This reflects the fact that the stock
market is far more complicated than a straight line.
