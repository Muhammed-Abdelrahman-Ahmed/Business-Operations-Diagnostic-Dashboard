# Business-Operations-Diagnostic-Dashboard

### Project Overview
This project represents a comprehensive, end-to-end data analytics lifecycle. Starting from a raw, unorganized dataset, the objective was to perform deep exploratory and diagnostic analysis to uncover underlying business trends, operational bottlenecks, and financial performance. 

The final deliverables include a detailed written diagnostic report with recommended actions, alongside two interactive Power BI reports designed for both macro-level financial tracking and micro-level logistics operations, with monitoring dashboard for main KPIs and necessary visuls. 

---

### Tech Stack & Methodology
* **Data Processing & ETL:** Microsoft Excel (Power Query)
* **Data Modeling:** Power Pivot, DAX (Data Analysis Expressions)
* **Data Visualization & BI:** Microsoft Power BI
* **Key Skills Applied:** Exploratory Data Analysis (EDA), Diagnostic Analysis, Relational Data Modeling (Star Schema), Data Storytelling, Business Intelligence Reporting.

---

### ⚙️ Analytical Workflow
The project was executed through a structured, multi-phase analytical pipeline:

1. **Exploratory Data Analysis (EDA):** Conducted an initial deep dive into the raw dataset to understand variable distributions, relationships between columns, and identify data anomalies.
2. **Data Cleaning & Transformation (ETL):** Utilized **Power Query** to clean the dataset, handle missing values, standardize formats, and shape the data for modeling.
3. **Data Modeling (Star Schema):** Designed a robust relational data model using **Power Pivot**, separating the data into Fact and Dimension tables to optimize query performance and analysis.
4. **Project Briefing:** Established a clear project brief defining the analytical objectives, scope, and key business questions to be answered.
5. **Descriptive & Diagnostic Analysis:** 
   * Transitioned from describing *what* happened to diagnosing *why* it happened.
   * Investigated root causes behind sales trends, financial losses, and operational inefficiencies.
6. **Reporting & Visualization:**
   * Authored a comprehensive written report detailing the analysis results and providing actionable, data-driven recommendations.
   * Developed two separate, targeted interactive reports in **Power BI**.

---

###  Dashboards & Deliverables

#### 1. Financials & Loss Dashboard (Macro Scope)
*Designed for strategic tracking of revenue, profit margins, and identifying areas of financial leakage.*


#### 2. Operations & Logistics Dashboard (Micro Scope)
*Designed for granular tracking of delivery performance, operational efficiency, and product metrics.*


---

# 🔑 Key Insights & Analytics Discoveries

Our end-to-end diagnostic analysis of the Global Super Store dataset (2011–2014, covering 25,000 orders) revealed critical operational bottlenecks and clear avenues for margin recovery[cite: 9]:

*   **The 20% Discount "Tipping Point":** The most critical finding is that whenever applied discounts exceed 20%, transactions systematically flip from profitable to net financial losses. 
This aggressive discounting behavior actively destroyed $921K in gross profits without driving necessary volume, as the highest quantity of units sold actually occurred at a 0% discount.
*   **The Root of Regional & Category Losses:** 
    *   **Tables Subcategory:** Suffered $144,000 in direct losses due to an excessive average discount rate of 29%.
    *   **Southern Asia Market:** Ranks 5th globally in sales but near the bottom in net profit, heavily driven by an unsustainable average discount rate of 27%.
*   **Returns Anomaly (The "Anna Andreadi" Effect):** A disproportionate 61.25% of all returned orders globally are linked to a single salesperson (Anna Andreadi). 
Furthermore, the Office Supplies category drives the majority of returns (60.10%), with the issue heavily concentrated in Binders and Paper within the West region.
*   **Segment Profitability:** The Consumer segment is the highest performing, generating 51% of total profits (while unit economics remain identical across all segments at roughly ~$58 per order, volume is the true profit driver).
*   **Top Performer (Copiers):** The Technology category is the most profitable, spearheaded by Copiers, which yield an exceptionally high average profit margin of 31.72% ($122 profit per order), outperforming Phones due to strict discount discipline.



---
**📂 Repository Structure:**
* `Data/`: Contains the initial raw datasets .
* `Screens/`: Contains high-resolution screenshots of the data model and interactive dashboards.
