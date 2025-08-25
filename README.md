# Vegamour Tweet Generation & Analysis Pipeline
Overview
<img width="1600" height="852" alt="image" src="https://github.com/user-attachments/assets/a8b0aa38-3443-4070-89dd-cf8294dd8b04" />


This project demonstrates a step-by-step pipeline for collecting, generating, cleaning, and analyzing tweets related to Vegamour hair products. The process includes:

Retrieving tweets from social media APIs (placeholder code)

Generating synthetic tweets using AI (GPT-2)

Cleaning tweets for analysis

Performing sentiment analysis with TextBlob

Assigning emotion tags (simulated)

Pipeline Steps
1. Retrieving API Tweets

This step is a placeholder in the current codebase.

Intended for fetching real tweets from social media platforms like X

Example: Pulling tweets mentioning Vegamour products.

2. Retrieving AI-Generated Tweets

Uses Hugging Face’s GPT-2 model to create synthetic tweets based on customizable prompts.

Produces raw text output that may include prompt echoes and extraneous data.

3. Cleaning Tweets

Removes unwanted elements such as prompt echoes, URLs, hashtags, mentions, and extra whitespace.

Ensures the text length respects Twitter’s 280-character limit.

Prepares tweets for accurate sentiment and emotion analysis.

4. Sentiment Analysis

Utilizes TextBlob to calculate sentiment polarity for each tweet.

Classifies tweets as Positive, Neutral, or Negative based on polarity scores.

5. Emotional Analysis

Assigns one of four emotions — Joy, Frustration, Nostalgia, or Gratitude — randomly.


