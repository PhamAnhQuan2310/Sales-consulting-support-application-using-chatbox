# Sales Consulting Support System

A web-based sales consulting application for a fruit shop, combining Natural Language Processing, customer review analytics, product recommendation, and news aggregation in a single platform.

## Main Features

- Customer support chatbot powered by a fine-tuned T5 model for intent-based response generation.
- Sentiment detection integrated into chatbot conversations.
- Upload and analyze customer review datasets from CSV files.
- Classify reviews into positive, neutral, and negative sentiment using VADER.
- Product recommendation using Item-based Collaborative Filtering and Cosine Similarity.
- Generate recommendations based on user-product rating patterns.
- Visualize the most frequently reviewed products with statistical charts.
- Rank and display customer reviews based on helpfulness scores.
- Aggregate fruit-related news from online news sources through web scraping.
- REST-style chatbot and news endpoints for asynchronous frontend interaction.

## Tech Stack

**Backend:** Python, Flask  
**Frontend:** HTML5, CSS3, Bootstrap 5, JavaScript, Jinja2  
**NLP:** T5, Hugging Face Transformers, NLTK VADER  
**Machine Learning:** scikit-learn, Cosine Similarity, Joblib  
**Data Processing:** Pandas  
**Visualization:** Matplotlib  
**Web Scraping:** BeautifulSoup4, Requests

## Project Structure

- `app.py` - Main Flask application and API routes
- `chatbot/` - Product search and recommendation modules
- `sentiment_analysis/` - Sentiment analysis components
- `news_scraper/` - News crawling and aggregation
- `data/` - Application datasets
- `templates/` - Jinja2 HTML templates
- `static/` - CSS, JavaScript and static assets
