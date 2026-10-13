# amazon-prime-video-analysis
 Description: Exploratory data analysis of the Amazon Prime Video catalogue using Python, pandas, and Matplotlib
# Amazon Prime Video — Exploratory Data Analysis

## Project objective

Explore the Amazon Prime Video catalogue to understand its content composition, release-year distribution, genre distribution, country representation, and rating labels.

## Key findings

1. **Content type:** Movies account for 80.82% of the 9,668 titles, while TV shows account for 19.18%.

2. **Release years:** 2021 is the most represented release year in this dataset, with 1,442 titles. The dataset's release years range from 1920 to 2021.

3. **Genres:** Drama is the most frequently assigned genre, followed by Comedy and Action.

4. **Country representation:** Among recorded country assignments, the United States ranks first, followed by India and the United Kingdom.

5. **Ratings:** `13+` is the most frequent individual rating label. The dataset contains multiple rating systems, so the labels should not be combined without a clearly defined mapping.

## Data-quality limitations

- The `date_added` column is missing for 9,513 titles, limiting analysis of when titles were added to the platform.
- Country information is missing for most records, so country findings represent only records with recorded country information.
- A title can have multiple genres and countries, meaning those counts are assignments rather than mutually exclusive title counts.
- The latest release year in the dataset is 2021; the findings should not be presented as a description of the current catalogue without newer data.

## Conclusion

The dataset is heavily weighted toward movies, with Drama the most frequently assigned genre and the United States the most frequently listed country among records with country information. These findings describe the catalogue's recorded characteristics, not customer viewing preferences, platform growth, or revenue.
