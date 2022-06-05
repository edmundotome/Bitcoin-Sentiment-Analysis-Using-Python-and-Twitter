# Bitcoin-Sentiment-Analysis-Using-Python-and-Twitter
A data mining project to analyze the reaction of Twitter users after the falls of Bitcoin throughout 2021.

## Fall Analysis
Took the day when bitcoin price started the biggest fall in 2021 (this happen in 10th May) and analyze the sentiment reaction the next ten days, this taking 1000 random tweets using Bitcoin as a hashtag.

<div align="center">

Day/Sentiment | Positive | Neutral | Negative
------------- | :---: | :---: | :---:
day 1  | 540 | 414 | 46
day 2  | 542 | 412 | 46
day 3  | 578 | 377 | 45
day 4  | 530 | 382 | 88
day 5  | 601 | 351 | 48
day 6  | 603 | 348 | 49
day 7  | 516 | 383 | 101
day 8  | 525 | 375 | 100
day 9  | 541 | 355 | 104
day 10 | 503 | 362 | 135 ![plt](https://user-images.githubusercontent.com/37748958/172033523-82c298d0-6160-4868-af12-eb9a839b7c3b.png)

</div>

The graph show a correlation between time and sentiments about the constant fall in bitcoin price



## Rise Analysis
Took previous day to the highest bitcoin value in 2021 (this happen in 7th october) and analyze the sentiment reaction during ten continous days before, this taking 1000 random tweets using Bitcoin as a hashtag.

<div align="center">

Day/Sentiment | Positive | Neutral | Negative
------------- | :---: | :---: | :---:
day 1  | 494 | 372 | 134
day 2  | 494 | 388 | 118
day 3  | 487 | 416 | 97
day 4  | 495 | 422 | 83
day 5  | 492 | 360 | 148
day 6  | 491 | 351 | 158
day 7  | 465 | 305 | 230
day 8  | 450 | 298 | 252
day 9  | 451 | 284 | 265
day 10 | 493 | 362 | 145

![plt](https://user-images.githubusercontent.com/37748958/172033456-5be012bb-07c6-4c3a-8c33-b5a3dbf23ed1.png)

</div>

The graph show a correlation between time and sentiments about the days before the maximum bitcoin price

Use tweepy library to manage the twitter API, pandas to organice data as a dataframe, re library to data cleaning, textblob to words analysis and seaborn to visualize data.
