# Project Title: Social Media Sentiment Analyzer

## Overview

This project analyzes public sentiment on Twitter towards brands, products, or topics.  It utilizes Python, the Tweepy library for gathering data, PostgreSQL for storage, and leverages text analysis techniques for sentiment scoring.

## Technologies Used

* **Python 3.x** 
* **Tweepy** (for Twitter API interaction)
* **PostgreSQL** (database)
* **TextBlob** (sentiment analysis)
* **Seaborn** (data visualization)

## Project Structure

* `data_collection.py`: Script for fetching tweets from Twitter and storing them in PostgreSQL.
* `preprocessing.py`: Functions for cleaning and normalizing tweet text.
* `sentiment_analysis.py`:  Functions to calculate sentiment scores.
* `analysis.py`: Contains SQL queries and logic for analyzing sentiment data.
* `visualization.py`: Script for generating visualizations of sentiment trends.

## Getting Started

1. **Prerequisites:** 
   * Python 3.x 
   * PostgreSQL installed and running
   * Twitter Developer API Keys (obtain from [https://developer.twitter.com/en](https://developer.twitter.com/en))
2. **Setup:**
   * Clone the repository: `git clone https://github.com/eeroak/social-media-sentiment-analysis`
   * Install dependencies: `pip install -r requirements.txt`
   * Create a database in PostgreSQL and execute the provided schema setup script.
   * Set environment variables for your Twitter API credentials.
3. **Usage**  
   * Run the scripts in the following order:
     * `data_collection.py`
     * `preprocessing.py`
     * `sentiment_analysis.py`
     * `analysis.py`
     * `visualization.py`


## Results

* 

## Challenges

* 

## Project status
Project is: _in progress_

## License

Distributed under the MIT License. See LICENSE for more information.

## Authors/Contact

Eero Kuosmanen - [Github](https://github.com/eeroak)
