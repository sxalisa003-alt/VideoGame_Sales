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

### Data Cleaning and Constraints
The dataset required preprocessing due to missing values, inconsistencies, and structural limitations.

##### Data Transformation:
 The original dataset structure was modified to support analysis. The data was unpivoted to convert wide-format sales columns into a long format, enabling easier aggregation, filtering, and visualization across regions and time.
Additionally, sales values were standardized by replacing "." with "," to ensure correct decimal formatting and numeric interpretation.

##### Handling Missing Data:
 Rows with extensive missing values (9 out of 11 fields, including Platform and Global Sales) were removed (26 records) to maintain data integrity.
Additionally, 271 records (1.6%) contained missing year values. These were excluded from time-series analysis but retained where year was not required.

##### Data Quality Considerations:
  Some inconsistencies and anomalies were present in the dataset, which may affect absolute accuracy but do not significantly impact overall trends and patterns.

##### Aggregation Decisions:
 Due to a large number of publishers, analysis was limited to the top 10 publishers by sales. This reduces noise and improves interpretability while still capturing the majority of market activity.

##### Precision Handling:
  Extremely small percentage values (e.g., in average sales per game) were rounded to improve readability in visualizations without affecting overall insights.
   
## Dashboard and Dataset

### Dataset Structure

![VideoGamesSales_DatasetDescription](https://github.com/sxalisa003-alt/VideoGame_Sales/blob/ac2c221c6f130e18ae0864059b12406813b49c80/images/VGSales%20DatasetDescrp%202026-02-22.png)


### Dashboard


![VideoGameSales Dashboard](https://github.com/sxalisa003-alt/VideoGame_Sales/blob/cd06bbcc06782940c15507bbeb57ff891b90354c/images/Dashboard_VideoGameSales.png)

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
![Top10Genre](https://github.com/sxalisa003-alt/VideoGame_Sales/blob/c7f65e43f77b96ab3a5d3fb08542b1f66d066dd4/images/top10genre.png)

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

![PublisherMarketShare%](https://github.com/sxalisa003-alt/VideoGame_Sales/blob/0d4fd8922d30500b2a391abefeb51ce53957e2bb/images/PubMarShare.png)

##### DISCLAIMER: To maintain clarity and avoid fragmentation, the analysis focuses on the top 10 publishers, as the full dataset contains a large number of low-contributing publishers that would obscure meaningful patterns.

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

![RegionalShareOvertime](https://github.com/sxalisa003-alt/VideoGame_Sales/blob/5ef1d9bb2cc9c6a8e49b0fd67c68b0916143e7f6/images/RegonalMarketShareOverrttime.png)

North America consistently holds the largest share of global video game sales at approximately 49.28%, making it the most significant market in the dataset.
While no extreme fluctuations are observed over time, the distribution highlights a stable regional hierarchy, where North America leads, followed by Europe and Japan, with other regions contributing a smaller but distinct share.
This suggests that global sales performance is heavily influenced by North American demand, making it a critical region for commercial success. 

### Regional Genre Preference in %

![RegionalGenrePreference%](https://github.com/sxalisa003-alt/VideoGame_Sales/blob/bde3793788a5cd1f541d4fc0f11132830593ce8e/images/RegionalGenPref.png)

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

![RegionalPlatformPreference](https://github.com/sxalisa003-alt/VideoGame_Sales/blob/1769a1e546548d80ccfc64c98345446364a6f1ba/images/RegionalPlatformPreference.png)

Regional differences in platform performance highlight distinct market dynamics across the gaming industry.

* North America (NA) shows strong performance across multiple platforms, including PS2, Xbox 360, PS3, Wii, DS, and Xbox, indicating a diverse and highly competitive market with broad platform adoption.
* Europe (EU) follows a similar pattern to North America, with high-performing platforms such as PS2, Xbox 360, PS3, DS, PlayStation, and PC, suggesting aligned consumer preferences and market structure. Europe favourinmg both PS3 and X360 hints to high-performance console competition.
* Japan (JP) displays a more concentrated platform preference, with strong performance from DS, PlayStation, PS2, and SNES, indicating a tendency toward specific platforms rather than broad adoption. Japen favouring DS and SNES hints to strong handheld and legacy ecosystem loyalty.
* Other regions show limited platform dominance, with PS2 and PS3 leading, suggesting a less diversified market.
These differences suggest that global platform strategies cannot be standardized, as regional markets vary in both platform adoption and consumer preferences.

North America and Europe exhibit high platform diversity, while Japan shows platform specialization, and Other regions reflect limited market penetration and platform spread.

### Platform Lifecycle Analysis by Decade

![PlatformLifecyclewe1980-2020](https://github.com/sxalisa003-alt/VideoGame_Sales/blob/869d222c7b861aab838593b96237d76273e6ff7b/images/PlatformLifecycle.png)

##### 1980–1989: Market Emergence & Early Dominance
The early 1980s show a highly concentrated market, with the Atari 2600 dominating from 1980–1982 as the only consistently recorded platform in the dataset.
A major shift occurs in 1983 with the entry of the NES, which rapidly scales from 10.96M to 50.08M in its second year. From 1983–1988, NES maintains clear dominance, signaling a transition toward more advanced console technology and stronger market adoption.

In 1988–1989, the Game Boy (GB) enters and quickly disrupts the market, surging from 1.43M to 64.97M. This coincides with a decline in NES sales, suggesting a consumer shift toward handheld gaming rather than a failure of the NES itself.

The sharp drop in GB sales in 1990 is observed, but no causal claim can be confirmed from the dataset. This fluctuation likely reflects early-stage volatility common in emerging platforms.

##### 1990–1999: Competitive Expansion & Console Wars
The 1990s introduce direct platform competition and overlapping lifecycles.
SNES dominates from 1990–1994, benefiting from being a next-generation successor to NES. However, the entry of PlayStation (PS) in 1994 marks a major disruption. Within two years, PS scales aggressively, reaching 94.7M by 1996 and peaking at 136.17M in 1997—the highest annual platform sales observed.
Nintendo responds with the N64 in 1996, which shows steady but comparatively lower growth. Meanwhile, GB demonstrates intermittent recovery, indicating sustained relevance in the handheld segment.

From 1994 onward, PS establishes dominance, signaling a shift toward Sony’s entry reshaping the competitive landscape.

##### 2000–2009: Transition Cycles & Multi-Platform Competition
This decade is defined by rapid platform turnover and overlapping generations.

The launch of PS2 in 2000 creates a transition effect, where earlier PS sales decline as users migrate to the new system. PS2 goes on to dominate from 2001–2005, becoming the central platform of the era.
Simultaneously:
* GBA (2000–2005) shows fluctuating performance before declining
* GameCube (2001–2007) has a shorter lifecycle with moderate adoption
* DS (2004 onward) shows strong, sustained growth, eventually overtaking PS2
  
By the late 2000s:
* PS3 (2006) and X360 enter into direct competition
* The market becomes highly fragmented, with no single platform maintaining long-term dominance

PC shows gradual, stable growth across the decade, indicating a less volatile but consistent segment.

##### 2010–2020: Maturity, Saturation & Decline
The final decade reflects a maturing market with overall declining sales across most platforms.

Key transitions include:
* The shift from PS3 to PS4 around 2013
* The introduction of 3DS (2011), which starts strong (62.28M) but declines steadily
* PSV (2011) showing limited market impact compared to competitors

X360, DS, and PlayStation platforms remain in close competition during the early 2010s, but all exhibit declining trends over time.
Newer platforms such as XOne and later Xbox variants enter the market but fail to sustain long-term growth within the dataset.

Overall, this period suggests market saturation and reduced growth momentum, with shorter platform lifecycles and diminishing peak sales.

## Conclusion and Recomendations

##### Platforms

##### Conclusion
* Sony’s PlayStation ecosystem (not just PS3 alone) emerges as the most dominant platform family over time. Its strength lies in consistent generational transitions, where each new console builds on the previous one without losing user momentum. This continuity supports sustained sales across multiple regions, indicating strong global distribution and effective market penetration.
* Microsoft’s Xbox platforms are strong competitors, particularly in certain peak years, but show less consistency in maintaining dominance across console generations.
* Nintendo platforms (e.g., DS) demonstrate periods of high performance, particularly in earlier years, but tend to follow shorter lifecycle peaks compared to PlayStation.

A sharp decline in platform sales is observed from 2017–2020; however, this is attributed to missing or incomplete data, not actual market collapse.

##### Recommendation
Platform developers should adopt elements of the PlayStation strategy:
* Focus on seamless generational transitions to retain users across console upgrades
* Prioritize backward compatibility or ecosystem continuity to reduce switching friction
* Leverage exclusive titles and strong launch lineups to drive early adoption

The underlying principle here is simple but powerful: reduce friction, and users will stay. Increase friction, and they wander.

##### Platforms

##### Conclusion
Nintendo leads both in market share and average sales per game, indicating not just scale but also efficiency in converting releases into successful titles.
Interestingly, a higher number of published games does not necessarily translate into higher average sales, suggesting that quality, brand strength, and audience alignment matter more than sheer volume.

##### Recommendation
Publishers should:
* Diversify across platforms to maximize reach and reduce dependency on a single ecosystem
* Balance quantity with quality, focusing on high-performing titles rather than excessive output
* Expand into globally relevant genres while still tailoring content to regional preferences






