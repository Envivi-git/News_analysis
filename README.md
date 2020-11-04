# News_analysis

## Context and goal

The goal of the project is estimate the relevance of the news and track their impact in real time. It is also the goal of this project to discover factors that contribute to the relevance of a particular new.
The project starts as part of an academic study. The project is related to the Master of data Science by the UOC (Universidad oberta de catalunya).
On the initial stage, we are compiling information from different forums `Meneame`, `Titter` and `Reddit`.
For the case of Meneme, the information is extracted by using Python 3 and the library Beautiful Soup. For Reddit and Twitter, we have used the APIs.

## Members

The team members involved on the data scrapping are Brais Suarez Souto and Enrique Vilanova Vidal.

## Code remarks

The code has been written and executed on `google colab`. There is a link included at the top of the code to open and execute the code on `google colab`. All the cells/chunks of the code have to be executed in order to get the desired results from the scrapper of each website.
In order to run the code properly, please note that the data is saved on a google drive folder, you may need to change the path to your own drive or local folder.

## Files for web scrapping

The files are:

* Scrapper/meneame.ipynb: Contains a scrapper for Meneame with calls to all the libraries. The scrapper is coded with Python and the library Beautiful Soup.
* Scrapper/Reddit.ipynb: Contains a scrapper for Reddit with calls to all the libraries. The scrapper is coded with Python and the library praw.
* Scrapper/TwitterAPIScrapper.ipynb: Contains a scrapper for Twitter with calls to all the libraries. The scrapper is coded with Python and the library tweepy.

All the scrappers generate a csv file as output for further data analysis.

Other libraries used:

* Datetime
* json
* pandas
* request
* urllib
* numpy
