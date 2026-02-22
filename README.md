# Video Game Sales Analysis Dashboard - Excel BI Project

### Overview

This project explores global and regional video game sales trends using Microsoft Excel as a BI tool. The goal of this project is to transform raw sales data into a clean, structured, interactive dashboard that reveals insights on genre popularity, platform market performance, publisher influence, regional market behaviour.
The analysis focuses on trends across multiple years, highlighting how sales patterns evolve overtime and differ across regions.

### Project Objectives 

The dashboard is designed to answer the following analytical questions:
1. What were the top 5 performing Genres and Platforms between the years 2009 and 2020?
2. How did gaming platforms perform overtime and across regions?
3. What impact do publishers have on overall sales perfomance?
4. How do regional sales pattern differ by genre and platform?
5. What trends exist in platform lifecycle and market share?

### Tool & Skills Used
* Microsoft Excel
* Data Cleaning & Transformation
* Data Normalization (Unpivoting)
* Pivot Tables & Pivot Charts
* Data Visualization
* Business Analysis

### Data Preparation
1. Deleted 26 rows with blanks from the columns Platform to Global_Sales
2. Replaced '.' to ';' for all sales columns
3.  The original data set contained separate columns for regional sales(NA_Sales, EU_Sales, JP_Sales, and Other_Sales). To enable flexible analysis and dynamic filtering the dataset was unpivoted into a normalized structure thus giving us a new table were the regional columns were transformed into a Region category with a unified Sales column. This approach allowed slicers and pivot tables to function consistently across all visuals.

   
## Dashboard and Dataset

### Dataset Structure

![VideoGamesSales_DatasetDescription](https://github.com/sxalisa003-alt/VideoGame_Sales/blob/ac2c221c6f130e18ae0864059b12406813b49c80/images/VGSales%20DatasetDescrp%202026-02-22.png)


### Dashboard


![VideoGameSales Dashboard](https://github.com/sxalisa003-alt/VideoGame_Sales/blob/31171f428b698c659e3a1f493cbbf1f94544a66e/images/VGSalesDas_2026-02-22.png)
 This dashboard includes:
 1. KPI Cards
    * Total Sales
    * Top Genre
    * Top Platform
    * Top Publisher
 3. Top 5 Genres (Global performance over a decade)
 4. Platform Performance Analysis
 5. Publisher Market Share (%)
 6. Regional Sales Distribution
 7. Platform Lifecycle Trends
 8. Interactive slicers by Region, Genre, Publisher, Platform




### Key Insights


## Conclusion, Recomendations and Constraints

### Contraints





