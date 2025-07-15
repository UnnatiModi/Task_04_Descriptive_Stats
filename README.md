# Task_04_Descriptive_Stats
# 📊 Research Task 04 – Descriptive Statistics with Polars

This repository contains data analysis for **U.S. 2024 Presidential Election social media datasets**, using the **Polars** Python library for high-performance data manipulation.

## 📁 Datasets Analyzed

1. **Facebook Ads** (`2024_fb_ads_president_scored_anon.csv`)
2. **Facebook Posts** (`2024_fb_posts_president_scored_anon.csv`)
3. **Twitter Posts** (`2024_tw_posts_president_scored_anon.csv`)

All datasets are sourced from Illuminating 2024, anonymized for research purposes.

---

## 📌 Objectives

- Perform descriptive statistics on large datasets using **Polars**.
- Identify numeric and categorical columns automatically.
- Summarize data both overall and **grouped by meaningful columns**:
  - Facebook Ads: `page_id`, `ad_id`
  - Facebook Posts: `Page Admin Top Country`
  - Twitter Posts: `source`
- Generate visualizations to highlight key insights.

---

## 🛠 Tools Used

- Python 3.x
- [Polars](https://pola.rs/) for fast, memory-efficient data handling
- Matplotlib & Seaborn for visualizations
- Jupyter Notebook for exploratory analysis

---

## 📈 Visualizations Included

### ✅ Top 10 Topics in Facebook Ads

Bar chart showing most frequently mentioned political topics across all ads, based on average topic presence.

---

### ✅ Likes Distribution by Country (Facebook Posts)

Box plot comparing user engagement (likes) across the top 5 countries that manage Facebook pages.

---

## 💡 Key Insights

- **Advocacy and issue-based messages dominate** across all platforms.
- Twitter posts show **higher virality** (views, likes) than Facebook.
- Facebook Ads are **budget-variable** and often unique per ad ID.
- **Core political topics** (economy, governance, health) are central themes.
- Most content originates from the **U.S.**, but there’s meaningful activity from other countries.

---


