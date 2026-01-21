# 🏙️ Dubai Real Estate Market Analysis (2000–2025)

### 📊 Project Overview
This project is a comprehensive analysis of the Dubai Real Estate market using **Power BI**, analyzing **1.6 million real estate transactions** sourced directly from the Dubai Land Department (DLD).

The goal was to transform raw government open data into an interactive executive dashboard to track transaction trends, identify high-value investment hubs, and visualize the market's growth to a total valuation of **AED 6.3 Trillion**.

<img width="1736" height="727" alt="Dashboard Preview" src="https://github.com/user-attachments/assets/4cf5ee48-9453-4898-9c99-8aa6be90bbdd" />

*(Note: Visual based on 1.6M rows of official transaction data)*

---

### 📥 Download & Usage
Due to the large dataset size (1.6M+ rows), the Power BI file is hosted externally.

1. **[Click Here to Download the Project File (.pbix)](https://drive.google.com/file/d/1UnJoICFj5DO58AZSc56BU0pvyyxDvS6a/view?usp=sharing)** via Google Drive.
2. Open the file in **Microsoft Power BI Desktop**.
3. Use the **Year Slider** (top right) to filter specific market cycles (e.g., the 2021–2025 Boom).
4. Click on any bar in the "Top 10 Areas" chart to cross-filter the map and KPIs.

---

### 💾 Data Source
* **Source:** [Dubai Pulse / Dubai Land Department (Open Data)](https://www.dubaipulse.gov.ae/data/dld-transactions/dld_transactions-open)
* **Dataset:** Real Estate Transactions (Golden Record)
* **Note:** This project utilizes official government data to ensure accuracy and market validity.

---

### 🔍 Key Insights & Findings
* **Market Valuation:** Validated a total market transaction value of **AED 6.3 Trillion** since 2000.
* **Top Location:** **Marsa Dubai (Dubai Marina)** remains the historical leader in transaction value, outperforming newer developments.
* **Post-COVID Recovery:** A significant volume spike is observed from **2021 to 2025**, with the market reaching peak activity levels in 2025.
* **Investment Trends:** Residential units dominate the transaction volume (87%) compared to commercial properties.

---

### 🛠️ Technical Skills Demonstrated
* **Data Engineering (Power Query):**
    * Cleaned and transformed a 1.6M+ row dataset, filtering out legacy pre-2000 records.
    * Standardized inconsistent date formats (Hijri/Gregorian) to create a reliable timeline.
    * Created custom geospatial columns (Area + City + Country) to resolve map visualization errors.
* **Data Modeling:**
    * Designed a robust **Star Schema** with a dedicated Date Table connected to the Fact Table (1:* relationship).
    * Validated relationships to ensure accurate time-intelligence filtering across decades.
* **DAX (Data Analysis Expressions):**
    * Developed custom measures for **Average Price per Sq. Meter** to track true market inflation, avoiding the volatility of simple average prices.
    * Implemented dynamic currency formatting (AED) and large number scaling (Millions/Trillions).
* **Executive Visualization:**
    * Designed a high-contrast "Dark Mode" dashboard for professional presentation.
    * Implemented **Geospatial Mapping** to visualize sales distribution hotspots across the emirate.
    * Used "Top N" filtering to isolate the top 10 performing neighborhoods by value.

---

### 👤 Author
* **Name:** Syed Affan Ahmed
* **Role:** Aspiring Data Analyst | Power BI Developer
* **Location:** United Arab Emirates
* **Connect on LinkedIn:** [View Profile](https://www.linkedin.com/in/syed-affan-ahmed-570870236/)
