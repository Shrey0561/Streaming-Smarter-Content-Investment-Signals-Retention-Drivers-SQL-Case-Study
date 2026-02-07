# Streaming Smarter: Content Investment Signals & Retention Drivers (SQL Case Study)
> This project simulates a real-world scenario: what a content analyst might uncover when exploring Netflix's catalog using only SQL.

## TL;DR
**Problem:** Netflix must prioritize content investments that support global growth and long-term viewer retention, but content signals are scattered across metadata.

**Process:** Used **SQL** to clean and segment **8,800+** titles by genre mix, production geography, longevity, and catalog consistency to uncover scalable patterns.

**Result:** Identified internationally scalable genres (Action, Drama), emerging production hubs (India, South Korea), and long-running TV formats as retention anchors, while uncovering data gaps that could distort strategic decisions.

## SQL Queries Preview 
Snapshot of SQL queries used for data cleaning and segmentation, including genre counts, production-country trends, and title longevity. 

![Dirty data queries](dirty_data_queries.png)

## Table of Contents
 * [Overview](#overview)
 * [Tools Used](#tools-used)
 * [Key Business Questions & Insights](#key-business-questions--insights)
 * [Strategic Implications](#strategic-implications)
 * [What I'd Explore Next](#what-id-explore-next)
 * [What This Project Demonstrates](#what-this-project-demonstrates)
 * [Let's Connect](#lets-connect)

## Overview
This project investigates Netflix's content strategy and global expansion patterns using only SQL. By querying 8,800+ titles, it explores genre popularity, top production countries, director frequency, and data quality issues, all through a business-question lens.

## Tools Used
**SQL:** Data cleaning, transformation, and exploratory analysis

**Microsoft Excel (minor):** Used only to fix UTF-8 encoding errors during CSV import

## Key Business Questions & Insights

**📈 Peak Content Growth Year** 
- **2018:** spike suggests aggressive global catalog expansion aligned with subscriber growth strategy.

**🌍 Top Content-Producing Countries**
 - USA: **2,806 titles**
 - India: **972 titles**
 - **Insight**: Regional storytelling (especially APAC) is becoming key

**🎬 Content Type Split**
 - Movies: **6,119 titles**
 - TV Shows: **2,674 titles**
 - **Insight**: While movies dominate volume, long-running TV shows present stronger binge-retention signals.

**🎭 Top Genres**

| Genre Combo                                       | Count                              |
|---------------------------------------------------|------------------------------------|
| Dramas, International Movies                      | 361                                |
| Documentaries                                     | 358                                |
| Stand-Up Comedy                                   | 334                                |


**Insight:** International drama formats appear to serve as scalable cross-border retention drivers.

**🎥 Most Frequent Directors**

| Director                                       | Titles                     |
|------------------------------------------------|----------------------------|
| Rajiv Chilaka                                  | 19                         |
| Raul Campos, Jan Suter                         | 18                         |
| Suhas Kadav                                    | 16                         |
| Martin Scorsese                                | 12                         |

**Insight:** Mix of international animation + iconic film directors

**⏱ Average Movie Run-Time**
- Avg length: **99.6 mins**
- **Outliers** flagged -> signals need for data review

**📺 Longest-Running TV Shows**

 | Title             | Seasons           |
 |-------------------|-------------------|
 | Grey's Anatomy    | 17                |
 | Supernatural      | 15                |

**Insight:** Long-running US dramas drive binge retention

**🧼 Data Quality Check**

| Field            | Missing Values        |
|------------------|-----------------------|
| Director         | 2633                  |
| Cast             | 825                   |

**Observation:** Cleaning is essential even on high-profile public datasets.

> **Overall Takeaway:** These insights act as early indicators of what content categories are likely to support engagement and long-term platform retention.

## Strategic Implications
* Invest in international drama and action formats for scalable growth.
* Expand long-running serialized content to strengthen binge retention.
* Standardize metadata governance to improve investment forecasting accuracy.
* Prioritize emerging production markets (e.g., India, South Korea) for cost-efficient global expansion.

## What I'd Explore Next
In a future version of this project, I would:
- Overlay viewer ratings to check if genre trends align with audience demand
- Explore time-based churn risk for older shows
- Begin testing a Python model to predict binge-worthy content combinations

## What This Project Demonstrates
- Ability to translate content metadata into strategic investment signals
- Understanding of how catalog structure influences retention and global expansion
- Experience linking descriptive content trends to decision-support frameworks
- SQL-driven analytical thinking without reliance on BI tools
- Ability to use content attributes as proxies for retention and engagement when direct user data is unavailable.

## Let's Connect
I'm building my career in data analytics with a focus on turning business questions into insights. Feel free to reach out via:
 * [GitHub](https://github.com/Shrey0561)
 * [LinkedIn](https://www.linkedin.com/in/shreya-srinath-879a66205/)
 * [Notion](https://www.notion.so/Data-Analyst-Portfolio-221ebe151fdd801e9445e32590b67758?source=copy_link)


I'm always up for conversations, mentorship, or entry-level opportunities.
