# Streaming Smarter: Netflix Content Strategy & Retention Signals (SQL)
> This project simulates a real-world scenario: what a content analyst might uncover when exploring Netflix's catalog using only SQL.

## TL;DR
**Problem:** Netflix needs to understand what types of content signal global growth and retention potential.

**Process:** Queried and cleaned **8,800+ titles** using SQL to analyze trends in genres, production countries, season longevity, and data quality.

**Result:** 
- Identified **Action & Drama** as globally scalable content
- Flagged data quality gaps (e.g., missing dates, inconsistent country labels)
- Highlighted **India and South Korea** as rising content producers

**Takeaway:** SQL-driven content analytics can guide smarter platform investments without advanced BI tools.

## SQL Queries Preview 
Snapshot of SQL queries used for data cleaning and segmentation, including genre counts, production-country trends, and title longevity. 

![Dirty data queries](dirty_data_queries.png)

## Table of Contents
 * [Overview](#overview)
 * [Tools Used](#tools-used)
 * [Key Business Questions & Insights](#key-business-questions--insights)
 * [Case Study - Full Walkthrough](#case-study-full-walkthrough)
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
- **2018:** 1,144 titles -> expansion linked to global growth strategy

**🌍 Top Content-Producing Countries**
 - USA: **2,806 titles**
 - India: **972 titles**
 - **Insight**: Regional storytelling (especially APAC) is becoming key

**🎬 Content Type Split**
 - Movies: **6,119 titles**
 - TV Shows: **2,674 titles**
 - **Insight**: Movies still dominate, but TV is rising as binge behavior grows

**🎭 Top Genres**

| Genre Combo                                       | Count                              |
|---------------------------------------------------|------------------------------------|
| Dramas, International Movies                      | 361                                |
| Documentaries                                     | 358                                |
| Stand-Up Comedy                                   | 334                                |


**Insight:** Drama & international focus show Netflix's global-first strategy

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
> *Overall Takeaway:* These insights act as early indicators of what content categories are likely to support, engagement, and long-term platform retention.

## Case Study - Full Walkthrough
Covers the SQL logic, insights, and recommendations behind each query block, and connects the outputs to real-world content strategy decisions Netflix might explore.

[View the full case study](https://docs.google.com/document/d/1v0nIUuxNxiTiPsNWtdvXeOKIJabTFmtJuQ1BOnej7pw/edit?usp=sharing)

## What I'd Explore Next
In a future version of this project, I would:
- Overlay viewer ratings to check if genre trends align with audience demand
- Explore time-based churn risk for older shows
- Begin testing a Python model to predict binge-worthy content combinations

## What This Project Demonstrates
- Ability to derive business insights using SQL without BI tools
- Exposure to real-world data cleaning and exploratory analysis
- Understanding of how content trends link to strategic decisions
- Interest in streaming/media analytics and early-career SQL application
- Ability to use content attributes as proxies for retention and engagement when direct user data is unavailable.

## Let's Connect
I'm building my career in data analytics with a focus on turning business questions into insights. Feel free to reach out via:
 * [GitHub](https://github.com/Shrey0561)
 * [LinkedIn](https://www.linkedin.com/in/shreya-srinath-879a66205/)
 * [Notion](https://www.notion.so/Data-Analyst-Portfolio-221ebe151fdd801e9445e32590b67758?source=copy_link)


I'm always up for conversations, mentorship, or entry-level opportunities.
