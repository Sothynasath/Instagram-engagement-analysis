# Instagram-engagement-analysis
I built this to figure out what content actually drives meanigful interactions such as shares/saves and not just reach because I want to understand what makes people engage with content rather than skipping past it. Using data cleaning, pivot tables, and visual storytelling I explored patterns in engagement behavior to determine which content strategies are most likely to maximize monetization potential. 

## Project Context
This project analyzes Instagram post-level performance data to identify where audience engagement drops off across the content engagement funnel. The goal is to understand which content behaviors sustain deeper engagement and how these insights can inform strategic decisons to improve business outcomes related to efficiency, audience retention, and monetization potential.

## Business Objective
Identify where audience engagement declines across the content interaction funnel and determine which content traits sustain deeper engagement behaviors, particularly as saves and shares.

## Key Questions
- At which stage does engagement decline most frequently across the enagement funnel?
- Which post characteristics correlate to sustain deeper engagement (saves, shares vs likes)?
- How do engagement patterns differ between high- and low-performing posts?

## Data Source
This project uses a publicly available Instagram post-level analytics dataset obtained from Kaggle. The dataset includes the following fields: upload_date, media_type, likes, comments, shares, saves, reach, impressions, caption_length, hashtags_count, followers_gained, traffic_source, engagement_rate, and content_category. The data is anonymized and contains no personally identifiable user information.

## Metrics Engineered
- Like Rate = Likes / Reach
- Comment Rate = Comments / Reach
- Save Rate = Saves / Reach
- Share Rate = Shares / Reach
- Deep Engagement Rate = (Saves+Shares) / Impressions

## Methodology
1. Cleaned raw Instagram analytics data using Excel
2. Engineered new enagement metrics to capture behaviral depth
3. Built pivot tables to analyze performance across media types
4. Modeled engagement funnels to ientify decline patterns
5. Interpreted insights through a business strategy lens

## Key Insights
- High impressions do not guarantee meaningful engagement
- Carousel posts consistently maintain higher save and share rates
- Reels generate strong reach but experience higher mid-funnel engagment loss
- Top-performing posts reduce early funnel decline significantly

## Business Impact
Understanding engagement drop-off helps marketing teams optimize content strategy to improve algoritm performance, stronger audience retention, and higher monetization potential. Content that systains deeper engagment signals greater audience value. 

## Tools Used
- Google Sheets (formulas, pivot tables, charts) 
- Pivot Table analysis for engagement funnel comparison
- Data Cleaning & Transformation (handling missing values, formatting metrics, creating derived KPI's) 
- Visual Analytics and chart-based storytelling 

## Next Steps
- Add time-series engagement trend analysis to monitor performance over time
- Build churn-risk proxy based on declining engagement and flag content where enagagment drop is at a high risk
- Expand analysis to user-level data if available for a deeper analysis 
