# YouTube Video Analysis Tool

This Python script analyzes YouTube videos by extracting subtitles, comments, and other metadata. It provides various insights including a summary of the video content, sentiment analysis of comments, text difficulty metrics, and general video statistics.

## Features

- Extract video ID from YouTube URL
- Fetch and transcribe audio from YouTube videos
- Retrieve video comments and replies
- Summarize video content
- Perform sentiment analysis on comments
- Evaluate text difficulty of video subtitles
- Fetch general video data (likes, dislikes, views, rating)

## Requirements

- Python 3.x
- Required Python libraries:
  - requests
  - beautifulsoup4
  - pandas
  - google-api-python-client
  - transformers
  - torch
  - textstat
  - ffmpeg-python
  - yt-dlp

## Installation

1. Clone this repository
2. Install the required libraries:

## Usage

1. Run the script:

2. Enter the YouTube URL when prompted
3. The script will output:
- A summary of the video content
- Sentiment analysis of the comments
- Text difficulty metrics
- General video statistics

## API Keys

You need to provide a valid YouTube Data API key. Replace `'YOUR_API_KEY'` in the script with your actual API key.

## Note

This script uses various APIs and machine learning models, which may have usage limits or require additional setup. Make sure you comply with the terms of service for all used APIs and models.

## License

[MIT License](https://opensource.org/licenses/MIT)
