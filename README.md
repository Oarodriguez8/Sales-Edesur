# Executive Summary: Commercial and Operational Performance Report (Edesur Dominicana)
**Period:** January 1 to November 30, 2025

---

## 1. Summary of Key Performance Indicators (KPIs)

Overall performance during the analyzed period shows moderate growth in billing and revenue collection compared to the same period last year (Prior Year). However, this coexists with a reduction in the volume of energy billed and a decline in operational loss control.

* **Total Billing:** **RD$ 46,056 MM** (Millions of Pesos), representing an increase of **+1.49%** vs. the prior year.
* **Collections (Revenue):** **RD$ 44.8K MM** (where K represents thousands, equivalent to RD$ 44,800 MM). This records an increase of **+2.66%** compared to the prior year.
* **Collection Efficiency:** **97.2%**, achieving an improvement of **+1.15%** over last year, which consolidates excellent collection management relative to billed commitments.
* **Billed Energy:** **4,462.7 GWh**, representing a **drop of -2.71%** in the volume of energy delivered compared to the prior year.
* **Service Availability (ASAI):** Remains stable and robust at **95.4%** (0% variance).

<img width="1387" height="781" alt="Reporte-Edesur" src="https://github.com/user-attachments/assets/3191bf70-a6a5-4f03-82f8-8f9f5ae9512e" />

---

## 2. Diagnosis of the Critical Problem

Even though monetary revenues increased (potentially driven by tariff adjustments or increases in contract value), the dashboard exposes a **severe operational deviation**:

### **Disproportionate Increase in Energy Losses (32.1%)**
This key indicator suffered a deterioration of **-4.63%**, rising from 30.6% (prior year) to the current **32.1%**.

* **Impact of the gap:** While the volume of billed energy **decreased by -2.71%** (dropping from 4.6K GWh to 4,462.7 GWh), the percentage of losses rose considerably. This implies that a significant portion of the purchased or distributed energy is being diverted through technical losses (grid deficiencies) or non-technical losses (fraud, illegal connections, metering failures).
* **Infrastructure gap (Telemetering / Smart Metering):** The provincial breakdown reveals a strong correlation between low telemetering rates and operational performance. Provinces such as **San Juan (34.0% telemetering coverage)** and **Barahona (40.5% telemetering coverage)** show a critical lag compared to the Distrito Nacional, which leads with **96.6%**.

---

## 3. Recommendations and Next Steps

To contain the financial impact resulting from losses and maximize the high collection efficiency, the following strategic actions are proposed:

1. **Targeted Inspection Plan in High-Loss Areas:**
   * Deploy network audit and commercial fraud inspection operations with priority in **San Juan, Barahona, and Baní**, due to their low levels of metering protection.
   * Execute energy balances via macro-metering on circuits within **Zone 1 (Distrito)**. Although it boasts 96.6% telemetering coverage, this zone accounts for **59.7% of total billing** (RD$ 27,516 MM); therefore, any marginal reduction in its losses will significantly impact cash flow.

2. **Acceleration of Telemetering Investments (CAPEX):**
   * Establish a mandatory target to raise the overall telemetering indicator (currently at **81.2%**), prioritizing technical funding in Zone 4 and Zone 5 to reach a minimum of 75% coverage over the next two quarters.

3. **Seasonality Management and Grid Maintenance:**
   * The monthly billing chart identifies clear seasonality, with peak maximums between **August and October** (exceeding RD$ 4,500 MM monthly). It is recommended to pull forward preventive grid maintenance to the months of April-May to minimize the increase in technical losses caused by thermal saturation of the power lines during peak demand season.

4. **Data Governance Optimization in the Dashboard (IT Note):**
   * Standardize scale labels: The Collections nomenclature uses **"K"** to refer to billions (thousands units on the KPI's visual scale), which causes confusion with Billing, which is explicitly denoted in **"MM"**. It is suggested to homogenize both metrics to "MM" (e.g., RD$ 44,800 MM).
   * Review the logic for the **Billed Contracts** KPI (10,462,136), which shows a drop alert of **-88.54%** vs. the prior year (91.3M). It is necessary to confirm if the historical data contained duplicates or if there is a calculation error in the DAX formula for time comparison.
