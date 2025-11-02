## 🚢 Global Supply Chain & Logistics Analytics Dashboard | Power BI

### 📊 **End-to-End Supply Chain Intelligence & Decision-Support System**

This project is a **real-world logistics analytics dashboard** built using synthetic supply-chain data modeled on industry patterns.
It simulates enterprise-grade analytics similar to global logistics leaders and was developed as part of a data-driven business case & interview-ready portfolio project.

The dashboard delivers **visibility, optimization & predictive intelligence** across the global supply chain cycle using Power BI & SQL.

---

## ✅ **Key Features**

* Shipment performance monitoring (global routes & timelines)
* Customer value segmentation & spend analysis
* Cost, revenue & efficiency KPI-tracking
* Route-level operations intelligence
* Scenario-based opportunity modelling
* Emissions, fuel & sustainability analytics
* Predictive modeling: cost, delays, emissions & customer satisfaction

---

## 🎯 **Ultimate Business Solution Provided**

This dashboard enables logistics & supply-chain teams to:

* Reduce operational delays & route inefficiencies
* Enhance customer satisfaction & identify high-value segments
* Improve cost-to-serve & resource utilization
* Meet sustainability & emission-reduction goals
* Make proactive decisions using predictive analytics
* Improve supply-chain reliability & cost efficiency end-to-end

📌 **Core Outcome:**

> A complete 360° supply-chain command center turning raw logistics data into **actionable operational, customer & sustainability insights**.

---

## 🧠 **Tech Stack**

| Category    | Tools                                 |
| ----------- | ------------------------------------- |
| Power BI    | Dashboard, DAX, Modelling             |
| SQL         | Data import, cleaning, transformation |
| CSV Dataset | Raw logistics dataset                 |
| Excel/Word  | Documentation, Insights               |
| GitHub      | Project hosting & versioning          |

---

## 🗂️ Project Repository Structure

```
📁 Global-Supply-Chain-Dashboard
│── 📄 README.md
│── 📁 Data
│   ├── SupplyChainDataset.csv
│   └── SupplyChainDatabase.sql
│── 📁 PowerBI
│   └── GlobalSupplyChainDashboard.pbix
│── 📁 Dashboard Images
│   ├── Shipment_Overview.png
│   ├── Customer_Value_Analysis.png
│   ├── Financial_Operational_KPIs.png
│   ├── Route_Efficiency.png
│   ├── Opportunity_Modelling.png
│   ├── Sustainability_Emissions.png
│   └── Predictive_Insights.png
│── 📁 Documentation
│   ├── Insights_Report.docx
│   └── DAX_Measures.docx
```

---

## 🧾 **Dataset Overview**

✔️ **36 Columns** covering operations, customer, sustainability & predictive attributes
(Shipment, Revenue, Cost, Emissions, Ports, Customer, Route, Scenario, Forecasts)

---

## 📊 Dashboards & Key Metrics

### **1️⃣ Shipment Overview**

**Metrics:**

* Total Shipments
* Avg Delivery Days
* On-Time Delivery %
* Avg Cost per Shipment

**Visuals:** Column Chart, Line Trend, Cost by Shipment Mode, Region Slicer

📍 *Dashboard Image*

<img width="1326" height="744" alt="1  SHIPMENT OVERVIEW DASHBOARD" src="https://github.com/user-attachments/assets/51ec461f-0a10-443f-99be-e073ba13d5ba" />


---

### **2️⃣ Customer Value Analysis**

**Metrics:** Revenue, Cost Savings, Efficiency, Satisfaction

**Visuals:**
Top Customers Charts, Segmentation Treemap, Spend Trend, Bubble Chart

📍 *Dashboard Image*

<img width="1324" height="746" alt="2  CUSTOMER VALUE   PERFORMANCE DASHBOARD" src="https://github.com/user-attachments/assets/25ad54d2-12f0-429e-8c75-6f88c747465a" />


---

### **3️⃣ Financial & Operational KPIs**

**Metrics:** Profit per Route, Cost per Container, Fuel Use, Emissions, Dwell Time

📍 *Dashboard Image*

<img width="1324" height="746" alt="3  Financial   Operational KPIs dashboard" src="https://github.com/user-attachments/assets/21c070ed-2941-498c-a30c-1753490581f2" />


---

### **4️⃣ Route Efficiency**

**Metrics:** Delivery Delay, Dwell Time, Emissions per Route, Route Performance Score

📍 *Dashboard Image*

<img width="1327" height="743" alt="4  Route Efficiency Dashboard" src="https://github.com/user-attachments/assets/12dd26cb-e0a4-4c8f-aaba-c5e315eacc25" />


---

### **5️⃣ Opportunity Modelling**

**Metrics:** Cost Savings, Efficiency Gains, Delivery Impact, Satisfaction Impact

📍 *Dashboard Image*

<img width="1323" height="743" alt="5  Opportunity Modelling Dashboard" src="https://github.com/user-attachments/assets/aa880a69-4112-4dbb-8595-a6aef64b87f1" />


---

### **6️⃣ Sustainability & Emissions**

**Metrics:** Fuel Use, CO2 Emissions, Sustainability Score, Offsets

📍 *Dashboard Image*

<img width="1323" height="742" alt="6  SUSTAINABILITY   EMISSIONS PERFORMANCE" src="https://github.com/user-attachments/assets/dac97ea7-573a-4b6d-a755-c70583bcd799" />


---

### **7️⃣ Predictive Insights**

**Metrics:** Predicted Cost, Revenue, Emissions, Delivery Time, Satisfaction

📍 *Dashboard Image*

<img width="1322" height="745" alt="7  PREDICTIVE INSIGHTS DASHBOARD" src="https://github.com/user-attachments/assets/b4bd685b-1435-45e4-b785-833143cb4dd8" />


---

## 📐 **DAX Measures Used**

```DAX
Total Shipments = COUNT('Supply Chain Data'[ShipmentID])

Average Cost per Shipment = AVERAGE('Supply Chain Data'[Cost])

Average Delivery Days = AVERAGE('Supply Chain Data'[AverageDeliveryTime])

Average Emissions per Shipment = AVERAGE('Supply Chain Data'[Emissions])

Cost per Container =
DIVIDE(SUM('Supply Chain Data'[Cost]), SUM('Supply Chain Data'[TotalShipments]))

On-Time Delivery % = AVERAGE('Supply Chain Data'[OnTimeDeliveryRate])

Operational Utilization Rate = AVERAGE('Supply Chain Data'[SatisfactionScore])

Profit per Route =
SUM('Supply Chain Data'[Revenue]) - SUM('Supply Chain Data'[Cost])

Route Performance Score % =
AVERAGE('Supply Chain Data'[SustainabilityScore])

Delivery Delay Days = AVERAGE('Supply Chain Data'[ImpactOnDeliveryTime])
```

---

## 🧾 SQL Import Script (Folder contains .sql backup)

```sql
-- Importing Logistics & Shipment Dataset
SELECT * FROM SupplyChainData;
```

---

## 📥 How to Run This Project

1. Clone the repository
2. Import SQL file into DB (optional; or use CSV)
3. Open `.pbix` file in Power BI Desktop
4. Refresh data & explore dashboards

---

## 👤 Author

👨‍💻 Author

Souvik Bose
- 🌐 [LinkedIn](https://www.linkedin.com/in/souvik-bose-7272ab1b3/)

**Skills:** Power BI, SQL, Python, Data Analysis, Supply Chain

---

## ⭐ If you like this project

✅ Star the repo

✅ Follow me for more BI & Data Science projects

---




