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

![image](https://github.com/vishnupriya-projects/Instagram-page-Analysis/assets/159273003/808ff775-828e-49f3-8087-5233257a39bf)

From above table, almost all type of posts are contributing below 1 lac impressions, to improve impressions various factors such as reel type, its duration and key words need to improve further.

#### 5. Keyword’s identification based on description of post at various impressions
By using word cloud generator, the following key words are identified.

![image](https://github.com/vishnupriya-projects/Instagram-page-Analysis/assets/159273003/7d7f2c4e-9f7a-48ea-b5c8-bc72e7539e8f)


Major keywords: DATA, DATASCIENCE, DATAANALYTICS, STATISTICS, PROJECTS, PYTHON, SQL & JOB these are few majorly used key words used to reach more followers. 
Key words based on impressions: 

![image](https://github.com/vishnupriya-projects/Instagram-page-Analysis/assets/159273003/ec0348b9-eb3a-486e-b198-d1a83001abb4)

If we see major impressions was there for key words related to COURSES, BIG DATA, JOB & INTERVIEW related content in data science & analytics.

#### 7. HYPOTHESIS ANALYSIS
1. Relation b/w Instagram reach, followers visit & new followers:
   
![image](https://github.com/vishnupriya-projects/Instagram-page-Analysis/assets/159273003/cea490ac-fcc6-4fc3-9fc7-f5511f673004)

- From the above scatter plot, we can see that points are moving in forward direction, so there is a positive correlation b/w instaram reach, followers visit and new followers.
- If instagram reach increseres there can be potential increase in followers visit & to new followers.
2. Relation b/w Instagram reach, Impressions:
- From below scatter plot, we can see that points are moving in forward direction, so there is a positive correlation b/w instagram reach and no of impressions.
- If impressions for posts increses, instagram reach also increses or vice-versa.

![image](https://github.com/vishnupriya-projects/Instagram-page-Analysis/assets/159273003/7b3d2acd-6e8b-4611-843d-9b5ea4d2f7c3)

3. Relation b/w followers vs enagement rate, followers vs retention rate:
- From the below chart, we see that points are moving in forward direction, so there is a positive correlation b/w  total no of followers and enagement rate.
- As enagement rate increses the followers count also increses or vise-versa.

   ![image](https://github.com/vishnupriya-projects/Instagram-page-Analysis/assets/159273003/482edd35-99e3-4eb1-b650-9cd2a12e6da6)

- From below chart we see that no of followers count & retention rate are moving in positive direction.
- As Retention rate for IG REELS increses the followers count also increses or vise-versa.

  ![image](https://github.com/vishnupriya-projects/Instagram-page-Analysis/assets/159273003/212bf62c-3a5c-4ee8-b961-5a10076e8b23)

4. Word Count vs Enagement Rate:

   ![image](https://github.com/vishnupriya-projects/Instagram-page-Analysis/assets/159273003/be89364a-3c8f-4b06-a898-3aa02a2ce568)

Approximate word count was calculated from the captions data available in excel.
Formula used to calculate the word count by subtracting total length with length having spaces and as follows:
- Word count = Len(description) – Len(substitute(description, “  “, “”)).
From above graph we see that word count was dispersed and there is no relation b/w word count and engagement rate.


#### 8. Age Group analysis
- From below table, if we see that age group b/w 25-34 yrs have more followers followed by 18-24 yrs and least by 65+ yrs.
- Men followers are more compared to female.
- This means most people are at higher studies/in other jobs looking for transitions/upgrading themselves in data science field.

![image](https://github.com/vishnupriya-projects/Instagram-page-Analysis/assets/159273003/c7b6faac-4704-4bd0-8336-f31c29ff62ad)

#### 9. City and Country wise analysis
- From below table we see that from INDIA has more followers followed by USA.
- In India Bangalore city holds more followers followed by Chennai, Hyderabad, Delhi & Mumbai. 

![image](https://github.com/vishnupriya-projects/Instagram-page-Analysis/assets/159273003/d2409fec-9454-4089-9ce6-0c5c57bdd834)


### Recommendations
- Most of the followers are belongs to INDIA, USA specially from Bangalore region in INDIA.
- According to gender wise 25-34 age group people are the more followers and majority are male.
- IG Reels are contributing high impressions, reach, followers and engagement rate than other type of posts.
- Among reels, below 20s reels has high retention rate, 40-50 sec reels has more engagement rate & >50 s videos have high retention rate.
- From hypothesis analysis, there was a relation b/w no. of followers with engagement rate and retention rate.
- As engagement rate & retention rate increases, followers count also increases.
- The overall impressions for majority no of posts are < 1 lac, to increase Instagram reach & followers impressions play major role which needs to increase.
- The captions used in various type of posts has no relation with engagement rate.
- More impressions are received for key words related to jobs, interview preparation, BIG DATA, data science related COURSES like python, statistics and excel, AI etc.
- To improve more impressions the content related to above mentioned key words need to increase.

### Acknowledgement

-Thanks to dataanalystduo team, for providing the data and Special thanks to kalpesh for your guidence through out the project.



