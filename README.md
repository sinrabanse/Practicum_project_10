# Practicum_project_10
 My tenth project from Practicum course. "Presentation and Dashboard using Tableau"

 What was used in the project: Tableau, PowerPoint.

# Project Description

I work as a video ad analyst at the Sterling & Draper advertising agency. I devote a lot of time to analyzing trending videos on YouTube to determine what content deserves marketing attention. Each video has a specific category (Entertainment, Music, News & Politics, etc.), region, and trending date. A video can be in the trending section for several days in a row.

Every week I need to answer the same questions:
   - What video categories were trending last week?
   - How were they distributed among various regions?
   - What categories were especially popular in the United States?

After a short meeting with managers, we came to the conclusion that the dashboard should have the following draft:<br/>
![Draft for dashboard](https://github.com/sinrabanse/Practicum_project_10/raw/main/Draft_for_dashboard.png)

# Steps
1) In Tableau Public, use  trending_by_time.csv to create a dashboard modeled on the draft.
2) Publish the dashboard on the Tableau Public server.
3) Use your dashboard to answer the questions the managers asked me:
   - Which video categories trended most often?
   - How were they distributed among regions?
   - What categories were especially popular in the United States? Were there any differences between the categories popular in the US and those popular elsewhere?
   - Prepare a brief presentation containing a report (answers to these questions and graphs).

# Description of the data

Data is stored in file trending_by_time.csv

Columns:

'record_id' — primary key<br/>
'region' — country/geographical region<br/>
'trending_date' — date and time<br/>
'category_title' — the video category<br/>
'videos_count' — the number of videos in the trending section
