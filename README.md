# Coffee Quality Institute — Power BI Dashboard

A 5-page interactive Power BI report that explores the Coffee Quality Institute (CQI) cupping data.  
This repository includes the `.pbix` file and the
screenshots of each report page for quick reference.

> **Files**
>
> - `CQI.pbix` — the full Power BI report  
> - `Page_1,...Page_5` — high-resolution screenshots of each page

---

## 📊 Report Pages

### Page 1 — Quality Drivers Overview
Core scatter visuals show how **Aroma, Body, Balance, Acidity, Flavor, Aftertaste** relate to **Total Cup Points**.  
Slicers allow filtering by **Country of Origin** and **Variety**.
  
![Page 1](https://github.com/srk5555/Cofee_Quality_Institute_Analysis/blob/main/Page_1.png?raw=true)

### Page 2 — Processing Method Deep-Dive
Matrix with per-method averages (aroma, balance, body, flavor, aftertaste, acidity, uniformity) and a bar chart of **Average Total Cup Points by Processing Method**.  
Country and variety slicers included.
  
![Page 2](https://github.com/srk5555/Cofee_Quality_Institute_Analysis/blob/main/Page_2.png?raw=true)

### Page 3 — Origin Insights
Table repeats method averages for context and a bar chart of **Sum of Total Cup Points by Country of Origin** to compare top-performing origins.
  
![Page 3](https://github.com/srk5555/Cofee_Quality_Institute_Analysis/blob/main/Page_3.png?raw=true)

### Page 4 — Defects & Distribution
Monthly trends for **Category One** and **Category Two Defects**, defect counts by **Variety**, and distribution of **Variety counts vs Total Cup Points**.  
High-level cards show total cup points and total defects.
  
![Page 4](https://github.com/srk5555/Cofee_Quality_Institute_Analysis/blob/main/Page_4.png?raw=true)

### Page 5 — Harvest, Region & Physicals
Breakdowns of **Total Cup Points** by **Processing Method**, **Harvest Year**, **Region**, and **Variety**.  
Additional visuals cover **Bag Weight by In-Country Partner**, **Moisture % vs Total Cup Points**, and **Bean Color** filters.
  
![Page 5](https://github.com/srk5555/Cofee_Quality_Institute_Analysis/blob/main/Page_5.png?raw=true)

---

## 🧱 Data Model (High Level)
- (CQI cupping records; cleaned and standardized)
- Fact table: cupping scores & attributes (aroma, body, balance, flavor, aftertaste, acidity, uniformity, defects, total cup points)
- Dimensions: country of origin, variety, processing method, harvest year, region, color, in-country partner
- Simple calculated measures for page KPIs (e.g., *Sum of Aroma*, *Sum of Balance*, *Sum of Acidity*, etc.)

> **Tip:** For exploratory analysis, start at **Page 1** and filter by country or variety to see how score components move together.  
Then jump to **Page 2** to understand how processing influences profile and cup score.

---

## ▶️ How to Open
1. Clone/download this repository.
2. Open `CQI.pbix` with **Microsoft Power BI Desktop** (June 2023 or later recommended).
3. Message me for the Source Dataset for the dynamic working of the PowerBI report.
4. Refresh the report to validate connections.

---




