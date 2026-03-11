# Amazon Prime Video Content Analysis (Power BI)

## 📌 Project Overview

This project analyzes the Amazon Prime Video content catalog to uncover trends in content quality, release behavior, runtime, audience engagement, and global production distribution. The goal was to transform raw streaming metadata into a clean, executive-ready dashboard that supports data-driven content strategy decisions.

The final deliverable is an interactive **Power BI dashboard** designed for both technical and non-technical stakeholders.

---

## 🎯 Business Objectives

* Understand the overall quality of Prime Video content using IMDb and TMDB metrics
* Identify trends in content releases and runtime over time
* Analyze the balance between Movies and TV Shows
* Evaluate audience age certifications distribution
* Visualize global content production footprint

---

## 📂 Dataset Description

* **Source:** Amazon Prime Video metadata (IMDb & TMDB enriched)
* **Rows:** ~8,300 titles
* **Key Fields:**

  * Title, Type (Movie / Show)
  * Release Year
  * Runtime
  * IMDb Score & Votes
  * TMDB Score & Popularity
  * Seasons
  * Age Certification
  * Production Countries

---

## 🧹 Data Cleaning & Transformation (Power Query)

The raw dataset required extensive preprocessing to ensure analytical accuracy:

* Removed duplicate titles and invalid records
* Handled missing values in scores and runtime fields
* Standardized content types (Movie / Show)
* Converted numeric fields to proper data types
* Filtered erroneous release years and outliers
* Created helper columns for aggregation (counts, averages)

These steps ensured reliable KPIs and consistent visual behavior.

---

## 📊 Dashboard KPIs

* **Average IMDb Score:** 5.94
* **Average TMDB Score:** 5.96
* **Total Titles:** 8,308
* **Movies:** 88.33%
* **TV Shows:** 11.67%

---

## 🔍 Key Insights

### 1. Content Composition

* Movies dominate the Prime Video catalog, accounting for nearly **90%** of all titles.
* TV Shows represent a smaller but potentially high-engagement segment.

### 2. Release Trends

* Peak content releases occurred between **2017 and 2019**.
* A noticeable decline in new titles appears after 2020.

### 3. Runtime Analysis

* Average runtime has **decreased over time**, suggesting a shift toward shorter content formats.

### 4. Audience Engagement

* IMDb scores and TMDB popularity show a **downward trend for newer releases**, indicating increasing competition or changing viewer preferences.

### 5. Age Certification Distribution

* **R-rated** and **TV-MA** content dominates the platform, highlighting a strong focus on mature audiences.

### 6. Global Production

* Content production is heavily concentrated in **North America and Europe**, with emerging contributions from Asia and South America.

---

## 🎨 Design & Visualization Choices

* Dark theme for modern, streaming-platform alignment
* KPI cards for instant executive insight
* Line charts for trend analysis
* Bar charts for ranking and comparison
* Map visualization for geographic storytelling
* Interactive filters for content type exploration

The layout follows a top-down storytelling flow: **Overview → Trends → Distribution → Geography**.

---

## 🏁 Conclusion

This project demonstrates the ability to:

* Clean and transform real-world messy data
* Design insightful KPIs aligned with business questions
* Build visually compelling, stakeholder-ready dashboards
* Communicate insights clearly through data storytelling

The dashboard is suitable for **portfolio presentation, interviews, and business reporting**.

---

## 🔮 Future Enhancements

* Genre-level engagement analysis
* Time-to-popularity forecasting
* Viewer sentiment correlation
* Advanced DAX measures for dynamic benchmarks
* Drill-through pages for title-level analysis

---

## 🛠 Tools Used

* Power BI
* Power Query (M Language)
* DAX
* IMDb & TMDB Metadata

---

📌 *This project highlights practical Business Intelligence skills applied to real-world entertainment data.*


