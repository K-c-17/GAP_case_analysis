---

# Predicting Consumer Tastes with Big Data at Gap

## Overview

This repository contains the code, data, and analysis related to the team project on **Predicting Consumer Tastes with Big Data at Gap**, based on the **Harvard Business School Case Study (517115-PDF-ENG)**. The goal of this project is to assess the role of big data in informing business decisions at Gap Inc., particularly in light of the company’s move away from traditional creative direction towards a data-driven process.

Gap’s CEO, Art Peck, sought to replace creative directors with big data-driven processes to predict consumer trends and streamline product development. This project explores whether this decision was the right move, how big data can be applied across different Gap brands, and the balance between data analytics and creative intuition in marketing strategy.

---

## Project Objectives

The repository aims to answer the following questions through the provided analysis and code:

1. **Was Art Peck correct in firing his creative directors?**
    - We analyze whether transitioning from relying on the creative vision of directors to a big data-driven approach was a strategic decision. This includes evaluating how data informs creative decisions versus the traditional role of directors in fashion brands.

2. **What types of web data can support Gap's data-driven creative process?**
    - We collect and demonstrate how web data (from sources like social media, customer reviews, Google Trends, and competitor analyses) can provide insights into consumer tastes and preferences. The analysis highlights how this data can inform product development, trend forecasting, and decision-making at Gap.

3. **Is the big data approach effective for Gap Inc.'s primary brands: Gap, Old Navy, and Banana Republic?**
    - The repository includes analysis for each of the three brands, determining which ones benefit more from the data-driven strategy. The data is sourced from non-brand sites, such as fashion blogs, customer sentiment data, and industry reports, to illustrate brand-specific insights.

4. **For what purposes are big data and predictive analytics more or less useful in marketing?**
    - This analysis focuses on the balance between "art" (creative intuition) and "science" (data analytics) in marketing. We assess how and when Gap should lean on data versus traditional creative instincts in its marketing strategy.

5. **How can the marketing team balance art vs. science using web data?**
    - Recommendations are made on how Gap's marketing team can leverage the insights from big data while maintaining the creative aspects of fashion marketing, ensuring the right balance between art and science in their decision-making processes.

---

## Contents of the Scripts Directory

The `scripts` directory contains the following scripts:

1. **Sentiment Analysis of NYT Articles**: Scripts that extract and analyze sentiment from New York Times articles related to GAP Inc., Old Navy, and Banana Republic.

2. **Google Trends Extraction**: Scripts to extract and process Google Trends data for GAP Inc. and its associated brands to identify popular search patterns.

3. **Ratings Data Scraping**: Scripts to scrape product ratings and review data for GAP Inc., Nautica, and Banana Republic from Amazon's website.

---

## Repository Structure

```
/scripts
    - Data scraping and analysis scripts
    - Predictive modeling and insights generation
/reports
    - Executive summary
    - Slide deck presentation
```

---

## Requirements

To run these scripts, you will need the following Python packages:

- `requests`: For making HTTP requests to web pages (e.g., Amazon for web scraping, Google Trends).
- `json`: For handling JSON data responses from APIs.
- `urllib`: For working with URLs, handling errors, and parsing data.
- `pprint`: For printing JSON data in a more readable format.
- `time`: For adding delays and handling time-related functions.
- `azure`: For Azure-related services (if applicable).
- `BeautifulSoup4`: For parsing HTML content when scraping data.
- `pandas`: For data manipulation and analysis.
- `matplotlib` and `seaborn`: For data visualization.
- `pytrends`: For interacting with the Google Trends API.
- `tweepy`: For Twitter API interactions.
- `textblob`: For sentiment analysis.
- `numpy`: For numerical computations.
- `selenium`: For web browser automation (e.g., scraping dynamic content).
- `statsmodels`: For statistical models and hypothesis testing.
- `scikit-learn`: For machine learning models and evaluation metrics.

You can install these packages using pip by running the following command:

```bash
pip install -r requirements.txt
```


---

## Running the Scripts

### 1. Sentiment Analysis of NYT Articles

- Navigate to the `scripts` directory.
- Run the sentiment analysis script using Python:

```bash
python Gap NYT Sentiment Analysis.ipynb
python Banana Republic NYT Sentiment Project.ipynb
python Competitor NYT Sentiment Analysis.ipynb
python Old Navy NYT Sentiment Analysis.ipynb
```

This script will extract articles related to GAP, Old Navy, and Banana Republic from the New York Times and perform sentiment analysis on the content.

### 2. Google Trends Data Extraction

- Navigate to the `scripts` directory.
- Ensure you have set up a Google API key for the Google Trends API.
- Run the Google Trends extraction script:

```bash
python dextract_google_trends.ipynb
```

This script will fetch Google Trends data related to GAP and its associated brands, saving it in a structured format for analysis.

### 3. Ratings Data Scraping from Amazon

- Navigate to the `scripts` directory.
- Run the scraping script to get ratings data for GAP, Nautica, and Banana Republic products from Amazon:

```bash
python Walmart Gap Clothes Reviews.ipynb
python dextract_ratings_analysis_BRepublic.ipynb
python dextract_ratings_analysis_GAP.ipynb
python dextract_ratings_analysis_Nautica.ipynb
```

This script will extract product ratings and reviews data from Amazon, which can then be used for further analysis.

## Additional Notes

- Make sure you comply with the terms and conditions of the websites (e.g., Amazon, New York Times) while scraping data.
- When using the Google Trends API, ensure your API key is kept secure and not shared publicly.
- If you encounter any issues or need further assistance, please refer to the documentation or reach out.

---

## Conclusion

The analysis provided in this repository offers insights into how Gap Inc. can use big data to predict consumer trends, streamline operations, and balance creative direction with data analytics across its primary brands. The findings and methodologies here can support the company's broader strategy to remain competitive in the fast-evolving retail landscape.

---
