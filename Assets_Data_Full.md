# 📘 Strik3Zone Models & Metrics – Formula Index

This document catalogs all custom models, ratings, groupings, tools, and datasets used across the Strik3Zone platform. These are the core systems that power our rankings, projections, scouting tools, and analytics engines.

---

## 🧠 Models

| **Model**                     | **Description**                                                                 |
|------------------------------|---------------------------------------------------------------------------------|
| `STORM`                      | Relief pitcher performance and trust model (Stat Tracking On Relief Metrics)     |
| `ProspeX`                    | Prospect ranking and performance projection using industry comps + stat growth  |
| `UltiTeam`                   | Team scoring system that blends wins, off-season, ownership, fan trust, and expectations |
| `Super Sleeper Stars`        | Predictive model to identify breakout players based on underweighted metrics     |
| `Fantasy-Baseball_Weighted`  | Normalizes player value vs league-wide positional and categorical importance     |

---

## 🏷️ Ratings

| **Rating**        | **Description**                                                         |
|-------------------|-------------------------------------------------------------------------|
| `MngrCon`         | Manager Confidence Rating (based on usage, quotes, and consistency)     |

---

## 🧩 Groupings & Tiers

| **System**                          | **Description**                                                        |
|------------------------------------|------------------------------------------------------------------------|
| `Fantasy-Baseball_Tier_Ranking`    | Category-based tier rankings across positions based on statistical clusters and Roto value |

---

## 💰 Tools

| **Tool**                              | **Description**                                                          |
|--------------------------------------|--------------------------------------------------------------------------|
| `Auction Value Player Calculator`     | Estimates player auction $ values across formats using available category scoring |
| `Fantasy-Baseball_Value_Spreadsheet` | Weighted sheet version for manual use or draft planning                 |

---

## 📊 Reference Statistics & Datasets

| **Reference**                       | **Description**                                                        |
|-------------------------------------|------------------------------------------------------------------------|
| `MLB_League_Metrics_Value`          | League-wide averages, percentiles, and positional replacement values    |
| `MLB_Player_Master`                 | Master database of active and historical MLB players                   |
| `MLB_Prospects_Current`             | Prospect records by season (active pipeline)                           |
| `MLB_Prospects_Retired`             | Prospect performance archive                                           |
| `Teams_Master`                      | Team identity and performance metrics                                  |

---

## 📅 Tables (Used by Models)

| **Table**                                      | **Purpose / Model**                |
|------------------------------------------------|------------------------------------|
| `MLB_Prospect_Rankings_2025`                  | Current season prospect rankings (ProspeX) |
| `MLB_Team_Standings_Rankings_2025`            | Team performance vs UltiTeam expectations |
| `FantasyBaseball_Auction-Price_2025`          | Used by Auction Value and Tier models |
| `MLB_Player_Draft-Signing_2025`               | For ProspeX future value tracking   |
| `MLB_Player_Career_Values`                    | All-time model results, career summaries |

---

## 🔮 Predictive Projections

| **Model**                 | **Type**            | **Description**                     |
|--------------------------|---------------------|-------------------------------------|
| `MLB Season Projections` | Predictive Model     | Player-level forecasts across all positions |
| `NFL Season Projections` | Predictive Model     | Cross-sport model architecture test |

---

## 🧪 Connected Stats

| **Source**                           | **Model Used** | Notes                           |
|-------------------------------------|----------------|----------------------------------|
| `MLB_Player_Stats_2025_All-Categories` | STORM, $Value   | Full dataset from Fangraphs      |
| `MLB_Player_Stats_BaseballRef_RP`     | STORM           | Relief-only stats from B-Ref     |

---

## ✅ Use Cases Across Platform

| **Repo**          | **Purpose**                                 |
|------------------|---------------------------------------------|
| `models-metrics` | Stores and calculates all scores and formulas |
| `WebApp-001`     | Displays results and interacts with PostgreSQL |
| `Google Sheets`  | Drafting & visualization layer for users     |
| `Substack`       | Publishes weekly projections and insights    |

---

> Last updated: **2025-08-07**  
> Maintainer: [Strik3Zone](https://github.com/Strik3Zone)
