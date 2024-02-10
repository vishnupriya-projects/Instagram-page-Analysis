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

### Analysis and Insights:
#### 1. Basic statistics of data:
- Followers:	106100
- Total Page Reach:	7206419
- No. of Visits:	171877
- New Followers:	61166
- Total Impressions:	9130594
- Engagement Rate:	9%
- Growth Rate:	1%
- Retention Rate:	42%
#### 2. Engagement across different post types

![image](https://github.com/vishnupriya-projects/Instagram-page-Analysis/assets/159273003/6692002d-77ea-47a9-a91f-b2817652d10c)

From above analysis it was clear that reels are contributing more impressions, reach & shares & more engagement rate with users followed by carousel & image type posts.
observation: The content posted in form of REELS was attracted by more users than image posts.


#### 3. Retention rate, Engagement rate analysis based on duration bucket

![image](https://github.com/vishnupriya-projects/Instagram-page-Analysis/assets/159273003/d1d6cd95-3ba7-4adf-8128-d94826c8d81e)

From above table, if we divide data of above 30s & below 30s, impressions, reach, and engagement rate are more for > 30 s reels but retention rate was least. 
Observation:
- If impressions & reach need to increase then 50 s reels can be preferred.
- If retention rate i.e., the posted content needs to watch till end, below 20s reels can be preferred.
- To increase engagement rate, 40-50 sec reels can be preferred.

#### 4. Analysis of impressions







#### 2. Engagement across different post types



#### 2. Engagement across different post types



#### 2. Engagement across different post types





