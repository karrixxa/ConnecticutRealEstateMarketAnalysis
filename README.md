# Connecticut Real Estate Market Analysis

This project analyzes Connecticut real estate sales from 2001–2023 to understand how housing prices, municipal assessments, property types, and market shocks changed over time.

Using real estate sales data from the Connecticut Open Data Portal, we explored long-term market trends, differences across towns, assessment accuracy, and the effects of major events such as the 2008 housing crisis and the post-COVID housing boom.

## Overview

The main research question was:

How have real estate prices and municipal assessments in Connecticut changed from 2001 to 2023, and what do these patterns reveal about market trends across time, property types, and towns?

We focused on questions such as:

- How did housing prices change from 2001–2023?
- How did the 2008 recession and post-COVID market boom affect sales?
- How closely do assessed values match actual sale prices?
- Do higher-value homes show weaker assessment accuracy?
- How do trends differ across towns and property types?

## Data

The main dataset came from the Connecticut Open Data Portal’s Real Estate Sales 2001–2023 data. It includes property transactions of $2,000 or greater reported by municipalities across Connecticut.

Key variables included:

- List year
- Town
- Sale amount
- Assessed value
- Sales ratio
- Property type
- Residential type
- Date recorded
- Assessor and OPM remarks

We also used supplementary population and income datasets to support town-level analysis.

## Data Cleaning

Data cleaning and preprocessing included:

- Removing incomplete records with missing sale amount or assessed value
- Filtering missing property types
- Removing extreme sales ratio outliers
- Reformatting recorded dates
- Cleaning and standardizing town names
- Merging real estate data with population and income data
- Using text mining on assessor and OPM remarks to identify distressed transactions such as foreclosures, short sales, and bank-owned properties

## Analysis

The project included several visual and statistical analyses:

- Property type distribution across major cities
- Median sale price comparisons across top towns
- Sales volume by residential type
- Monthly and yearly seasonality in sales
- Great Recession impact on high-end markets
- Post-crisis sales volume and average price by town
- Assessed value vs. sale amount analysis
- Post-COVID housing price trends
- Foreclosure and short-sale patterns over time

## Key Findings

Connecticut’s housing market showed strong seasonal patterns, with higher sales activity in summer and lower activity in winter.

The 2008 housing crisis caused widespread price declines and lower transaction volume. Distressed sales such as foreclosures and short sales increased sharply during this period.

After 2020, housing prices rose quickly across major cities and property types, especially for multi-family homes.

Municipal assessed values generally predicted sale prices, but assessment accuracy weakened for higher-value properties. This suggests that expensive homes may be more likely to be under-assessed relative to their market value.

## Tools

- R
- SQL
- ggplot2
- dplyr
- Data cleaning
- Data visualization
- Regression analysis
- Text mining

## Contributors

- JC Cheng
- Charis Xiong
- Rahul Santhanam
- Kyle Leung

## Acknowledgments

Data was sourced from the Connecticut Open Data Portal.
