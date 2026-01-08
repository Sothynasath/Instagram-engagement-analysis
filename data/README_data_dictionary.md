# Data Dictionary — Instagram Engagement Analysis

## Dataset Overview
This dataset contains post-level Instagram analytics used to analyze engagement performance and audience drop-off across the content funnel.

## Files
- `raw/RawInstagram_Analytics.csv` — Original exported dataset (unchanged)
- `cleaned/instagram_cleaned.csv` — Cleaned dataset used for analysis

## Column Definitions
| Column | Description |
|------|------------|
| post_id | Unique identifier for each post |
| post_date | Date the post was published |
| impressions | Total times the post was shown |
| reach | Unique accounts reached |
| likes | Total likes |
| comments | Total comments |
| saves | Total saves |
| shares | Total shares |
| profile_visits | Profile visits from post |
| follows | Follows gained from post |
| media_type | Image, Reel, or Carousel |
| traffic_source | Home, Explore, Profile, Hashtags |

## Notes
Cleaning steps and assumptions are documented in the analysis folder.
