# Pairs_Trading_Strategy_Model
The purpose of this code is to implement a pairs trading strategy between Nifty and Bank Nifty to obtain maximum profit. 

Pairs trading is a popular trading strategy that involves identifying two correlated assets and taking positions based on the relative price movements between them. The strategy assumes that the prices of the two assets will converge over time, even if they deviate from their typical relationship in the short term. Pairs trading seeks to profit from the price spread between the two assets by taking long and short positions simultaneously.

In this code, the assets being considered are Nifty and Bank Nifty. Nifty and Bank Nifty are two popular indices in the Indian stock market. Nifty represents the top 50 stocks on the National Stock Exchange (NSE), while Bank Nifty represents the banking sector stocks in the NSE. These two indices are highly correlated, given the significant influence of the banking sector on the overall market.

The code processes historical price data of Nifty and Bank Nifty, calculates the spread (the logarithmic difference) between their prices, and generates Z-scores to identify entry and exit signals for long and short positions. The Z-scores help identify instances where the spread deviates significantly from its mean, indicating potential trading opportunities.

The code then executes the pairs trading strategy by tracking entry and exit points based on specific Z-score thresholds. It calculates the profit or loss for each trade and maintains a cumulative PNL (profit and loss) to track the overall profitability of the strategy. Additionally, the code performs rolling mean calculations and displays the Z-score DataFrame, PNL DataFrame, and cumulative PNL graph to visualize the strategy's performance.

Overall, this code is a simplified implementation of a pairs trading strategy between Nifty and Bank Nifty, aiming to identify profit opportunities based on the relative price movements of these two indices.
