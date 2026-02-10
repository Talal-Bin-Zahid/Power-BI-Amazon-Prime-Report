# Power-BI-Amazon-Prime-Report
<img width="884" height="497" alt="Amazon Prime Report" src="https://github.com/user-attachments/assets/b95dd185-7bfd-4263-ad69-1222ec2cbca0" />

## 1. Project Overview & Business Context

**Report Name:** Amazon Prime Content Analysis Report
**Platform:** Power BI

**Purpose / Goal**
This report provides a comprehensive, single-page analytical overview of the Amazon Prime Video content catalog. It is designed to help stakeholders understand content volume, distribution, diversity, and historical growth trends across ratings, genres, countries, and content types (Movies vs TV Shows).

**Target Audience**

* Content Acquisition Managers
* Studio & Distribution Executives
* Market & Media Analysts
* Strategy and Planning Teams

---

## 2. Data Source & Connection Details

* **Primary Data Source:** Amazon Prime Video Content Catalog Dataset (Cloud Data Warehouse Extract)
* **Dataset Name (Service):** `Amazon_Prime_Content_Catalog_2021`
* **Data Environment:** Cloud-based
* **Authentication Method:** Service Account / Cloud Credentials
* **On-Premise Gateway:** Not Required

---

## 3. Report Structure

* **Number of Pages:** 1
* **Page Name:** Overview Dashboard
* **Report Focus Areas:**

  * Catalog Summary & KPIs
  * Content Distribution by Rating
  * Content Distribution by Genre
  * Geographical Distribution of Content
  * Content Type Split (Movies vs TV Shows)
  * Historical Content Growth Trend

---

## 4. Core KPIs & High-Level Metrics

### Catalog Size & Coverage

* **Total Titles:** 9,655
* **Total Ratings:** 25
* **Total Genres:** 519
* **Content Time Span:**

  * **Earliest Release Year:** 1920
  * **Latest Release Year:** 2021

### Content Type Breakdown

* **Movies:** 7.81K (80.82%)
* **TV Shows:** 1.85K (19.18%)

---

## 5. Content Distribution Metrics

### A. Ratings Distribution (Total Shows by Rating)

The dashboard highlights how content is classified across audience ratings:

* **13+:** ~2,117 titles
* **16+:** ~1,547 titles
* **ALL:** ~1,268 titles
* **18+:** ~1,243 titles
* **R:** ~1,010 titles
* **PG-13:** ~393 titles
* **7+:** ~385 titles
* **PG:** ~353 titles
* **Unrated / Other:** ~253 titles

This distribution provides insight into audience targeting and maturity segmentation of the catalog.

---

### B. Genre Distribution (Top Genres by Total Shows)

Top contributing genres include:

* **Drama:** ~986 titles
* **Comedy:** ~536 titles
* **Drama, Suspense:** ~399 titles
* **Comedy, Drama:** ~377 titles
* **Animation, Kids:** ~356 titles
* **Documentary:** ~350 titles
* **Kids:** ~334 titles
* **Action, Drama:** ~297 titles
* **Documentary, Special Interest:** ~296 titles

This metric helps identify dominant content categories and genre diversity within the platform.

---

### C. Geographical Distribution

**Top Content-Producing Countries:**

* **United States:** ~41.34% (≈229 titles)
* **India:** ~45.6% (≈253 titles)
* **United Kingdom**
* **Canada**
* **Spain**
* **Germany**
* **Australia**
* **France**

A geographical map visualization is used to highlight regional content concentration and global reach.

---

## 6. Time-Based Metrics & Trends

### Content Growth Over Time

* **Visualization:** Area / Line Chart (Movies vs TV Shows)
* **Metric:** Total Shows by Release Year

**Key Insights:**

* Minimal content volume prior to 1950
* Gradual growth from 1950–2000
* Sharp acceleration in content production post-2000
* Significant spike in releases after 2010, especially for Movies

This trend analysis supports long-term content acquisition and production strategy decisions.

---

## 7. Visualizations Included

* KPI Cards: Total Titles, Total Ratings, Total Genres, Start Date, End Date
* Bar Charts: Ratings Distribution, Genre Distribution
* Pie / Donut Charts: Content Type Split, Top Countries Contribution
* Map Visualization: Total Shows by Country
* Time Series Chart: Total Shows by Release Year

---

## 8. Data Refresh & Maintenance

* **Refresh Frequency:** Weekly
* **Schedule:** Every Sunday at 3:00 AM (UTC)
* **Workspace:** Media & Content Analytics
* **Owner / Maintainer:** Content Insights Team

---

## 9. Technical Specifications

* **Power BI Desktop Version:** Latest Stable Release (Q4 2023)
* **Data Modeling Complexity:** Low to Moderate
* **DAX Usage:**

  * Aggregations (COUNT, DISTINCTCOUNT)
  * Percentage Calculations
  * Time-based Summaries
* **Row-Level Security (RLS):** Not Implemented

---

## 10. Intended Business Value

This report enables stakeholders to:

* Assess overall catalog size and diversity
* Identify content gaps by region, genre, or rating
* Track historical growth patterns
* Support content acquisition, licensing, and investment decisions
* Provide a single-view executive snapshot of Amazon Prime Video’s content landscape

---

**End of README**

