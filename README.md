# Beats Wireless Speaker Survey — Externship Capstone

## Overview
This project analyzes consumer survey data collected for Beats by Dre on wireless speaker preferences, satisfaction, and purchasing behavior. The analysis combines traditional data analysis with AI-powered sentiment analysis using the Google Gemini API to extract deeper insights from open-ended survey responses.

## Tools & Technologies
- **Python** (pandas, numpy, matplotlib) – Data cleaning and analysis
- **TextBlob** – Sentiment analysis on open-ended responses
- **WordCloud** – Visualization of common themes in survey responses
- **Google Gemini API** – AI-powered analysis of survey text responses
- **Google Colab** – Development environment

## Dataset
Consumer survey responses covering wireless speaker ownership, usage habits, brand preferences, satisfaction ratings, and purchasing factors.

Key survey topics included:
- Wireless speaker ownership and usage frequency
- Sound quality ratings and open-ended feedback
- Feature importance rankings (sound quality, battery life, design, connectivity, durability, price)
- Brand ownership history
- Purchase decision factors
- Overall satisfaction and improvement suggestions
- Demographic information (age, gender, income)

> Note: Personal identifiers (email addresses) have been removed from the dataset prior to upload.

## Project Workflow

### 1. Data Cleaning
- Loaded and standardized raw survey response data
- Removed duplicate entries and handled missing values
- Cleaned and formatted columns for analysis

### 2. Exploratory Data Analysis
- Analyzed feature importance rankings across respondents
- Explored brand preferences and ownership patterns
- Examined satisfaction scores by demographic segments
- Investigated purchase decision factors and price sensitivity

### 3. Sentiment & Text Analysis
- Used **TextBlob** to perform sentiment analysis on open-ended responses
- Generated **word clouds** to visualize common themes from satisfied vs. unsatisfied respondents
- Used **Google Gemini API** to extract deeper insights from free-text survey answers

### 4. Visualizations
- Feature importance bar charts
- Satisfaction score distributions
- Word clouds comparing highly satisfied vs. unsatisfied customer language
- Brand preference and usage pattern charts

## Files
| File | Description |
|---|---|
| `BeatsExternship.ipynb` | Full analysis notebook |
| `wireless_speakers_cleaned.csv` | Cleaned survey dataset (emails removed) |

## Notes
- The Google Gemini API key has been removed from the code. To run the notebook, add your own key via Google Colab's `userdata` secrets manager
- Raw survey data contained personal identifiers which have been excluded from this repository
