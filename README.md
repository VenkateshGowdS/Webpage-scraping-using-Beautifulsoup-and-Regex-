# Webpage-scraping-using-Beautifulsoup-and-Regex-
We scrape information of a webpage, fetching all details(date, description, event type) that occured on September 10. 
import re
import urllib,requests
from bs4 import BeautifulSoup
from urllib.request import urlopen
import sqlite3
