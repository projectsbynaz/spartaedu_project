# California Housing Data Exploration – Visualising with Seaborn

**Credit:** Nazia Malakzi 
**Course:** Sparta Education – Python for Data Skills Sprint, September 2025

## Overview
This project explores the California housing dataset using Seaborn to visualise relationships between key housing factors. The analysis emphasises properties in the Bay Area compared to other areas of California based on proximity to the Pacific Ocean, examining differences in geographic distribution, house values, population, household size, income, and age of the main householder.

## Key Findings

### Property Values & Regional Differences
From the house values KDE plot, Bay Area properties show their highest concentration around the $200K mark, while inland properties peak around $100K. This represents a **100% price premium** for Bay Area location. The Bay Area distribution also has a wider price range with a longer 'tail' toward higher values, extending up to $500-600K, showing the area has both affordable and luxury segments.

### Geographic Distribution Patterns  
The scatter plot clearly shows the Bay Area has dense clustering of properties in a small geographic area, while near ocean properties are more spread out across larger coastal territories. This clustering indicates high competition and limited supply in the Bay Area market.

### Housing Age Analysis
Looking at the housing age boxplot, 50% of Bay Area homes fall between 29-54 years old (the interquartile range shown by the box edges). Near ocean areas tend to have newer housing stock, while the Bay Area shows older housing stock. There's a weak correlation between housing age and income in inland areas, likely due to various factors like local policies, development timing, and geographic constraints.

### Population & Household Patterns
The population vs households scatter plot shows consistent household formation patterns across all geographic types with a linear positive correlation. This suggests stable demographic trends regardless of location proximity to the ocean.

## Investment Insights

### Where to Invest
- **Bay Area**: Higher entry cost (2x premium) but shows properties extending to $500K+, indicating strong appreciation potential
- **Inland Areas**: Lower entry point around $100K with potential to reach Bay Area pricing levels over time
- **Near Ocean**: Middle-tier opportunity between inland and Bay Area pricing

### Market Gaps Identified  
- **Renovation Opportunities**: With 50% of Bay Area homes being 29+ years old, there's significant potential for value-add through updating older housing stock
- **Geographic Arbitrage**: The 100% price gap between Bay Area and inland creates clear investment strategy differences
- **Supply Constraints**: Dense Bay Area clustering with limited geographic area creates natural scarcity pricing

## Motivation
Having spent a lot of time in California before, especially around the Bay Area and other parts of Northern California, I enjoyed connecting the dataset to real-world observations. My experience in real estate helped me interpret the visualisations in a practical context, while the dataset may not reflect exact current values, it still provides valuable insights into housing patterns and trends.

## Visualisations Included
1. **Geographical Distribution of Housing**: Scatter plot showing the location of properties by ocean proximity, highlighting Bay Area clustering.
2. **House Values by Location**: KDE plot showing that Bay Area properties tend to have higher values compared to other regions.
3. **Housing Median Age by Location**: Boxplot comparing the age distribution of houses in Bay Area vs other areas.
4. **Pair Plot: Housing Age vs Median Income**: Explores how income and housing age relate across areas, with emphasis on the Bay Area.
5. **Population vs Households**: Scatter plot showing population density and household size differences by location.

## Personal Takeaways
* The Bay Area clearly stands out in terms of higher property values, median income, and unique housing characteristics. Being a scarce location, there is higher demand.
* Dense geographic clustering creates both opportunities (undervalued adjacent areas) and risks (market concentration)
* The data shows clear market segmentation - Bay Area, coastal, and inland represent distinct investment strategies
* Combining data analysis with personal experience made the project engaging and insightful.

## Data Considerations
While this dataset provides valuable insights into housing patterns and regional relationships, it represents historical data rather than current market conditions. The analysis demonstrates methodology for identifying market premiums and geographic investment opportunities that can be applied to updated datasets.

## Fun Note
If you ever visit San Francisco, don't miss *Half Moon Bay Beach*, one of my personal *favourite* beaches along the California coast.
