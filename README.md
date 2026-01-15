# 🏙️ Dubai Real Estate Market Analysis (2000–2025)

### 📊 Project Overview
This project is a comprehensive analysis of the Dubai Real Estate market using **Power BI**. The goal was to analyze transaction trends, identify high-value areas, and visualize market growth over the last two decades.

The dataset includes **1.6 million real estate transactions** sourced from open government data (Dubai Land Department), covering the period from 2000 to early 2026.

![Dashboard Preview](dashboard_screenshot.png)
*(Note: Visual based on 1.6M rows of transaction data)*

---

### 🔍 Key Insights & Findings
* **Market Growth:** The market has transacted a total of **AED 6.3 Trillion** since 2000.
* **Top Location:** **Marsa Dubai (Dubai Marina)** remains the highest-value area historically, outperforming newer developments.
* **Post-COVID Boom:** A significant sharp rise in transaction value is observed from **2021 to 2025**, reaching peak levels in 2025.
* **Property Preferences:** Residential units dominate the transaction volume compared to commercial properties.

---

### 🛠️ Technical Skills Demonstrated
* **Data Cleaning (Power Query):**
    * Filtered out legacy data (pre-2000) to focus on the modern freehold market.
    * Standardized date formats from mixed Hijri/Gregorian inputs.
    * Created custom columns for geospatial mapping (City/Country concatenation).
* **Data Modeling:**
    * Built a **Star Schema** with a dedicated Date Table connected to the Fact Table (1:* relationship).
    * Validated relationships to ensure accurate time-intelligence filtering.
* **DAX (Data Analysis Expressions):**
    * Created measures for *Total Volume*, *Total Value*, and *Average Price*.
    * Formatted dynamic currencies (AED) and handled large number scaling (Millions/Trillions).
* **Data Visualization:**
    * Designed an interactive **KPI Dashboard** with slicers for year and property type.
    * Implemented Geospatial Mapping to visualize sales distribution across Dubai.
    * Used "Top N" filtering to isolate the top 10 performing neighborhoods.

---

### 📂 How to Use This Project
1.  **Download** the `Dubai_Real_Estate_Market_Analysis.pbix` file from this repository.
2.  Open it in **Microsoft Power BI Desktop**.
3.  Use the **Year Slicer** (top right) to filter the "Boom" period (2021–2025).
4.  Click on any bar in the "Top 10 Areas" chart to cross-filter the map and KPIs.

---

### 📫 Contact & Connect
* **Connect on LinkedIn:** [Click Here to View Profile][(https://www.linkedin.com/in/syed-affan-ahmed-570870236/)]
* **Location:** United Arab Emirates
