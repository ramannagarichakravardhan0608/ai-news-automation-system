# AI-Powered Automated News Aggregator with Email Alert

## Overview

This project is an AI-powered automated news aggregation system built using n8n, Docker, Google Gemini AI, Gmail API, and RSS feeds.

The workflow automatically:
- Collects AI and tech news from RSS feeds
- Filters recent news
- Merges articles
- Uses Gemini AI to generate high-value summaries
- Sends summarized insights through email automatically

---

# Features

- Automated AI news collection
- RSS feed integration
- AI-powered summarization using Gemini
- Automated email alerts
- Dockerized local deployment
- Workflow automation using n8n
- Real-time news processing

---

# Tech Stack

- n8n
- Docker
- Google Gemini API
- Gmail OAuth API
- RSS Feeds
- JavaScript
- AI Automation

---

# RSS Sources

- TechRadar AI Feed
- KDnuggets Feed

---

# Workflow Architecture

```text
RSS Feeds
    ↓
Filter Recent News
    ↓
Merge News Articles
    ↓
Gemini AI Summarization
    ↓
Generate Insights
    ↓
Send Email Alerts
