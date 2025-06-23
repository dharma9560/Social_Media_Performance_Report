# Social Media Performance Analysis – Onyx Data DNA Challenge (June 2025)

This project is my submission for the **Onyx Data dataDNA Challenge – June 2025**, focused on analyzing a comprehensive social media performance dataset from 2024. The objective was to extract actionable insights that can inform better **content strategies**, **posting schedules**, and **platform-specific decisions**.

The dataset included over **5,500 posts** across **TikTok, Instagram, Facebook, LinkedIn, YouTube**, and **X.com**, with metrics such as:
- Content type (video, carousel, text, PDF, live stream, etc.)
- Content category (educational, promotional, entertainment, etc.)
- Performance metrics: likes, shares, impressions, comments, views, clicks
- Engagement rate and click-through rate
- Regional breakdown across 8 countries

---

## Project Steps

### 1. Data Cleaning
- Standardized column names, date formats, and country names
- Handled nulls and missing fields in impressions, engagement, and click data
- Filtered out test posts and removed duplicates

### 2. Data Modeling
- Built a star schema for efficient reporting in Power BI
- Created relationships between posts, platforms, regions, content types, and performance metrics

### 3. Report Creation (Power BI)
- Designed an interactive dashboard with 3 key views:
  - **Summary**: Overall impressions, views, and monthly performance trends
  - **Platform Performance**: Post-level metrics by platform, post type, and content category
  - **Regional Performance**: Country-wise engagement and CTR analysis with content breakdown
- Included slicers for month, platform, region, and content category

### 4. Analysis & Key Insights

#### Platform Performance
- **Instagram, Facebook, and TikTok** showed the highest average engagement per post.  
- **Facebook and TikTok** also had strong **click-through rates** (~2% and 1.7%).  

#### Content-Type Impact
- **Videos** generated over **73% of total engagement**, especially when unsponsored.
- **Organic content** dominated impressions (~80%) compared to sponsored posts (~20%).
- **Product promotion** and **educational content** performed best across both impressions and engagement.

#### Regional Trends
- **USA, Japan, and Brazil** led in total video views and engagement.
- CTR varied by region: **Japan had the highest CTR (0.70%)**, while **India and Brazil** showed the lowest (~0.59%).
- Engagement rate was consistent across countries (~13.3–13.7%).

#### Posting Strategy
- Best time to post: **mid-week around noon**, or **weekend afternoons**
- Strategic hashtags like **#CustomerStory, #FeatureHighlight**, and **#ProductDemo** helped boost impressions.


## ?? Power BI Dashboard (Screenshots)

| Summary View | Platform View | Regional View |
|--------------|---------------|----------------|
| ![Summary](./Report_Summary.png) | ![Platform](./Report_Platform.png) | ![Region](./Report_Region.png) |


