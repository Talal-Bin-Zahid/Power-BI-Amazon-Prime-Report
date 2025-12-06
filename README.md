# Power-BI-Amazon-Prime-Report
<img width="884" height="497" alt="Amazon Prime Report" src="https://github.com/user-attachments/assets/b95dd185-7bfd-4263-ad69-1222ec2cbca0" />

## 1. Project Overview & Business Context

**Report Name:** Amazon Prime Content Analysis Report

**Purpose/Goal:** To provide a comprehensive, single-view analysis of the Amazon Prime Video catalog, detailing content distribution across ratings, countries, genres, and content type over time.

**Target Audience:** Content Acquisition Managers, Studio Executives, and Market Analysts.

---

## 2. Data Source and Connection Details

**Primary Data Source:** Amazon Prime Video Catalog Dataset (Cloud Data Warehouse Extract)

**Authentication Method:** Service Account/Cloud Credential

**Data Gateway:** No — data is sourced from a cloud-based environment and does not require an on-premise gateway.

---

## 3. Report Structure and Key Metrics

**Number of Pages/Tabs:** 1 (The Overview Dashboard) 

**Key Pages/Areas:** Catalog Overview and Distribution Analysis

### **Core Metrics (KPIs)**

* **Total Titles:** 9,655
* **Movie Count:** 7.81K (80.82% of total)
* **TV Show Count:** 1.85K (19.18% of total)
* **Earliest Start Date:** 1920
* **Latest End Date:** 2021

### **Visualizations of Note**

* **Geographical Map:** Total Shows by Country
* **Time Series Chart:** Total Shows by Release Year
* **Distribution Charts:** Ratings, Genres, and Top Contributing Countries (Bar & Pie charts)

---

## 4. Data Refresh and Maintenance

**Refresh Frequency:** Weekly (Every Sunday at 3:00 AM UTC)

**Dataset Name in Service:** Amazon_Prime_Content_Catalog_2021

**Workspace Location:** Media & Content Analytics

**Owner/Maintainer:** Content Insights Team

---

## 5. Technical Specifications

**Power BI Desktop Version:** Latest Stable Release (as of Q4 2023)

**DAX Complexity:** Low to Moderate — primarily simple aggregations and percentage calculations

**Row-Level Security (RLS):** No

---
