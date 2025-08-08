# Sprint 6 - Module 1 Project: Video Game Analysis - Ice

## Project Description

This project marks the conclusion of the first module of the course. The objective is to apply all the skills acquired so far in a real-world case study: analyzing video game sales data to identify success patterns and support strategic marketing decisions.

The online store **Ice** sells video games worldwide. Historical data through 2016 is used to plan a campaign for 2017.

---

## Project Content

- Exploratory data analysis
- Data cleaning and transformation
- Trend visualization
- Hypothesis testing
- Regional segmentation
- Strategic conclusions

---

## Dataset
`games.csv`

Available columns:

- `name`: Video game name
- `platform`: Platform (e.g., Xbox, PlayStation)
- `year_of_release`: Release year
- `genre`: Genre
- `na_sales`, `eu_sales`, `jp_sales`, `other_sales`: Sales by region (in millions of USD)
- `critic_score`: Critic score (0-100)
- `user_score`: User score (0-10)
- `rating`: Rating ESRB

---

## Step 1: Data Preparation
- Rename columns to lowercase
- Convert data types
- Handle missing values (including "TBD")
- Calculate global sales per game

---

## Step 2: Exploratory Analysis

- Games released by year
- Sales by platform and evolution over time
- Identification of leading and emerging platforms
- Analysis of reviews vs. sales
- Distribution of genres and their profitability

---

## Step 3: User Profile by Region
For each region (NA, EU, JP):

- Top 5 platforms
- Top 5 genres
- Impact of the ESRB rating on sales
---

## Step 4: Hypothesis Testing

Hypotheses evaluated:

1. The average user ratings for **Xbox One** and **PC** are the same.
2. The average user ratings for the **Action** and **Sports** genres are different.

- Definition of null and alternative hypotheses
- Selection of alpha value
- Justification of the statistical method used
- Interpretation of results

---

## Step 5: Conclusions

- Summary of key findings
- Recommendations for marketing campaigns
- Reflection on the analytical process

---

## Checklist

- Quality of data cleaning and analysis
- Clarity of visualizations and explanations
- Statistical reasoning in hypothesis testing
- Notebook organization and comments
- Well-founded conclusions

---

## Tools

- Python
- Pandas
- Matplotlib
- Seaborn
- SciPy