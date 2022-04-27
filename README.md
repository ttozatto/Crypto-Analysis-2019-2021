# Crypto-Analysis-2019-2021
![image](https://user-images.githubusercontent.com/42552721/165603300-8160b520-fd1a-490a-955c-704ccbca62ee.png)

## Introduction
This is a study on the crypto market between the years of 2019 and 2021.

In the notebook I show some analysis on what happened to the biggest tokens in this period and some insight about the Sharpe Ratio applied to crypto.

I wrote a blog post in Medium using this project: https://medium.com/@ttozatto.ds/can-we-guess-the-best-cryptos-looking-at-sharpe-ratio-19cfc89a71a

## File Description
 - /tokens - Folder with historical data (.csv) from the current top 1000 tokens from CoinMarketCap.com.
 - project.ipynb - Jupyter Notebook with the cryptocurrency analysis

## Dependency 
 - requests = 2.27.1
 - json = 2.0.9
 - pandas = 1.2.5
 - numpy = 1.21.2
 - matplotlib = 3.5.0
 - plotly = 5.6.0
 - my fork of cryptoCMD (a scraper for coinmarket.com) -> https://github.com/ttozatto/cryptoCMD
 - - The fork just add the `id_number` parameter to distinguish different tokens that are represented by the same `symbol`.

You will need a free API key from https://coinmarketcap.com/api/

## Summary of results
The analysis show that the Sharpe Ratio is not a good metric to build cryptocurrencies portfolios.

## Aknowledgements
I would like to pay my special regards to:
 - Udacity, that proposed this work in the Data Science Nanodegree
 - CoinMarketCap.com, that freely provides data on crypto
 - guptarohit, that built the cryptoCMD scraper

