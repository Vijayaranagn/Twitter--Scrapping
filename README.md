# Twitter--Scrapping
Twitter scraping using "SNSCRAPE"
To deploy this project run

!pip install beautifulsoup4
!pip install pymongo
!pip install streamlit
!pip3 install snscrape 

#Environment libraries

* import snscrape.modules.twitter as sntwitter
* import pandas as pd
* from pymongo import MongoClient
* from datetime import datetime
* import streamlit as st
* import tweepy
* import pymongo

#MongoDB - DataBase

Make a customised collection with your mongodb database to store your scraped data in cloud database .csv.

#Create GUI using "Streamlit"

Streamlit use for create a page like "keyword or Hashtag to be searched, select the date range and limit the tweet count need to be scraped. After scraping, the data needs to be displayed in the page and need a button to upload the data into Database and download the data into csv and json format"
