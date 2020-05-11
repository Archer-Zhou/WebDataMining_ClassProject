# This is a Class Project
The project contains two parts:
1. Web Scraper  
2. Data Mining

## 1. Web Scraper
This part is a simple Scraper that used to get user info from [https://www.douban.com/]  
Infos including their nicknames, locations and registered date.  
Data was stored in /data/douban_edges.csv douban_info.csv
## 2. Data Mining
This part contains three main Analysis.
### 2.1 Group Finding
Use the Algrithm -- Louvain to find user's group.
### 2.2 Visuallizing in Map
Use the pyechart packege to visualize the user location data.  
The rendered image is in /data/china.html
### 2.3 Prediction of New Users
Use the Algrithm -- ARIMA(Autoregressive Integrated Moving Average model) to predict new users.
