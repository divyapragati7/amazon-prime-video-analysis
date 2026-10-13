# amazon-prime-video-analysis
 Description: Exploratory data analysis of the Amazon Prime Video catalogue using Python, pandas, and Matplotlib
# Amazon Prime Video — Exploratory Data Analysis

## Project Overview

This project explores the Amazon Prime Video catalogue using Python. The goal is to understand the distribution of content types, release years, genres, countries, and content rating labels.

The analysis focuses on data cleaning, exploratory data analysis (EDA), visualisation, and communicating findings while recognising data limitations.

## Business Questions

- What proportion of the catalogue consists of movies versus TV shows?
- Which release years are most represented?
- Which genres appear most frequently?
- Which countries are most frequently listed?
- Which content rating labels occur most often?

## Tools and Technologies

- **Python** — data analysis
- **Pandas** — data cleaning and manipulation
- **Matplotlib** — data visualisation
- **Google Colab** — notebook development
- **GitHub** — project versioning and presentation

## Key Findings

### 1. Content Type Distribution

The dataset contains 9,668 titles:
- Movies: 7,814 (80.82%)
- TV shows: 1,854 (19.18%)

Movies account for approximately four-fifths of the titles in the dataset.

### 2. Release-Year Distribution

The most represented release year is 2021, with 1,442 titles, compared with 962 titles released in 2020.

This is an increase of approximately 49.9% in the number of titles associated with those release years. It does not mean that Amazon Prime added 49.9% more content to its platform in 2021.

### 3. Genre Distribution

The most frequently assigned genres are:
- Drama: 3,687 assignments
- Comedy: 2,099 assignments
- Action: 1,657 assignments

Titles can have multiple genres, so these counts represent genre assignments rather than mutually exclusive titles.

### 4. Country Distribution

Among the recorded country assignments, the most frequent are:
- United States: 334
- India: 246
- United Kingdom: 67

Country information is missing for many titles, so these results describe only the available country information. Titles associated with multiple countries can contribute to more than one count.

### 5. Content Ratings

`13+` is the most frequent individual rating label, with 2,117 titles. The dataset contains multiple rating systems, so labels were compared as recorded rather than combined into a single scale.

## Data Quality and Limitations

- The `date_added` column is missing for 9,513 of the 9,668 titles.
- Country information is missing for most records.
- Multiple genres and countries may be associated with one title.
- The release years in this dataset range from 1920 to 2021.
- The analysis describes catalogue data; it does not measure customer viewing behaviour, customer preferences, or revenue.

## Project Structure

- `amazon_prime_analysis.ipynb` — notebook containing the analysis, code, and charts
- `README.md` — project overview, methods, findings, and limitations

## Conclusion

The dataset is predominantly composed of movies, and Drama is the most frequently assigned genre. The United States is the most frequently listed country among the available country assignments.

This project demonstrates foundational data analyst skills, including data cleaning, exploratory analysis, visualisation, and careful interpretation of results.

## Future Improvements

- Investigate the original source and quality of missing values.
- Explore release-year trends using additional visualisations.
- Improve text consistency and validate country and rating categories.
- Extend the analysis with reliable viewing or engagement data, if available.
