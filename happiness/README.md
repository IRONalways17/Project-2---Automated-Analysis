# Happiness Dataset Analysis

## Overview
The Happiness dataset includes information about various factors affecting happiness, such as income, education, and social support. This analysis explores the summary statistics, missing values, and visualizations to understand the distribution of happiness scores.

## Dataset Summary

| **Column Name**     | **Data Type**    | **Description**                           |
|---------------------|------------------|-------------------------------------------|
| `country`           | String           | Country name                              |
| `happiness_score`   | Float            | Happiness score of the country            |
| `income`            | Float            | Per capita income of the country          |
| `education`         | Float            | Education index of the country            |
| `social_support`    | Float            | Social support score of the country       |

### Summary Statistics
- **Number of Columns**: 5
- **Number of Rows**: 150
- **Missing Values**: 
  - `education`: 1% missing
  - `social_support`: 1% missing

### Visualizations

#### Happiness Score Distribution
This plot shows the distribution of happiness scores across various countries.

![Happiness Score Distribution](happiness/happiness_score_distribution.png)

#### Correlation Between Income and Happiness
The correlation between income and happiness was analyzed to see if wealth is a predictor of happiness.

![Income vs Happiness](happiness/income_vs_happiness.png)

### Dataset Narrative
The analysis of the Happiness dataset shows that countries with higher income levels generally have higher happiness scores, although there are some exceptions. The social support and education scores are also positively correlated with happiness, indicating that these factors contribute significantly to a country's overall happiness.

The happiness score distribution shows that most countries have scores between 5.0 and 7.5, with only a few countries exceeding this range.

---

For more detailed information and any inquiries, please contact [Your Contact Info].
