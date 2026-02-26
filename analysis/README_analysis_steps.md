# Analysis Steps (Google Sheets)

## Goal
This document outlines the full analytical workflow used to prepare, transform. and analyze the dataset with the objective to determine which content behaviors are engagement drivers and where interaction declines across the engagement funnel.

## Data preparation
Source Import
- Import raw CSV into Google Sheets
Standardization
- Standardize column names using (snake_case) formatting
- Convert date fields to proper datetime format for consistency
- Remove duplicates where necessary, ensure numeric fields were stored as values rather than text
  
Data Intergrity Checks
- Identified blanks/zero values and documented handling assumptions
- Create calculated fields to evaluate engangement quality.
   - engagement_rate = (likes + comments + saves + shares) / impressions
   - save_rate = saves / impressions
   - follow_rate = follows / reach

## Analytical Process
**Aggregation** 
- Constructed pivot tables grouped by media_type
- Calculated averages for engagement metrics across formats
**Comparative Analysis**
- Compared performance across content formats
- Evaluated variance between engagement depth levels
**Funnel Modeling**
- Built interaction funnel metrics to identify where engagement declines
- Compared early-stage vs late-stage interaction behavior
**Performance Ranking**
- Ranked content formats by engagement efficiency
- Identified formats associated with stronger retention signals

 **Analytical Assumptions**
- Impressions were treated as the denominator for engagement metrics to standardize comparison across posts
- Rows with missing core performance metrics were excluded from aggregate calculations
- Engagement behaviors were assumed to represent audience interest levels, with saves/shares indicating stronger intent than likes
