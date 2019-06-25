# Analysis of speeches given by PM Narendra Modi from January 2014 to March 2019

![wordcloud](https://raw.githubusercontent.com/katreparitosh/Election-Campaign-Analytics/master/Word-Cloud/wordcloud.png)

## Description 

All of the speeches given by PM Narendra Modi are made available [here](https://www.pmindia.gov.in/en/tag/pmspeech/) by the Prime Ministers
Office. For the project, I scraped over 500 speeches and analysed using text analysis tools in Python.

## Method

1. Scraping
  * Scraped all the speeches available online into multiple batches using **Selenium Library** and **Webdriver** with Chrome.

2. Extraction of data
  * To scrape the raw text and data from the batches I used helper functions.
  * Code is available in subsequent folders of the months [2018](https://github.com/katreparitosh/Election-Campaign-    Analytics/tree/master/Code/2018).

3. Managing, storing and further cleaning the data
  * I used 'Pandas' to create dataframe for each batch of speeches and exported each to 
  a **pickle** file for flexible storage.
  * I consolidated the three data frames into one dataframe annd cleaned the data using 'Pandas' functions,
  String methods, regular expressions, etc.
  * Using **string** and **nltk** libraries, I stripped the speeches from punctuation, converted to lowercase, tokenized the text,
  dropped the stopwords, etc.
  * Codes are available [here](https://github.com/katreparitosh/Election-Campaign-Analytics/tree/master/Code/Cleaning%20and%20Wrangling).

## Findings 
All codes for analysis are available [here](https://github.com/katreparitosh/Election-Campaign-Analytics/blob/master/Code/Analysis/Analysis.ipynb)

Some visualizations 
![1](https://github.com/katreparitosh/Election-Campaign-Analytics/blob/master/Findings/4.png)

![2](https://github.com/katreparitosh/Election-Campaign-Analytics/blob/master/Findings/5.png)

![3](https://github.com/katreparitosh/Election-Campaign-Analytics/blob/master/Findings/3.png)

![4](https://github.com/katreparitosh/Election-Campaign-Analytics/blob/master/Findings/6.png)
