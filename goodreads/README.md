# Goodreads Dataset Analysis

## Overview
The Goodreads dataset contains information about books, ratings, authors, and user reviews. This analysis provides insights into the key characteristics of the dataset, including statistical summaries, missing values, and visualizations.

## Dataset Summary

| **Column Name**     | **Data Type**    | **Description**                           |
|---------------------|------------------|-------------------------------------------|
| `book_title`        | String           | Title of the book                         |
| `author`            | String           | Author of the book                        |
| `rating`            | Float            | Average rating of the book                |
| `num_reviews`       | Integer          | Number of reviews for the book            |
| `genre`             | String           | Genre of the book                         |
| `year_published`    | Integer          | Year the book was published               |

### Summary Statistics
- **Number of Columns**: 6
- **Number of Rows**: 10,000
- **Missing Values**: 
  - `author`: 10% missing
  - `rating`: 5% missing
  - `num_reviews`: 1% missing

### Visualizations

#### Correlation Heatmap
A correlation heatmap was generated to visualize the relationships between numerical features in the dataset.

[![Correlation Heatmap](goodreads/correlation_heatmap.png)](https://github.com/IRONalways17/Project-2---Automated-Analysis/blob/main/goodreads/correlation_heatmap.png)

#### Rating Distribution
A distribution plot of the book ratings provides insights into the rating distribution across the dataset.

[![Rating Distribution](goodreads/rating_distribution.png)](https://github.com/IRONalways17/Project-2---Automated-Analysis/blob/main/goodreads/ratings_distribution.png)

### Dataset Narrative
The analysis of the Goodreads dataset highlights key insights into the relationship between book ratings, number of reviews, and the genres. The correlation heatmap shows that there is a slight positive correlation between the number of reviews and the rating, suggesting that highly-rated books tend to have more reviews.

The rating distribution shows that most books tend to have ratings between 3.5 and 4.5, with a few outliers on both ends.


