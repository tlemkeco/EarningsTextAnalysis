# EarningsTextAnalysis
This repository will pull the relevant text from quarterly earnings releases published by corporations. 

I have grown increasingly interested in the stock market and how stock prices fluctuate with press releases, news, and also the release of quarterly earnings. Ultimately, I would like to programmatically sync a text analysis of the quarterly earnings report with the movement of the stock price. I would then like to apply nlp to the text of the earnings release to identify correlations between this and the movement in the stock price. 

Obviously, a human can read a quarterly report and likely predict with good accuracy a general consensus of how the stock price is going to repond or also correlate what in a quarterly report led to the subsequent stock movement. My question is find out whether a computer application can do the same. 

# EarningsTextAnalysis/Dermira_scrape_final
This script is for scraping the text data from a quarterly earnings report that I have saved to the directory as an html file. Here is a link to the HTML: https://investor.dermira.com/news-releases/press-release-details/2018/Dermira-Reports-First-Quarter-2018-Financial-Results-and-Provides-Corporate-Update/default.aspx. 

This first identifies the tags of the html document and then extracts them to a list. This list is then converted to a string which is converted to a spacy doc which can be utilized to apply text analysis such as tokenization, vectorization, etc. 
