# Cryptocurrency News Aggregator

## Description

A lightweight, Rust-based web application that aggregates the latest cryptocurrency news from multiple trusted sources. Users can search by cryptocurrency name or symbol to get real-time news articles with concise summaries, source info, and publication dates.

## Key Features

 - Search for cryptocurrency market data

 - Get the latest news related to cryptocurrencies

 - Error handling for missing data or API issues

 - Clean and modern responsive UI

 - Suggests supported cryptocurrencies

# How It Works

1. User enters a cryptocurrency name (e.g., bitcoin) in the search bar.

2. App fetches:

    Market data like price and market cap.

    Latest news articles.

3. Everything is displayed on the same page with clean and responsive design

## Technologies
- Backend: Rust

- Frontend: HTML/CSS


## APIs Used
- CoinGecko API
  
  Used to fetch real-time cryptocurrency data such as current price, market capitalization, and token details.

- GNews API

  Used to fetch recent news articles related to selected cryptocurrencies. Also includes basic date formatting and sentiment tagging.

## Installation

To run this project locally, ensure that you have Rust installed. You can follow the instructions to install Rust [here](https://www.rust-lang.org/learn/get-started).

Additionally, you need "GNEWS_API_KEY" API key variable  placed in your .env file

### Steps to run:

1. Clone the repository:
    ```bash
    git clone https://github.com/Timirlon/news-agregator-rust
    cd news-aggregator-rust
    ```

2. Install dependencies:
    ```bash
    cargo build
    ```

3. Run the server:
    ```bash
    cargo run
    ```


## Demo Screenshots




## Development Team

- Temirlan Turgimbayev SE-2321
- Amirkhan Turgimbayev SE-2322

## License

This project is designed for academic purposes only and is not intended for commercial use. Licensed under MIT License.