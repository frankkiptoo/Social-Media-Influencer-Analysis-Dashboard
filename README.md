# Social-Media-Influencer-Analysis-Dashboard

## Summary  
This project presents an end-to-end data cleaning, transformation, and visualization workflow for analyzing social media influencers across **Instagram, Threads, TikTok, and YouTube**.  

The analysis focuses on:  
- Identifying the **Top 5 influencers** by Followers, Engagement Rate, and Potential Reach.  
- Comparing **engagement performance vs follower counts** to uncover the value of micro vs. mega influencers.  
- Highlighting **platform-level performance** through KPIs (Total Influencers, Average Engagement Rate, and Potential Reach).  

The insights generated help brands and marketers make **data-driven decisions** about influencer partnerships and campaign strategies.  

---

## Tools Used  
- **SQL (PostgreSQL)** → Data cleaning, transformations, and standardization (handling nulls, removing emojis, converting follower/reach values, normalizing engagement).  
- **Power BI** → Data visualization and dashboard creation.  
- **DAX** → Calculated measures for KPIs and Top N filtering.  
- **Excel/CSV** → Initial dataset storage and preparation.  

---

## Project Highlights  
- **Data Cleaning:**  
  - Removed special characters, emojis, and duplicate records.  
  - Converted compact numeric formats (e.g., `92.6M`, `327.1K`) into full integers.  
  - Standardized engagement rates by stripping `%` signs and converting to numeric values.  
  - Filled missing values (e.g., engagement rate → 0, topic of influence → mode/unknown).  

- **SQL Transformations:**  
  - Created consistent column naming across all platforms.  
  - Extracted usernames from influencer names.  
  - Removed non-U.S. entries for platform-specific analysis.  

- **Power BI Dashboard:**  
  - KPIs for **Total Influencers, Average Engagement, and Potential Reach**.  
  - **Top 5 Followers** visual to highlight reach concentration.  
  - **Line & Clustered Column Chart** showing Engagement Rate vs Followers.  
  - **Top 5 Potential Reach** visual for campaign targeting.  
  - Platform filter (Instagram, Threads, TikTok, YouTube) for cross-platform insights.  

- **Business Insights:**  
  - Mega influencers = **large reach but low engagement** → great for awareness campaigns.  
  - Micro-influencers = **high engagement with smaller audiences** → great for targeted, community-driven campaigns.
    
- **Screenshot previews:**
  <img width="426" height="360" alt="Image" src="https://github.com/user-attachments/assets/26b56771-533f-41f4-a50b-6d96ab8d3064" />
