---
title: "Stock Price Analyzer using sentiment analysis on news articles and tweets"
excerpt: "Analysing the tweets and news, understanding the sentiment and predicting the stocks they are going to affect.<br/>"
# <img src='/images/500x300.png'>"
collection: project
---

News and current affairs affect the stocks when it comes to trading. It also affects the way people think & the way they make a decision.
We have a seen that the sentiment behind the news affect more than it should be.
But how can we escape it and predict the change before it happens?

Bloomberg is already using the technique of using sentiment analysis on current news to estimate the change on related stocks.
And making millions out of it.

Here is an example of how it works...

I used the Business Times to search for news articles on Facebook. Ideally, we can use tweets from powerful celebrities, media houses
and companies to reach to the news faster. So I ran it for the last six months and averaged the sentiments of each news article for a
given day. Here it goes...

<img src='/images/Sentiments.png'>

Here, every sentiment score for the day shows the sentiment average for the day. 1 means a very positive news for the company while -1
tends to show the negativity or a setback for the company. This gives an idea about how the stock of facebook is going to be in the
near term. Let us see how effective it is:

<img src='/images/Predictions.png'>

In the above image we can see that the dip in the second week of July 2019 on Facebook stock could have predicted.
The bull run for 26th June till 10th July 2019 could be predicted as the last point on Facebook news was positive on 25th June 2019
Thereafter, the sentiments are fairly stable near zero value which indicated there will be a stable change all the way till next
non-zero sentiment value. 

Further steps of improvement here would be to devise an relatability algorithm as sometimes the news article does not always affect the
stock. The other main step would be to figure out the accuracy of this method and how to improve it.
