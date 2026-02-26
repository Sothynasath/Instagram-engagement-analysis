# Analysis Steps (Google Sheets)

## Goal
Identify which content behaviors are engagement drivers and where drop-offs occur in the Instagram engagement funnel.

## Cleaning Steps
1. Import raw CSV into Google Sheets
2. Standardize column names using (snake_case) formatting
3. Convert date fields to proper datetime format for consistency
4. Remove duplicates where necessary
5. Identified blanks/zero values and documented handling assumptions
6. Create calculated fields to evaluate engangement quality.
   - engagement_rate = (likes + comments + saves + shares) / impressions
   - save_rate = saves / impressions
   - follow_rate = follows / reach

## Analysis
- Built pivot tables segmented by media type to compare performance patterns
- Constructed engagement funnel comparisons to identify behavioral drop-off stages
- Ranked media formats by performance to isolate high-retention content strategies

