# Trend Detection & Business Sentiment Analysis

**Real-time multi-source trend detection and sentiment analysis for businesses using News, Reddit, Amazon, Google Trends, and RSS feeds.**

This project analyzes **public perception, emerging topics, and consumer sentiment** for any brand or product by aggregating data from multiple platforms and applying **NLP + statistical modeling**.

---

## Features

| Feature | Description |
|-------|-----------|
| **Multi-Source Data Ingestion** | NewsAPI, Reddit (PRAW), Google News RSS, Amazon Reviews, Google Trends |
| **Relevance Filtering** | Business + topic-specific keyword filtering |
| **NLP-Powered Topic Extraction** | spaCy noun chunks + lemmatization |
| **Sentiment Analysis** | VADER sentiment per topic |
| **TF-IDF & LDA Topic Modeling** | Key term importance + latent topics |
| **Co-occurrence Network Graph** | Visualize topic relationships |
| **Google Trends Integration** | Interest over time, related queries |
| **Competitor Benchmarking** | Compare topics & sentiment |
| **Automated Reports & Visualizations** | CSV exports + PNG plots |

---

## Use Cases

- **Brand Monitoring** – Track public sentiment for *Westside*, *Nova Cream*, *Jaguar*
- **Product Launch Analysis** – Detect buzz around new flavors, models, collections
- **Competitive Intelligence** – Compare vs Zara, Breyers, BMW
- **Crisis Detection** – Identify negative sentiment spikes early

---

## Supported Businesses (Pre-configured)

| Business | Topic Examples | Competitors |
|--------|----------------|-----------|
| **Westside** | fashion, kurta, retail | Zara, Shoppers Stop |
| **Nova Cream** | ice cream, vegan | Breyers, Häagen-Dazs |
| **Jaguar** | luxury cars, electric | BMW, Mercedes-Benz |

> Easily extensible to **any brand + topic**.

---

## Project Structure
