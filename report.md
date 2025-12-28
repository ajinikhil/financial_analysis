# **AAPL (Apple Inc.) Stock Analysis Report**

## **Introduction**

This report analyzes the characteristics of Apple Inc. (AAPL) by analyzing the historical stock price behavior from 2020 to 2025. The report focuses on trend analysis, cumulative returns, closing price trend and volatility analysis to evaluate both risk and performance.

## **About the Dataset**

The dataset `2020-2025 Apple Stock Dataset` by `Saman Fatima` is downloaded from Kaggle, contains daily historical stock price data for Apple Inc. (AAPL), it includes variables like opening and closing prices, highest and lowest prices of the day and trading volume. 

For some analysis, daily data was converted to weekly frequency to reduce the noise. 

## **Methodology**

This analysis was performed using Python and used libraries like Pandas for the data analysis and matplotlib for data visualization. The dataset was a CSV file which contains daily historical stock price data for Apple Inc. (AAPL).

The column `Date` was converted to datetime format to enable time series operations. `Closing prices` were converted to numeric values for accurate calculations. Daily data was resampled to a weekly frequency by selecting the last trading day of each week.

Weekly returns were calculated by taking the percentage change in weekly closing price. Cumulative returns were calculated to represent the growth of the investment. Daily closing prices were illustrated to provide an understanding of price movements. 

`Standard deviation` of daily returns is used to calculate `volatility`

## **Closing Price Trend**

The closing price was plotted to observe the overall closing price movement and trends

__Observations:__
* The stock (AAPL) shows an upward trend over the period, which indicates a positive performance. Over the years there were some short-term fluctuations especially during the period of mid 2022 to 2023 and during 2025. 


![Closing price trend plot](Assets/closing_price_trend.png)

___fig:1.0 Closing Price Trend___

## **Trend Analysis: 10 Week Moving Average (MA)**

The weekly closing price of AAPL is analyzed with the 10-week Moving Average (MA). The MA helped to reduce the noise in weekly price. From 2020 onward the AAPL shows an upward trend with the weekly closing price and moving average increasing over time. This trend indicates growth despite some short-term volatility

__Observations:__

![Trend Analysis plot](Assets/weekly_price_trend(MA).png)

___fig:2.0 Trend analysis of 10 Week moving average___

## **Cumulative Returns**

__Observations:__

The cumulative returns graph illustrates the growth of $1 initial investment over the analysis period.

Overall, the cumulative return trend shows a steady growth from 2020 onward, which indicates a strong overall growth despite the short-term volatility. By early 2022 the $1 investment has already grown significantly (more than double the initial investment), which is followed by noticeable drawdowns during mid 2022.

From 2023 to 2024 the cumulative returns shows an overall upward trajectory and reaches a peak in early 2025 which is followed by a decline. Despite the decline the cumulative return remains well above the initial investment level.



![Cumulative Returns](Assets/cumulative_returns.png)

___fig:3.0 Cumulative Returns___

## **Conclusion**

This report analyzes the historical price behavior of Apple Inc. (AAPL) from 2020 to 2025 using closing price trends, trend analysis and cumulative returns. This analysis showed a long term upward trend in the stock price.