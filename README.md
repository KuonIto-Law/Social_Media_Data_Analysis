# Social Media Data Analysis

This repository contains graduate coursework on social media and digital trace data analysis.  
The projects focus on how online content spreads, how users engage across platforms, and how social media data can be analyzed using statistical methods, NLP, and network analysis.

## Platforms and Data

| Notebook | Platform / Data | Type of data |
|---|---|---|
| `01_google_trends_and_macro_data.ipynb` | Google Trends, World Bank, ILINet | Search behavior data, macro/public data, health time-series data |
| `02_twitter_social_impact.ipynb` | X (Twitter), YouTube | Social media posts, channel statistics, engagement data |
| `03_twitter_youtube_sentiment.ipynb` | X (Twitter), YouTube, Vent | Text data for sentiment and emotion analysis |
| `04_x_reddit_network_and_threads.ipynb` | X (Twitter), Reddit | Retweet network data, Reddit thread and comment structure |

## What I Analyzed

- **Google Trends and macro data:** analyzed the relationship between future-oriented search behavior and GDP, and modeled flu trends using Google Trends and ILINet data.
- **X and YouTube:** examined social impact and engagement using regression analysis and bootstrapping.
- **Sentiment and emotion across platforms:** compared sentiment and emotion detection methods using text data from X, YouTube, and Vent.
- **X networks and Reddit discussions:** analyzed retweet networks of politicians on X and compared political and non-political discussion structures on Reddit.
- **Political engagement on Reddit:** found that political threads tended to receive more replies than non-political threads, indicating stronger engagement around political content.

## Methods

- Data collection and preprocessing
- API-based social media data collection
- Regression analysis
- Bootstrapping
- Sentiment analysis
- Emotion detection
- Network analysis
- Statistical testing
- Time-series analysis

## Platforms Covered

- **X (Twitter):** posts, retweets, engagement, and network structure
- **YouTube:** platform statistics, text data, and engagement patterns
- **Reddit:** thread structure, reply patterns, and political vs. non-political discussions
- **Google Trends:** online search behavior data
- **World Bank / ILINet:** macro-level and public time-series data used for comparison and modeling

## Directory Structure

```text
.
├── a01
│   ├── 01_google_trends_and_macro_data.ipynb
│   ├── geoMap.csv
│   └── ILINet.csv
├── a02
│   ├── 02_twitter_social_impact.ipynb
│   ├── selected_channels.json
│   └── USCongress-tweets.zip
├── a03
│   ├── data/
│   ├── src/
│   ├── 03_twitter_youtube_sentiment.ipynb
│   ├── sample_df.csv
│   ├── Twitter_label.csv
│   └── YouTube_label.csv
└── a04
    ├── 04_x_reddit_network_and_threads.ipynb
    └── swiss_pol_retweet_network.gexf