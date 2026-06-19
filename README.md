# Business-Intelligence-Project_Marketflash
 
## Overview
 
Marketflash is a database and analytics project built for Markus, owner of a small marketing firm, to support sustainable growth by transitioning from spreadsheet-based to database-driven operations.
 
## Objective
 
Move from manual spreadsheets to a structured relational database, validate stakeholder requirements, and deliver an interactive dashboard with actionable insights.
 
---
 
## Project Stages
 
### 1. Database Design
- Built an initial **Crow's Foot diagram** with 1:N relationships based on stakeholder requirements (optionality + cardinality)
- Entities: **Campaigns** (Fact table) + supporting Dimension tables

### 2. Entity-Relationship Design
- Finalized **ERD in Star Schema**
- Assigned datatypes, constraints, Primary Keys, and Foreign Keys

### 3. Database Creation
- Built a sample database in **Beekeeper Studio**
- Populated with sample data and validated with SQL queries

### 4. Existing Data Cleanup
- Reformatted numbers and location fields in the source spreadsheet
- Corrected date formats in Tableau

### 5. Dashboard Mock-Up
- Designed an initial layout with planned metrics based on available columns

### 6. Tableau Dashboard
- Built worksheets and assembled the final dashboard

### 7. Analysis & Insights
- Extracted top 3 insights from the dashboard
---
 
## Deliverables
 
| Artifact |
|---|
| SQL Book |
| Crow's Foot / ERD |
| Excel (cleaned data) |
| Dashboard Mock-Up |
| Tableau Dashboard (live) |
 
---
 
## Key Insights
 
> Use **Audience Segment** as the primary filter on the dashboard to isolate campaign performance per segment.
 
1. **High-Value Niche Dominance** — The "Male, 60+" segment generates the highest profit at **$1.95M** despite being a narrow demographic, indicating strong product-market fit and efficient targeting for older male audiences.
2. **Cost Inefficiency in Seniors** — Overall conversion rate is strong at **20%**, but the Senior segment has the highest cost per conversion at **$61.3** vs. $46.4 for other segments — suggesting acquisition friction or suboptimal conversion pathways that warrant investigation.
3. **Geographic Concentration Risk** — India leads with **53.2K conversions** and the UK shows **7.82M engagements**, revealing significant regional performance gaps. Underperforming regions may represent untapped potential; over-reliance on top regions is a dependency risk.
---
 
## Tools/ Platforms Used
 
- **Beekeeper Studio** — SQL database creation and validation
- **Draw.io / Lucid Chart** — Dashboard mockup and database schema
- **Google Sheets / Excel** — Data cleaning and preparation
- **Tableau Public** — Interactive dashboard and visualisation
