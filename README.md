# Assignment-F-Market

##U.S. Strawberry Market Analysis (1998–2024)

####Overview

This project analyzes long-term trends in the U.S. fresh strawberry market using official data from the USDA National Agricultural Statistics Service (NASS).
The analysis focuses on three core economic dimensions — price, supply, and market value — to explore how these variables have evolved over time and how they interact across states and years.
All data were cleaned, standardized, and merged into a single consistent dataset for exploratory data analysis (EDA) and visualization.

####Goal

The primary goal of this project is to:
Examine national and state-level patterns in strawberry prices, production, and market value;
Identify long-term trends and fluctuations in the U.S. strawberry sector;
Highlight regional differences between key producing states such as California, Florida, Oregon, and North Carolina;
Provide an integrated overview of the economic structure and sustainability of the strawberry industry.

####Data Sources

All datasets were obtained from the USDA NASS Quick Stats database:
Fresh Market Strawberries (Commodity Code: STRAWBERRIES)
Variables: Price Received ($/CWT), Production (CWT), and Value of Production (USD)
Coverage: 1998–2024 (national and state level)
Units: CWT = hundredweight (100 pounds)
Data were filtered for “State” = U.S. Total and key strawberry-producing states.

####Methodology

Data Cleaning and Integration
Selected relevant columns (Year, State, Data Item, Value)
Removed withheld data marked as (D) or (Z)
Converted numeric strings (e.g., “1,234,000”) into numeric format
Filtered missing and zero values
Merged datasets by year to form a single integrated dataset
Aggregated production and value across states and years
Visualized trends using ggplot2 with consistent color themes

####Analysis and Findings

1. Market Price

U.S. strawberry prices have risen steadily from the late 1990s to 2024, increasing from around $85 to $140–150 per CWT.
Prices peaked between 2010–2015 and declined slightly around 2019–2020, likely due to market oversupply or climate impacts.
State-level analysis shows Oregon consistently commands higher prices than North Carolina, reflecting regional market differentiation.

2. Market Supply

National production increased significantly through the 2000s, with notable peaks in 2009–2010 and 2017.
California dominates national output, followed by Florida and North Carolina.
The “Other States” category shows a small but steady rise, suggesting gradual diversification of production regions.

3. Market Value

The total U.S. strawberry market value shows a strong long-term upward trajectory from 1998–2024.
Despite temporary dips around 2017 and 2020, recent years indicate recovery and sustained growth.
California remains the economic center, accounting for the majority of total market value, emphasizing both its strength and dependence within the national strawberry economy.

####Summary

Across price, supply, and value, the U.S. strawberry market exhibits long-term growth with short-term volatility.
Production expansion and increasing value underscore the crop’s economic importance, while fluctuations reflect challenges from climate variation, labor, and market forces.
California’s continued dominance highlights both regional concentration and the need for diversification to maintain national stability in strawberry production.

####Conclusion

The analysis reveals a dynamic and resilient U.S. strawberry industry characterized by:
Rising long-term prices and market value
Production leadership by California
Regional price variation and supply imbalance
Growing but uneven national diversification
Overall, the findings indicate that the U.S. strawberry sector remains economically strong yet regionally concentrated, with future sustainability hinging on adaptation to market and environmental pressures.
