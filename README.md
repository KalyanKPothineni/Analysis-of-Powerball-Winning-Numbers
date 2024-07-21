# Analysis of Powerball Winning Numbers

This project analyzes Powerball winning numbers to identify patterns, frequency, and trends from 2010 onwards. The goal is to understand the distribution of lottery outcomes and provide statistical insights for better number selection.

## Project Overview

### Purpose
- Analyze historical Powerball numbers to identify patterns and trends.
- Provide insights into the randomness of lottery draws.

### Data Sources
- [Data.gov](https://catalog.data.gov/dataset/lottery-powerball-winning-numbers-beginning-2010)
- [Powerball Official Site](https://www.powerball.com/)

## Data Preparation
- Convert `Draw Date` to datetime format.
- Split `Winning Numbers` into separate columns for each ball.
- Handle missing values in the `Multiplier` column.
- Convert numerical values to appropriate data types.

## Analysis Methods
- **Frequency Analysis:** Identify common numbers, pairs, triples, etc.
- **Trend Analysis:** Visualize the number of draws by year.
- **Pattern Recognition:** Heatmap for co-occurrence of white ball numbers; scatter plots for draw dates vs. winning numbers; K-means clustering.
- **Distribution Analysis:** Box plots and time series decomposition.

## Tools and Libraries
- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Statsmodels

## Key Findings
- Frequently appearing numbers include 36, 39, and 23.
- Common pairs such as (37, 44) and (41, 59) were identified.
- K-means clustering showed groupings of similar draws.

## Assumptions and Limitations
- The dataset is accurate and comprehensive.
- The drawing process is random and unbiased.
- Historical patterns may not predict future draws.

## Ethical Considerations
- Ensure unbiased interpretation and responsible messaging.

## References
- [Data.gov Powerball Winning Numbers](https://catalog.data.gov/dataset/lottery-powerball-winning-numbers-beginning-2010)
- [Powerball Winning Numbers History](https://www.powerball.com/)

