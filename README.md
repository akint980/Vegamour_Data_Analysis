# Vegamour Tweet Generation & Analysis 
Overview


- This project demonstrates a step-by-step pipeline for collecting, generating, cleaning, and analyzing tweets related to Vegamour hair products. The process includes:

- Retrieving tweets from X

- Generating synthetic tweets using AI (GPT-2)

- Cleaning tweets for analysis

- Performing sentiment analysis with TextBlob

- Assigning emotion tags 

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
<img width="1061" height="546" alt="image" src="https://github.com/user-attachments/assets/9e1c6bed-2f83-4091-a7e2-c01a0a75e6fb" />





