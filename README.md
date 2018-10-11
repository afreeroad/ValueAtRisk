# ValueAtRisk
Value-at-Risk

The included jupyter notebook describes an example of calculating value at risk for a given portfolio for a given, single asset such as the S&P 500. The user provides basic information such as the Asset (ticker symbol), the Years of historical data you wish to use, the Expected Percent Change that you want to measure, and the Value of the Portfolio you are estimating on.

The Python code retrieves asset data for a given number of years from IEX, using pandas datareader. It gives the option to export the data retrieved to a csv on a local machine titled "modified_data.csv".

The retrieved data has been modified to include the percentage change from day to day. A distribution of these percentage changes are then analyzed to compute the value at risk.

Two figures are provided, a histogram and gaussian curve, to help visualize the distribution of the percent daily change. A single vertical line is shown on the gaussian curve to distinguish the location on the distribution of the expected percent change.

In conclusion, a quantitative analysis of value-at-risk is given, along with the expected 1% risk of the portfolio in relation to the asset.
