# Negativity in NFL Fan Bases

## Repository Contents

### Installing/Building Code in this Repository

### Usage of Code in this Repository

## Data

The dataset for this project was collected using the Twitter API. In conjunction with Python, tweets were mined that contained specific hashtags related to each of the NFL's 32 teams. Each tweet was sorted by which team it related to and a sentiment score was calculated for each one. To start, 1000 tweets were collected for hashtags related to each team totaling in a dataset of 32,000 tweets. However, after removing duplicate tweets such as retweets, roughly 13,000 original tweets remained in the dataset. The tweets collected were the most recent found and so reflect recent sentiments expressed by Twitter users. The dataset can be found in CSV format in the data directory of this repository in `nfl_tweets.csv` ([src](data/nfl_tweets.csv)).

#### Data Dictionary

| Variable | Data Type | Description | Example |
|----------|-----------|-------------|---------|
| text | String | The text of the tweet | 'Let's go Bills! #BillsMafia' |
| team | String | The team whose hashtag is found in the tweet | 'Buffalo Bills' |
| compound | Numeric | The overall sentiment score of the tweet, ranging from -1 to 1 with -1 being most negative and 1 being most positive | 0.5 |
| negative | Numeric | The negative sentiment score of the tweet, ranging from 0 to 1 with 0 being least negative and 1 being most negative | 0.4 |
| positive | Numeric | The positive sentiment score of the tweet, ranging from 0 to 1 with 0 being least positive and 1 being most positive | 0.6 |
| neutral | Numeric | The neutral sentiment score of the tweet, ranging from 0 to 1, 0 being least neutral, 1 being most neutral | 0 |

## Figures

## References

This project was created as part of the Data Science Project Course (DS 4002)  at the University of Virginia in the Fall of 2022.