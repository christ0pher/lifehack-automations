# News Manager Automation Blueprint

## Overview
This blueprint outlines an automation process designed to manage and transform news content. It integrates with RSS feeds, OpenAI's GPT-4, and Notion, performing tasks from fetching and sentiment analysis of news articles to rewriting and updating Notion pages with transformed news content.

## Watch on youtube
[![Fixing the news! Curated news articles using OpenAI GPT-4, RSS, Notion and make.com.](http://img.youtube.com/vi/cmWhAVkq8jM/0.jpg)](https://youtu.be/cmWhAVkq8jM "Video Title")


## Workflow
1. **Start Trigger**: Initiates the scenario.
2. **Create Current News Page in Notion**: A new Notion page is created daily for storing news articles.
3. **Fetch RSS Feeds from Notion Database**: Retrieves URLs of RSS feeds stored in a Notion database.
4. **Fetch Current News**: Reads news articles from the fetched RSS URLs.
5. **Analyse News Sentiment**: Utilizes OpenAI GPT-4 to analyze the sentiment of the fetched news articles.
6. **Aggregate Positive News**: Aggregates news deemed positive by the sentiment analysis.
7. **Rewrite News Article**: Rewrites the aggregated news using OpenAI GPT-4, following specified transformation rules.
8. **Append Article to Notion Page**: Appends the rewritten news content to the designated Notion page.

## Prerequisites
- An active Notion account with API access.
- An OpenAI account with API access for GPT-4.
- RSS feed URLs stored in a Notion database for news sources.

## Features
- Automated fetching and sentiment analysis of news articles.
- AI-powered content transformation and rewriting.
- Dynamic updating of Notion pages with transformed news content.
