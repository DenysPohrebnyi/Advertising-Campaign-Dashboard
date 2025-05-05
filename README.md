# Advertising Campaign Performance Dashboard

Project Link: [Looker Studio Dashboard](https://lookerstudio.google.com/reporting/1ec1191f-7f40-4fd2-a525-2031284b069b/page/9q93E)

## Overview

This project presents a performance dashboard built in Looker Studio for analyzing advertising campaigns across Google Ads and Facebook Ads. The dashboard consolidates key metrics such as impressions, clicks, CTR, conversions, and cost-efficiency to support marketing team decisions.

## Objective

The client needed a unified and intuitive dashboard to monitor and compare campaign performance across advertising platforms. The goal was to enable real-time insight into ROAS and conversion trends, and to quickly identify underperforming campaigns.

## Timeline

- Start Date: March 4, 2025  
- End Date: March 25, 2025  
- Duration: 3 weeks

## Project Stages

1. Requirement Gathering
   - Defined business questions and KPIs with marketing stakeholders.
   - Determined platform-specific nuances (Google vs Facebook).

2. Data Preparation
   - Used PostgreSQL via DBeaver to clean and transform campaign data.
   - Applied CTEs, JOINs, and UNIONs to merge datasets and standardize metrics.
   - Exported cleaned datasets to Google Sheets for use in Looker Studio.

3. Dashboard Development
   - Designed an interactive dashboard in Looker Studio.
   - Included filters by channel, campaign name, and date range.
   - Visualized key marketing KPIs:
     - Impressions
     - Clicks
     - CTR
     - Conversions
     - Cost per Conversion
     - ROAS

4. Testing & Review
   - Conducted feedback sessions with the marketing team.
   - Iterated on usability and added custom filters for campaign groups.

5. Final Delivery
   - Delivered the dashboard with user training and metric documentation.

## Tech Stack

- Data Preparation: PostgreSQL (CTE, JOIN, UNION) via DBeaver  
- Visualization: Looker Studio (Google Data Studio)  
- Storage: Google Sheets (as data layer for Looker Studio)
