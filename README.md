# First-Street-Foundation
Work folder for machine learning project with First Street Foundation. Use Ridge, LASSO, GB and random forest to model property values in south Florida with administrative data.
## Executive summary
Objective
 - Organizational mission: Quantify the financial risk of tidal flooding to address stakeholder concern
 - Task for this research: Make the numbers more accurate with market value estimation

Data
 - Administrative property records (3 million), transaction records from ATTOM Data Solutions
 - Demographic data from census data
 - Flooding projections and other climate data from National Oceanic and Atmospheric Administration (NOAA) 
 
Methodology
 - Build seperate models within each city and county to account for geographical variation and improve data quality
 - Regularization models (Ridge, LASSO) as baseline
 - Regression trees ry random forest and gradient boosting as comparison for trial models

Findings
 - Trees work better than baseline
 - Random forest algorithm consistently outperform gradient boosting
 - City-level models have varying performance
 - Ability to predict within 10% deviation in some cities
 - Key filtering parameters should be optimized to improve prediction
 - Transaction time and building area are 2 primary factors of property value
