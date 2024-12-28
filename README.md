# Citi Bike Ride Duration Analysis

## Project Overview
This project analyzes ride duration patterns from Citi Bike, a major bike-sharing service in New York City. By investigating factors such as membership type, bike type, starting locations, and weekdays, the project seeks to provide actionable insights to optimize Citi Bike operations, enhance user satisfaction, and improve urban mobility.

## Key Objectives
1. **Membership Type Analysis**: Examine the differences in ride duration between subscribers and casual users.
2. **Bike Type Comparison**: Evaluate the effect of electric vs. classic bikes on ride duration, accounting for the day of the week.
3. **Regional Analysis**: Investigate how ride duration varies across different starting locations in NYC.
4. **Central Park Focus**: Identify significant factors influencing ride duration in Central Park, given its unique usage patterns.

## Data
- **Source**: Citi Bike official dataset.
- **Scope**: October 1–14, 2024 (partial dataset for computational efficiency).
- **Size**: 2.3M+ rows, cleaned and preprocessed to remove outliers and inconsistencies.

## Methods
- **Exploratory Data Analysis**: Visualized seasonal usage patterns and identified key variables (e.g., membership type, bike type).
- **Statistical Modeling**: Conducted t-tests, ANOVA, and linear regression to analyze the effects of various factors on ride duration.
- **Clustering**: Used spatial clustering to categorize NYC regions for regional analysis.

## Results
- **Membership Insight**: Casual users have longer rides compared to members, likely due to differing usage purposes.
- **Bike Preference**: Electric bikes are favored for longer trips, while classic bikes dominate shorter rides.
- **Regional Variations**: Central Park has the longest average ride durations; Queens and Uptown NYC have the shortest.
- **Model Limitations**: A multivariate linear regression model explained only 2.4% of Central Park ride duration variance, suggesting the need for alternative modeling approaches.

## Future Directions
- Explore advanced machine learning models (e.g., decision trees, gradient boosting) for better predictive performance.
- Incorporate a larger dataset spanning a year or more for more robust insights.
- Use big-data tools (e.g., Spark) to process the complete Citi Bike dataset.

## Repository Structure
```
├── Projecy.Rmd             # R Markdown file of all the codes of the project
├── Project Report.pdf      # Formal report of the analysis
└── README.md               # Project overview
```

## Dependencies
- R packages: `tidyverse`, `ggplot2`, `sf`, `mapview`, `tidygeocoder`.
