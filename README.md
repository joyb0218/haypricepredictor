# haypricepredictor
Hay Price Predictions Project

Creating a Python project using empirical probability that helps determine the best time to buy hay based on weather, supply, 
demand, cutting type, and quality.

empirical probability: is an estimated probability based upon previous evidence (data) or experimental results, 
it is not based on theory

I will be implementing machine learning models

It's based on weather which means for best results, you need to use app within three days of auction being held

Need history of weather condition 3 days prior, number sold, quantity, national holidays, how much rain fall happened
over the spring/summer, type: square.

Based on these factors, creating an algorithm not unlike what is used to buy and sell stock.

Need to provide a target price buyer is hoping to pay by making one transaction that can provide the most savings.

Will be using a sold price rounded up to the tenth

Need to scrape local weather information, rain fall, season and-- date, price, quantity through my emails 

Ideally it would need to be done according to the season: spring, summer, fall, winter

spring = april, may, june (first cutting, possibly second)
summer = july, august, september (second cutting / third cutting)
fall = october, november, december
winter = january, february, march

Weather should be considered up to three days prior to the auction.

FALL - Need weather table for each of these days... Need to scrape weather history for every Saturday. Need to know 
town of auction for weather information
Price = [8.9, 9.1, 8.3, 9.2, 8.6, 11.8, 7.4, 10.6, 10.9, 6.5, 10.1, 7.9, 9.4] 
Date = [28, 21, 14, 7, 30, 23, 16, 9, 2, 26, 19, 12, 5]
Qty = [1919, 2162, 1790, 1743, 1358, 1607, 1013, 1149, 1081, 1389, 1359, 622, 841]
