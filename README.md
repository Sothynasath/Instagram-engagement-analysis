# Instagram-engagement-analysis
Google sheet-based analysis of Instagram insights to identify where content loses audience attention across the engagement funnel (impressions, reach, likes, comments) using data cleaning, pivot tables, and visual storytelling. Determine which content strategies maximize monetization potential. 

## Project Overview
This project analyzes Instagram post-level performance data to identify where audience engagement drops off across the content engagement funnel. The goal is to understand which content behaviors drive deeper engagement and how these insights can be used to improve business outcomes such as reach efficiency, audience retention, and monetization potential.

## Business Objective
Identify engagement drop-off points from impressions to deeper interactions (likes, comments, saves, shares) and determine which content types minimize audience loss.

## Key Questions
- Where does engagement decline most frequently across the Instagram funnel?
- Which content types sustain deeper engagement?
- How does engagement quality differ between high- and low-performing posts?

## Data Source
This project uses a publicly available Instagram post-level analytics dataset obtained from Kaggle. The dataset includes the following fields: upload_date, media_type, likes, comments, shares, saves, reach, impressions, caption_length, hashtags_count, followers_gained, traffic_source, engagement_rate, and content_category. The data is anonymized and contains no personally identifiable user information.

## Metrics Created
- Like Rate = Likes / Reach
- Comment Rate = Comments / Reach
- Save Rate = Saves / Reach
- Share Rate = Shares / Reach
- Funnel Drop-Off Rates between engagement stages

## Methodology
1. Cleaned raw Instagram analytics data using Excel
2. Created derived engagement and drop-off metrics
3. Built pivot tables to analyze performance by content type and time
4. Visualized engagement funnels and drop-off behavior
5. Interpreted insights through a business and revenue lens

## Key Findings
- High impressions do not guarantee deeper engagement
- Carousel posts tend to retain higher save and share rates
- Reels generate strong reach but experience higher mid-funnel drop-off
- Top-performing posts reduce early funnel drop-off significantly

## Business Impact
Understanding engagement drop-off helps marketing teams optimize content strategy to improve algorithmic visibility, brand partnerships, and ad performance. Sustained engagement increases audience value and long-term revenue potential.

## Tools Used
- Google Sheets (formulars, pivottables, charts) 
- Pivot Table analysis for engagement funnel comparison
- Data Cleaning & Transformation (handling missing values, formatting metrics, creating derived KPI's) 
- Visual Analytics and chart-based storytelling 

## Next Steps
- Add time-series engagement trend analysis to monitor performance over time
- Build churn-risk proxy based on declining engagement and flag content where enagagment drop is at a high risk
- Expand analysis to user-level data if available for a deeper analysis 
