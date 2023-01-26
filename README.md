# Crypto App

A web application that displays various statistics and information about different cryptocurrencies to learn how to use and manipulate APIs.

## Screenshot

![App Screenshot](https://s3.eu-west-1.amazonaws.com/github.photos/CryptoApp.PNG)

## Tech Stack

ReactJS for building the user interface  
Redux for managing the application's state  
AntDesign for styling components  
ChartJS for creating charts and visualizations  
Axios for making API requests  
RapidAPI for accessing cryptocurrency data

## Features

-   View the current prices and market data of various cryptocurrencies.
-   View historical price data in the form of charts.
-   View the latest news stories related to cryptocurrencies.

## Run Locally

Clone the project

```bash
  git clone https://github.com/Alex-hrt/cryptoapp.git
```

Install dependencies

```bash
  npm install
```

Create a .env file and add your RapidAPI key

```bash
REACT_APP_RAPIDAPI_KEY =  ''
REACT_APP_CRYPTO_API_URL = 'https://coinranking1.p.rapidapi.com'
REACT_APP_NEWS_API_URL = 'https://bing-news-search1.p.rapidapi.com'
REACT_APP_NEWS_RAPIDAPI_HOST = 'bing-news-search1.p.rapidapi.com'
REACT_APP_CRYPTO_RAPIDAPI_HOST ='coinranking1.p.rapidapi.com'
```

Start the server

```bash
  npm start
```
