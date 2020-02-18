---
title: 'Statistician with R'
author: CodeCre8
date: '2020-01-10'
slug: statistician-with-r
categories:
  - Datacamp
image: 'img/portfolio/sun-bubbles.jpg'
showonlyimage: no
output: 
  html_document:
    number_sections: TRUE
weight: 9
---

I had a problem.  

Having witnessed the lies and lack of accountabilities during the implosion of the financial market in 2008, I no longer believed in the existence of professionalism and integrity in the financial industry. The sceptic in me has decided the role of keeping and growing my own hard-earned savings has to be a personal one.
<!--more-->

# Add Statistics to R
With the role comes the task of trading. It is something that I have to take as seriously as a second job. Further more, I need to be good at it. I want to be a trader who is successful and trades profitable.  

In this juncture of my life, the timing is perfect for me to devote the needed time and focus to take on this new challenge.I was taking courses on DataCamp out of interest of working with data, and that is where I discovered R. I believe knowing how to work with data efficiently can be a huge help in trading stocks. As I started taking courses such as Quantitative Analyst with R on DataCamp, I found myself running into concepts that I didn't really quite understanding. I started to suspect that knowing how use R to work with data isn't going to be enough. The fear of getting in over my head started to set in until I stumbled upon statistics.

Statistics is going to help me understand the markets, prices and probabilities, among other applications.

This is the space where I am going to keep a record what I learn about statistics and its application in relation to trading stocks, and R so that I can refer back to it in the future. 

# How is statistics going to help me succeed?
The following content comes largely from this article I found on Quora.
[Click for article](https://www.quora.com/How-can-statistics-be-used-in-trading)

## Father of statistics
The entire study of statistics originated from Carl Friedrich Gauss. He was a brilliant mathematician who lived in the early 1800s and gave the world quadratic equations, methods of least squares analysis and normal distribution. Though Pierre-Simon Laplace was considered the original founder of the normal distribution in 1809, Gauss is often given the credit for the discovery, because he wrote about the concept early on, and his work has been the subject of much study by mathematicians for 200 years. In fact, this distribution is often referred to as the "Gaussian Distribution."

The entire study of statistics originated from Gauss, and allowed us to understand markets, prices and probabilities, among other applications. Modern-day terminology defines the normal distribution as the bell curve with "normal" parameters. And since the only way to understand Gauss and the bell curve is to understand statistics, this article will build a bell curve and apply it to a trading example.

### Mean, Median and Mode

Three methods exist to determine distributions: mean, median and mode. Means are factored by adding all scores and dividing by the number of scores to obtain the average. Median is factored by adding the two middle numbers of a sample and dividing by two, or simply just taking the middle value from an ordinal sequence. Mode is the most frequent of the numbers in a distribution of values. The best method to gain insight into a number sequence is to use the mean because it averages all numbers, and is thus most reflexive of the entire distribution.

This was the Gaussian approach, and his preferred method. What we are measuring here is parameters of central tendency, or to answer where our sample scores are headed. To understand this, we must plot our scores beginning with 0 in the middle and plot +1, +2 and +3 standard deviations on the right and -1, -2 and -3 on the left, in reference to the mean. "Zero" refers to the distribution mean. (Many hedge funds implement mathematical strategies. To find out more, read Quantitative Analysis of Hedge Funds and Multivariate Models: The Monte Carlo Analysis.)

### Standard Deviation and Variance

If the values follow a normal pattern, we will find 68% of all scores will fall within -1 and +1 standard deviations, 95% fall within two standard deviations and 99% fall within three standard deviations of the mean. But this is not enough to tell us about the curve. We need to determine the actual variance and other quantitative and qualitative factors.

Variance answers the question of how spread out our distribution is. It factors in possibilities regarding why outliers may exist in our sample and helps us to understand these outliers and how they can be identified. For example, if a value falls six standard deviations above or below the mean, it can be classified as an outlier for the purpose of the analysis.

Standard deviations are an important metric that are simply the square roots of the variance. Modern-day terms call this dispersion. In a Gaussian distribution, if we know the mean and the standard deviation, we can know the percentages of the scores that fall within plus or minus 1, 2 or 3 standard deviations from the mean. This is called the confidence interval. This is how we know 68% of distributions fall within plus or minus 1 standard deviation, 95% within plus or minus two standard deviations and 99% within plus or minus 3 standard deviations. Gauss called these "probability functions." (For more information on statistical analysis, check out Understanding Volatility Measures.)

### Skew and Kurtosis

So far, this article has been about explanation of the mean and the various computations to help us explain it more closely. Once we plotted our distribution scores, we basically drew our bell curve above all the scores, assuming that they possess characteristics of normality. So still this is not enough because we have tails on our curve that need explanation to better understand the whole curve. To do this, we go to the third and fourth moments of statistics of the distribution called skew and kurtosis.

Skewness of tails measures asymmetry of the distribution. A positive skew has a variance from the mean that is positive and skewed right, while a negative skew has a variance from the mean skewed left – essentially, the distribution has a tendency to be skewed on a particular side of the mean. A symmetrical skew has 0 variance that forms a perfect normal distribution. When the bell curve is drawn first with a long tail, this is positive. The long tail at the beginning before the lump of the bell curve is considered negatively skewed. If a distribution is symmetric, the sum of cubed deviations above the mean will balance the cubed deviations below the mean. A skewed right distribution will have a skew greater than zero, while a skewed left distribution will have a skew less than zero. (For related reading, see Stock Market Risk: Wagging the Tails.)

Kurtosis explains the peak and value concentration characteristics of the distribution. A negative excess kurtosis, referred to as platykurtosis, is characterized as a fairly flat distribution where there is a smaller concentration of values around the mean and the tails are significantly fatter than a mesokurtic (normal) distribution. On the other hand, a leptokurtic distribution contains thin tails, as much of the data is concentrated at the mean.

Skew is more important to assess trade positions than kurtosis. Analysis of fixed income securities requires careful statistical analysis to determine the volatility of a portfolio when interest rates vary. Models to predict the direction of movements must factor in skewness and kurtosis to forecast the performance of a bond portfolio. These statistical concepts are further applied to determine price movements for many other financial instruments, such as stocks, options and currency pairs. Skews are used to measure option prices by measuring implied volatilities.

### Applying It to Trading

Standard deviation measures volatility and asks what kind of performance returns can be expected. Smaller standard deviations may mean less risk for a stock, while higher volatility may mean a higher level of uncertainty. Traders can measure closing prices from the average as it is dispersed from the mean. Dispersion would then measure the difference from actual value to average value. A larger difference between the two means a higher standard deviation and volatility. Prices that deviate far away from the mean often revert back to the mean, so that traders can take advantage of these situations. And prices that trade in a small range are ready for a breakout.

The often-used technical indicator for standard deviation trades is the Bollinger Band®, because they are a measure of volatility set at 2 standard deviations for upper and lower bands with a 21-day moving average. The Gauss Distribution was just the beginning of understanding market probabilities. It later led to Time Series and Garch Models, as well as more applications of skew such as the Volatility Smile.