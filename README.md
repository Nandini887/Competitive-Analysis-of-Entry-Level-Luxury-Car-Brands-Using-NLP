# Competitive-Analysis-of-Entry-Level-Luxury-Car-Brands-Using-NLP

Analytics on Unstructured Social Media Data (Edmunds Forum)

### Project Overview

This project analyzes social media discussions from Edmunds.com entry-level luxury car forums to extract competitive insights for the U.S. luxury automobile market. Acting as an analytics consultant for JD Power & Associates, the objective was to uncover brand associations, aspirational trends, and key vehicle attributes using natural language processing (NLP) and unsupervised learning techniques.

The analysis is fully implemented in Python and focuses on text mining, association analysis, and perceptual mapping, without relying on sentiment analysis.

### Business Objectives

Identify the top luxury car brands discussed by consumers

Measure brand associations using lift ratios

Visualize competitive positioning via Multi-Dimensional Scaling (MDS)

Discover key car attributes valued by consumers

Identify the most aspirational brand and derive business insights

### Data Source

Edmunds.com Entry-Level Luxury Performance Sedans Forum

~8,000–10,000 scraped forum posts

Each post contains:

user_id

date

message

Special care was taken to avoid double-counting quoted replies in the forum threads.

### Methodology & Tasks
🔹 Task A: Zipf’s Law Validation

Tested whether word frequencies follow Zipf’s Law

Performed econometric validation

Visualized top 100 words vs theoretical Zipf distribution

No stopword removal or lemmatization applied

🔹 Task B: Brand Frequency Analysis

Identified top 10 luxury brands

Replaced car model mentions with corresponding brands using a lookup file

Ensured 1 brand count per message, even if repeated

🔹 Task C: Lift Ratio Calculation

Computed pairwise lift values among top-10 brands

Quantified strength of brand associations in consumer discussions

🔹 Task D: Multi-Dimensional Scaling (MDS)

Visualized brand relationships on a 2D perceptual map

Interpreted proximity as strength of consumer association

🔹 Task E: Industry Insights

Derived strategic insights from lift analysis and MDS positioning

🔹 Task F: Attribute Analysis

Identified top 5 most discussed car attributes

Measured association strength between attributes and brands

🔹 Task G: Strategic Recommendations

Provided actionable recommendations based on attribute-brand associations

🔹 Task H: Aspirational Brand Analysis

Identified the most aspirational brand based on ownership-intent language

Discussed business implications and market positioning

### Tools & Technologies

Programming: Python

Libraries: Pandas, NumPy, NLTK, Matplotlib

Techniques: Web Scraping, NLP, Lift Analysis, MDS

Environment: Jupyter Notebook
