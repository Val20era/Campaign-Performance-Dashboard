# Performance Marketing Dashboard (Power BI)

Dataset is based on anonymized real-world paid media performance data across Google, Facebook, and TikTok.

## What This Project Demonstrates

- Marketing performance analysis
- KPI-driven dashboard design
- Business-oriented data storytelling
- Power BI data modeling and DAX skills
  
## Business Context

This dashboard was built to monitor paid acquisition performance across Facebook, Google, and TikTok.

The goal was to:
- Track marketing efficiency (CPA, ROAS)
- Identify top-performing campaigns and ads
- Analyze conversion trends by platform
- Support budget reallocation decisions

## Metrics

- CTR, CPC
- CVR, CPA, CR
- ROAS, RPC
- CPM, Frequency
- Engagement Rate
- Video View Rates (25%, 50%, 75%, 100%)
- Quality Score, Search Impression Share

## Dashboard Structure

1. KPI overview section — high-level performance metrics
2. Campaign breakdown — top campaigns by selected metric
3. Ad-level performance — granular efficiency analysis
4. Trend analysis — daily performance trends by platform
5. Dynamic metric selector to switch between Conversions, Revenue, Spend

## Key Insights

- TikTok drives the highest conversion volume but has volatile CPA.
- Google campaigns show the most stable ROAS.
- Influencer_Collab campaign contributes 28% of total conversions.
- Retargeting campaigns demonstrate the highest CVR.

## Technical Implementation

- Dynamic metric selector using disconnected table
- Top N filtering with dynamic sorting
- Time intelligence (WoW comparison)
- Conditional formatting for KPI growth
- Drill-through functionality for ad-level analysis
