# Spark Funds Investment Analysis

## Objective

Spark Funds, a prominent venture capital firm, seeks to make strategic investments in promising startups. The objective of this analysis is to provide insights into investment trends to assist Spark Funds in identifying suitable investment opportunities.

## Problem Statement

Spark Funds aims to invest between 5 to 15 million USD per round of investment and prefers to invest in English-speaking countries. The analysis will focus on addressing the following key questions:

1. What are the most suitable funding types within the desired investment range?
2. Which English-speaking countries have historically received the highest investments?
3. Which main sectors attract the most significant investment amounts?

## Data Overview

### Data Sources

1. [Companies Data](https://drive.google.com/file/d/13zUZ6YBopbsmTCAm5TwK22cN2AQGeQ2U/view?usp=drive_link): Contains information about various companies, including their sectors and countries.
2. [Rounds2 Data](https://drive.google.com/file/d/1EGAw0wYVkdRuRMIgZD1gWLBmI8utI2_P/view?usp=drive_link): Provides details about funding rounds, such as investment amounts and types.
3. [Mapping Data](https://drive.google.com/file/d/1WqY2zSzNS4FYU-PPWaLXLP7f7aKZ1Lar/view?usp=drive_link): Maps sub-sectors in the companies' data to main sectors for standardization.

### Data Preparation and Cleaning

1. **Filtering Investments**: We filter investments between 5 to 15 million USD.
2. **Country Selection**: Only English-speaking countries are included based on official language criteria.
3. **Data Merging**: Companies and rounds2 data are merged using the company identifier.

## Analysis Overview

### Investment Type Analysis

- Determine the funding types (e.g., venture, seed, angel) suitable for Spark Funds' investment range.
- Calculate average investment amounts for each funding type.

### Country Analysis

- Identify English-speaking countries with the highest historical investment amounts.
- Aggregate total investments by country to rank them accordingly.

### Sector Analysis

- Map sub-sectors to main sectors using the mapping file for standardized sector analysis.
- Analyze total investment amounts by main sector to identify top sectors.

## Visualizations

1. **Investment Type Analysis**: Bar plot illustrating average investment amounts for different funding types.
2. **Country Analysis**: Bar plot showcasing total investment amounts by country.
3. **Sector Analysis**: Bar plot displaying total investment amounts by main sector.

## Recommendations

### Investment Type Recommendation

Based on the analysis, it is recommended to consider funding types like **Venture** and **Private Equity** due to their significant average investment amounts within the desired range.

### Country Recommendation

The analysis highlights the **USA** as the leading market for investments. It is advisable to focus on the USA, United Kingdom, and Canada for potential investment opportunities.

### Sector Recommendation

Investing in sectors such as **Cleantech / Semiconductors** and **Health** is recommended, considering their substantial historical funding and growth potential.

## Conclusion

By leveraging the insights gained from this analysis, Spark Funds can make informed decisions and strategically allocate investments to maximize returns and achieve its business objectives.
