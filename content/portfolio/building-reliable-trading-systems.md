---
title: 'Building Reliable Trading Systems'
date: '2020-01-11'
slug: building-reliable-trading-systems
categories:
  - Development
tags:
  - trading
image: 'img/portfolio/sun-shoes.jpg'
showonlyimage: no
weight: 1
output: 
  html_document:
    number_sections: TRUE
---

This book written by Keith Fitschen provides a lot of chart examples. I hope this can help me get used to reading charts and forming insights to action. This book will serve as perfect complement to other projects. 
<!--more-->

To trade successfully, I need to know more than using R to work with data. I need a trading system. There are many books and websites promise to deliver a profitable trading system. The truth is that it is difficult for a beginner like myself to determine who is the truth-teller. Maybe it is not easy even for veterans, based on what I have gathered in forums and comment sections. Then, I have stumbled upon this book "Building Trading Systems" by Keith Fitchen through the library.

After researching the reviews online, I have got a good feeling about "Building a Trading System". 
>One of the best systematic trading books out there   
I have read many systematic trading books but I recommend this one above all of them. The author shows absolutely mind blowing equity curves with strategies so simple, and hundreds or thousands of trades per strategy, that overfitting seems very very unlikely. Those equity curves look better than in any other book I have ever seen. If you aren't satisfied with this book i don't know what on earth can satisfy you.   
>- Verified Purchaser, September 9, 2018   

## The Author - Keith Fitchen
Keith Fitchen is the creator of three very successful systems: Aberration, Aztec, I-Master and the president of TradeSystem, Inc. He is recognized as one of the most dedicated professional technical analysts in the financial industry.

### Insights
>The first pitfall in trading is greed. To address that is to establish max drawdown, average annual max drawdown, and the longest time between equity highs.   
>The greatest pitfall is the danger of curving-fitting. Using too few trades in the development samples, the developed trading system would be curve-fitted. It results in developing a trading system that won't perform as well it back-tests.
>Most strategies fail because they are overly curve-fitted.
>The goal of a trading system is one that its return averages more per year than its biggest draw-down. I must be able to trade through the drawdowns in order to realize returns.
>Draw-dwon is not a function of return.

*****

## What is a Tradable Strategy?
In order to trade profitably, one must be able to survive each trading day. Staying alive means having the discipline to follow a proven trading system in order to manage through the risk in the form of drawdown to realize the return.

### Trade System Characteristics
* Normal return/draw-down: These are the risk/reward I experience most of the time.
* Max draw-down: This is the worst-case benchmark I will have to trade through over an extended period of time, in the last 5 or 10 years.
* Longest time between equity highs: This is the longest time I will go before hitting a new equity high.
* Average annual max draw-down

### Performance Objectives
1. Average annual return is greater than max draw-down over at least a 5-year period.
2. Average annual return must be a multiple of the average annual max draw-down.
3. Max draw-down I can tolerate.

### Trend Trading Tenets
* I am not going to make 100 percent each year.
* Return and Risk are often correlated. Aimming for a relative high return comes with a relative high draw-down. The the same relation for the lower return.
* Exceptional returns might have to carry my performance for years.
* Trading for real means going through periods without any gains.
* Best traders average less than 30 percent a year.
* Best traders experience a max draw-down every five-year that is only a few percent less than their average return.

*****

## Developing a Strategy So It Trades Like it Back-Test
**Step 1: Define the risk/reward balance I can live with**
**Step 2: Develop a strategy that trades as well as it back-tests**

Developing a strategy involves testing ideas against historical data to see if the idea is profitable. During the development of strategy, no one has the infinite data pool but instead the small subset of the historical data to test the idea to see if it would be profitable in the future. 

### Curve-Fitting
According to the author, curve-fitting can be defined as the following:
>Either the overuse of trading rules, parameters, filters, stops, and so forth when developing a trading strategy on a relatively large body of data, or the proper use of rules, filters, and so on on a relatively small body of data.   

**Example:** Swiss Franc during the 1980s
**Parameter:** Moving Average. 
**Idea:** If today's n-day average is higher than yesterday's, the trend is up so I buy one contract. I hold that position until today's n-day average is less than yesterday's. When that happens, I exit my long posiition and go short. It is called a *reversal system*. I always have a position and that position alternates from long to short to long. The breakout in the table below shows the results when the n-day average is varied from 10 days to 100 days in 10-day increments.

|     # Days     |     Winning Trads     |     Losing Trades     |     Profit | Profit/Trade     |
|--------        |:-------------:|:-------------:|:------:|-------------:|
|       10       | 116           | 184           | 31,625 | 105          |
|       20     | 77            | 127           | 64,200 | 315          |
|       30     | 59            | 99            | 50,763 | 321          |
|       40     | 49            | 63            | 61,037 | 545          |
|       50     | 37            | 43            | 72,072 | 900          |
|       60     | 25            | 59            | 45,187 | 538          |
|       70     | 36            | 54            | 56,275 | 625          |
| 80     | 25            | 53            | 55,500 | 712          |
| 90     | 22            | 40            | 63,475 | 1,023        |
| 100    | 25            | 39            | 62,925 | 983          |

The table shows how well Swiss Franc trended in the 80s. 
**Only trade in the direction of the long-term trend**