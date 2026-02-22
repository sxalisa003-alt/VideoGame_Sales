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

#### Top 10 Genres from 2009-2020 

Action is the leading genre, accounting for the largest share of sales over the observed period.
However the sales trend exhibited by Action reveals a clear lifecyle pattern. 
Sales show early volatility between 2009 and 2011, followed by a recovery and peak phase between 2011 and 2013, where sales increase steadily. From 2014 onwards  sales enter  a sustained decline. This trend is likely influenced by console lifecycle dynamics, where declining late-stage console adoption and anticipation of new platform releases reduce consumer spending on existing-generation titles. As new consoles are introduced, both developers and consumers shift focus, contributing to the observed decline in sales.
A synchronized decline pattern is observed across multiple genres, suggesting that this is an industry-wide trend rather than a genre-specific shift.

### Top 5 Best Selling Platforms (Global)

The PlayStation ecosystem demonstrates a strong and sustained presence in the market, with PS3 emerging as the overall dominant platform across the observed period.
However, platform leadership varies significantly year-to-year, indicating a highly competitive and dynamic market:
* Wii leads in 2009 with 210.26 million sales
* Xbox 360 dominates in 2010 with 170.92 million
* PS4 leads in later years (2014–2016), reflecting the next generation of consoles

Despite this variation, PlayStation platforms maintain consistent top-tier performance, suggesting strong brand positioning and user retention.
A key shift occurs around 2013, marking a transition period between console generations. 
During this time:
*Sales for older platforms (Wii, Xbox 360, DS) decline sharply
*New-generation platforms, particularly PS4, begin to emerge

Interestingly, PS3 continues to perform strongly even after the release of PS4, indicating a slower transition between console generations. This could be attributed to:
* A large existing user base
* Delayed adoption of newer consoles
* Continued game releases and pricing strategies for older platforms


### Publisher Market share
##### DISCLAIMER 
To maintain clarity and avoid fragmentation, the analysis focuses on the top 10 publishers, as the full dataset contains a large number of low-contributing publishers that would obscure meaningful patterns.

Nintendo holds the largest market share at approximately 24%, making it the dominant publisher over the observed period. This indicates a highly concentrated market, where a small number of major publishers account for a significant portion of total sales. Nintendo’s dominance is particularly notable given its strong performance across multiple regions and platforms.

The remaining market share is distributed among other leading publishers, suggesting competitive participation but with no single publisher matching Nintendo’s overall influence.

### Top 10 Publisher Average saler per game
Nintendo leads in average sales per game at approximately 0.64 million units per title, reinforcing its strong performance not just in total volume, but also in per-game efficiency.

A key insight emerges when comparing Publisher Market Share with Average Sales per Game:
While Nintendo maintains its leading position in both metrics, other publishers show significant variation. Notably, a higher number of game releases does not necessarily translate to higher average sales per game.
For example, Electronic Arts ranks 2nd in total market share (17.74%), driven by a high volume of releases (5404 titles), but drops to 4th in average sales per game (0.21 million). This suggests that its market share is largely driven by quantity rather than per-title performance.

This contrast highlights two distinct publisher strategies:
* High-volume strategy: many releases, lower average performance
* High-efficiency strategy: fewer releases, higher impact per game

### Regional Share Overtime
North America consistently holds the largest share of global video game sales at approximately 49.28%, making it the most significant market in the dataset.
While no extreme fluctuations are observed over time, the distribution highlights a stable regional hierarchy, where North America leads, followed by Europe and Japan, with other regions contributing a smaller but distinct share.
This suggests that global sales performance is heavily influenced by North American demand, making it a critical region for commercial success. 

### Regional Genre Preference in %
Clear regional differences emerge in genre preferences:
* Japan shows a strong preference for Role-Playing games, distinguishing it from other region
* North America favors Action and Sports, while still maintaining a relatively balanced distribution across other genres
* Europe and Other regions also show higher preferences for Action and Sports, aligning closely with global trends

These patterns indicate that while some genres (such as Action) have universal appeal, others (like Role-Playing) are region-specific in popularity, particularly in Japan. The differences may be influenced by cultural preferences, regional gaming history, and market-specific demand, although further data would be required to confirm the underlying causes.

### Top 10 Gaming Platforms
The PS2 emerges as the best-performing platform, recording the highest total global sales among all platforms in the dataset. The PS2’s strong performance can be attributed to its long lifecycle, extensive game library, and widespread global adoption, allowing it to sustain high sales over multiple years.
### Platform Market Share
The dominance of the PS2 is further reinforced by its leading market share (~14%), indicating its significant impact on overall industry sales. Its dominance also reflects an earlier era of gaming where fewer competing platforms existed, enabling it to capture a larger share of the market compared to newer, more fragmented console generations.

### Regional Platform Preference
Regional differences in platform performance highlight distinct market dynamics across the gaming industry.

* North America (NA) shows strong performance across multiple platforms, including PS2, Xbox 360, PS3, Wii, DS, and Xbox, indicating a diverse and highly competitive market with broad platform adoption.
* Europe (EU) follows a similar pattern to North America, with high-performing platforms such as PS2, Xbox 360, PS3, DS, PlayStation, and PC, suggesting aligned consumer preferences and market structure. Europe favourinmg both PS3 and X360 hints to high-performance console competition.
* Japan (JP) displays a more concentrated platform preference, with strong performance from DS, PlayStation, PS2, and SNES, indicating a tendency toward specific platforms rather than broad adoption. Japen favouring DS and SNES hints to strong handheld and legacy ecosystem loyalty.
* Other regions show limited platform dominance, with PS2 and PS3 leading, suggesting a less diversified market.
These differences suggest that global platform strategies cannot be standardized, as regional markets vary in both platform adoption and consumer preferences.

North America and Europe exhibit high platform diversity, while Japan shows platform specialization, and Other regions reflect limited market penetration and platform spread.

### Platform Lifecycle


## Conclusion, Recomendations and Constraints

### Contraints





