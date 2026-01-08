# Analysis Steps (Google Sheets)

## Goal
Identify engagement drivers and where drop-offs happen in the Instagram engagement funnel.

## Cleaning Steps
1. Import raw CSV into Google Sheets
2. Standardize column names (snake_case)
3. Convert date fields to proper date format
4. Remove duplicates (if any)
5. Handle blanks/zeros (document assumptions)
6. Create calculated fields:
   - engagement_rate = (likes + comments + saves + shares) / impressions
   - save_rate = saves / impressions
   - follow_rate = follows / reach

## Analysis
- Pivot tables by media_type
- Pivot tables by traffic_source
- Top posts table by engagement_rate
- Funnel drop-off: impressions → reach → engagement actions

## Output Files
- `data/cleaned/instagram_cleaned.csv`
- `visuals/*.png`
