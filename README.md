# Facebook Ads in 2019 Canada Federal Election Reveal Limitation of 
Female Participation in Politics in Canada


## Summary of Findings
Is politic still a good old boy's club in Canada? For some parties in Canada, 
it might still is. In this paper, the audience demography of 14690 Facebook ads 
plublised during the election season were analysed. The findings indicates that
three out of the six parties who participated in the Federal Election have their 
ads reached substaintially more male than female audience. Moreover, it is also 
found that most of the parties have different messaging for female and male audiences — 
environmental and social topics for females, and economic topics for males.

## Data: Facebook Ads Library API
The data is collected through [Facebook Ad Library Scraper](https://github.com/minimaxir/facebook-ad-library-scraper) 
developed by Max Woolf (@minimaxir). The queries are set to collect the ads from the pages of each party 
and each leader that were active from June 1st, 2019 to October 21, 2019. 
Three data frames are retrieved — a data frame that contains the raw ads and 
their metadata; a data frame that has the unnested demographic distributions 
of people reached by ads, and the data frame that has the unnested region 
distributions of people reached by ads. The three data frames can be 
joined by the unique identifier of the ads. 

## Methods: EDA, Sentiment Analysis, TF-IDF

In this work, we examine the dataset of advertisements posted to Facebook at the time of the 2019 Canada federal election season by exploratory data analysis, sentiment analysis and TF-IDF keyword extraction.

### See the [PDF file](facebook_ads_library.pdf) for R code, data visualization and full analysis





