# Video Game Sales Performance Dashboard (1980–2020)

##  Project Overview
This project transforms raw, historical gaming sales data into an interactive Excel BI dashboard to solve a high-stakes retail expansion problem. 

### The Business Problem
We are a new, fast-growing video game retail brand currently expanding into an international brick-and-mortar and e-commerce storefront. To scale successfully without wasting capital, management needs to know **which platforms and genres to heavily invest in** for primary buying and selling. Furthermore, we must **cater inventory to local customer preferences** in each global region to eliminate the risk of overstocking dead inventory.

This dashboard tracks platform lifecycles, regional genre popularity, and publisher performance to give procurement teams a data-driven blueprint for international inventory allocation.

>  **Tech Stack & Skills Used:** Microsoft Excel, Data Cleaning, Data Normalization (Power Query/Unpivoting wide-format data), Pivot Tables & Charts, Dashboard Design, and Business Analysis.

---

##  Interactive Dashboard Preview
*You can view the full static layout in the repository named `Screenshot 2026-06-19 212652.png`.*

![Interactive Dashboard Demo](https://via.placeholder.com/800x450.png?text=Tip:+Replace+this+placeholder+with+a+link+to+your+dashboard+GIF+or+Video!) 
*(Check out the synchronized slicers on the left panel of `Screenshot 2026-06-19 212652.png` to filter the data instantly by Region, Genre, and Publisher).*

---

##  Executive Q&A: Key Business Insights

### Q1: Which genres and platforms are the safest bets for international investment?
* **The Insight:** **Action** is the ultimate software revenue driver globally, while **Sony’s PlayStation ecosystem (PS2, PS3, PS4)** provides the most reliable, repeating sales cycle in the industry.
* **The Data:** Even though Action game sales dip temporarily during hardware generation shifts (due to late-stage console adoption slowing down), it consistently captures the highest baseline customer spending. Hardware-wise, PlayStation displays incredible user loyalty. A player who owns a PS3 is highly likely to upgrade to a PS4, securing a long-term customer base. While competitors like Xbox show volatility between generations, PlayStation maintains consistent top-tier performance.
* **Business Action:** Always dedicate baseline shelf space and digital features to Action titles. Treat the latest PlayStation console family as your store's anchor inventory worldwide.

---

### Q2: How should stocking strategies change across global retail regions?
* **The Insight:** A "one-size-fits-all" inventory plan will leave international warehouses with piles of unsold stock. Gaming preferences are intensely regionalized.
* **The Data:** 
  * **North America (NA):** The biggest revenue driver (49.28% of global sales). A highly diverse, competitive market where customers heavily favor **Action** and **Sports** games across both Xbox and PlayStation.
  * **Europe (EU):** Tracks closely with NA volume, but shows a much stronger preference for **PlayStation** over Xbox, alongside a steady, unique market for **PC** titles. Europe favoring both PS3 and Xbox 360 points to fierce high-performance home console competition.
  * **Japan (JP):** A total structural outlier. Dominated by **Role-Playing Games (RPGs)** and **Nintendo handheld ecosystems (DS/Game Boy)**. Standard Western home consoles drastically underperform here, proving strong handheld and legacy ecosystem loyalty.
* **Business Action:** Run a localized buying model. Heavy up on RPGs and Nintendo handheld stock for Asian storefronts, and focus on high-performance home console software (Action/Sports) for Western markets.

---

### Q3: Should we stock games from high-volume publishers or curated, high-impact ones?
* **The Insight:** Quality, brand equity, and target audience alignment easily beat raw quantity. **Nintendo** runs an ultra-efficient, high-impact strategy, whereas publishers like **Electronic Arts (EA)** rely on churning out a high volume of annual releases.
* **The Data:** 

| Publisher Strategy | High-Volume (e.g., Electronic Arts) | High-Efficiency (e.g., Nintendo) |
| :--- | :--- | :--- |
| **Market Share** | 17.74% | **24.00%** |
| **Title Volume** | 5,404 Releases (Driven by Quantity) | Fewer Releases (Driven by Quality) |
| **Avg. Sales Per Game** | 0.21 Million Units | **0.64 Million Units (3x more efficient)** |

* **Business Action:** Prioritize premium marketing, pre-orders, and bundle deals for first-party Nintendo titles—they sell incredibly fast per SKU and yield maximum efficiency. For high-volume publishers like EA, stock heavily during the initial 14-day launch window to capture the hype, then use aggressive progressive discounting post-season to keep warehouse space moving.

---

### Q4: How do console lifecycles work, and when should our stores stop stocking an old system?
* **The Insight:** Most console lifecycles last 5–7 years (2 years scaling up, 3 years peaking, and a gradual sunset). However, software sales for a *winning* legacy system (like the PS3) stay highly profitable for **2–3 years after** the next-gen console (like the PS4) launches.
* **The Data:** Historical transitions show that mature console player bases keep buying games long after hardware manufacturing slows down because of delayed next-gen adoption and continuing software support.
  * **1980s (Market Emergence):** Single-platform dominance where the Atari 2600 gave way to the NES (scaling from 10.96M to 50.08M in year two). In 1989, the Game Boy disrupted everything, surging to 64.97M and proving the power of handhelds.
  * **1990s (Console Wars):** Overlapping lifecycles began. The SNES dominated early, but the entry of the original PlayStation in 1994 aggressively cracked the market, peaking at an unprecedented 136.17M annual sales units in 1997.
  * **2000s (Transition Cycles):** The launch of the PS2 in 2000 systematically absorbed legacy PS1 volume. The late 2000s became highly fragmented, with the Nintendo DS showing massive sustained growth alongside direct PS3 and Xbox 360 competition.
  * **2010s (Maturity & Saturation):** The shift from PS3 to PS4 around 2013 showed that the older PS3 still maintained a long, highly profitable sales tail because of a massive active user base.
* **Business Action:** Don't pull software inventory for a dominant console the second its successor comes out. Wind down hardware procurement, but maintain software depth for the older system to cash in on that high-margin, long-tail market.

---

##  Methodology & Data Caveats

* **Filtering Noise (Aggregation Decision):** The raw dataset contains thousands of low-selling or independent publishers. To keep the dashboard clean and actionable for executive decision-making, the publisher metrics are focused strictly on the **Top 10 Publishers**. This cuts out the background noise while still capturing the vast majority of true market activity.
* **Handling Missing Data & Precision:** Rows with extensive missing fields (such as missing Platform and Global Sales) were removed (26 records) to maintain data integrity. Records with missing year data (271 records) were excluded from time-series charts but kept for overall preference totals. Small percentage numbers were rounded for visual clarity.
* **The 2017–2020 Sales Drop:** The dashboard charts show a sharp drop-off in sales from 2017 to 2020. This is a **data collection constraint** (incomplete historical records for those specific years in the raw dataset) rather than an actual macroeconomic market crash. Our expansion strategy should ignore this drop-off and assume steady real-world market sizes.
  


