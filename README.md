# newsapi-to-csv
A data# NewsAPI Crypto News Data Pipeline

A Python data pipeline that fetches the latest cryptocurrency news 
from NewsAPI, processes the JSON response using Pandas, and exports 
the structured data as a CSV file.

## About
This project collects 100 news articles related to cryptocurrency 
topics (Bitcoin, Dogecoin, etc.) from various sources like CNN, 
Forbes, and Gizmodo, and organises them into a clean, structured 
dataset.

## Dataset Columns
| Column | Description |
|---|---|
| source | News outlet name |
| author | Article author |
| title | Article headline |
| description | Short summary |
| url | Link to full article |
| urlToImage | Article image link |
| publishedAt | Publication date/time |
| content | Article content snippet |

## Tools & Libraries
- Python
- NewsAPI
- JSON
- NumPy
- Pandas

## How It Works
1. Connects to NewsAPI using an API key
2. Fetches news articles in JSON format
3. Parses and normalises the JSON response
4. Loads the data into a Pandas DataFrame
5. Exports the DataFrame to `articles_data.csv`

## Setup
1. Clone the repo pipeline that fetches live news data from the NewsAPI, structures it into a Pandas DataFrame, and exports it as a CSV file for further analysis.
