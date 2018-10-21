# Optimize-momentum-strategy-with-52-week-high
## Introduction
This project aims to optimize momentum trading strategy with 52-week high. As we all know that momentum strategy means 
stock turns exhibit momentum behavior at intermediate horizons. Selling losers and buying winners can help us make profits. 
However, there two problems, one is what kind of past returns can best describe the future returns, past daily return, past monthly returns or other? The other one is that long-term reversal will occur after the momentum.

So in this project a optimization is made for momentum strategy. We developed a series of new momentum trading strategies based on the ratio of the current stock price to each of five different reference points in past prices: 52-week high, 52-week median, 52-week
low, half-year high, and 2-year high and then measure their performance. Finally, 52-week high price strategy results in stronger
investment performance than several others.

## Data
I downloaded the 505 stocks daily data in S&P 500 index from 2004 to 2016 from Bloomberg. All stock prices are adjusted for stock splits or stock dividends. And, the stock has at least one full year of daily price data.

## Methodology
Then I ranked the eligible stocks based on the ratio of current stock price to each one of the five past reference prices: 52-week high price, 52-week median price, 52-week low price, half-year high price, and 2-year high price. 

Then I formed three equally-weighted portfolios. The top 30% of the ranked stocks are placed in the top (ratio) portfolio, and the bottom 30% of the ranked stocks are placed in the bottom (ratio) portfolio. The middle (ratio) portfolio includes the remaining 40% of the stocks. All portfolios are held for 6 months and calculate the performance

## Reference
George TJ, Hwang CY (2004) [The 52-week high and momentum investing. J Financ]
