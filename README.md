# Instagram-Page-Analysis: Unlocking the data-driven Instagram page analysis across various post types on Data Analyst Duo's Instagram

### Brief Introduction:
This report helps to provide insights of Instagram engagement analysis and performance of different post types on Data Analyst Duo's Instagram account (@dataanalystduo) with approximately 106,000 followers.

### Objective: 
To analyze the data driven Instagram engagement analysis to gain insights into the performance of different post types on Data Analyst Duo's Instagram account.

### Data Cleaning and Prepartion:
The raw data available for this analysis is in 2 types:
- The type of post, likes, shares, comments, description, impressions, reach, post links etc., was available from 01/12/2022 to 27/10/2023 considered as table 1.
- The Instagram reach, new followers visit & no. of new followers’ daily data was available from 9/01/2022 to 27/10/2023.
- These above columns (Instagram reach, new followers visit & no. of new followers’) are joined together using V lookup and total followers were calculated based on present date followers count i.e, by the date of 27/10/2023, total followers count is 106031, total sum of new followers from 01/12/2022 to 27/10/2023 is 92186.
- The followers count on 01/12/23 is (106031 – 92186) = 13845.
- New followers will add based on current follower’s count considered as table 2.
- Then all the available data(table 1 & 2) was combined (based on possible joins) using v loop up of dates for easy analysis and was considered from 01/12/2022 to 27/10/2023 for further analysis.
Few new columns are added for further analysis:
1. Engagement rate:
- Interaction to each type of post by the users. It can be measured based on likes, shares, comments and saves of particular post.
- Engagement rate% = (sum of likes, shares, comments and saves) *100/ (No. of followers)
2. Growth Rate:
- The number of followers gained over a period of time.
- Growth rate = (Followers on last day – Followers on first day) *100 / Followers on first day.
3. Retention rate:
- It was calculated to identify the % users are having greater than 3s views.
- Retention rate % = No. of 3s views/impressions.
4. Duration bucket and Impressions bucket:
  - duration above 50s	Below 1 lac
  - duration b/w 20-30s	1 -2 lac
  - duration b/w 30-40s	2-3 lac
  - duration b/w 40-50s	3-4 lac
  - duration below 20s	Above 4 lac

## Instagram-page-Analysis

### Instagram-page-Analysis
