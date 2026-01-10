# NERC Power Generation Capacity Analysis (2006–2024)

A Power BI–driven analytical review of Nigeria Electricity Regulatory Commission (NERC) generation licence data, focusing on installed capacity trends, operational performance, fuel mix transition, and geographic distribution of power plants across Nigeria.

---

## 📌 Executive Summary (Regulatory & Management View)

Nigeria’s electricity generation landscape has evolved significantly between 2006 and 2024, marked by capacity expansion, uneven operational performance, and persistent dependence on fossil fuels. This analysis leverages NERC licence data to quantify year-on-year (YoY) performance, identify systemic risks, and highlight opportunities for renewable energy transition.

The dashboard provides regulators and decision-makers with a fact-based view of:

* Installed vs operational generation capacity
* Renewable energy penetration progress
* Fossil fuel dependency risk exposure
* State-level and geographic disparities in power infrastructure

---

## ❓ Business Problem

Despite multiple licensing rounds and policy interventions, Nigeria continues to experience power supply deficits. Key regulatory and strategic questions include:

* Is licensed generation capacity translating into operational power plants?
* How fast is renewable energy adoption relative to fossil fuels?
* Which states are experiencing growth or stagnation in generation capacity?
* What level of systemic risk exists due to fossil fuel dependency?

This project addresses these gaps through structured analytics and YoY performance tracking.

---

## 🧪 Methodology

### Data Source

* Nigeria Electricity Regulatory Commission (NERC) – Generation Licence Dataset (2006–2024)

### Data Model

* Star schema
* Dedicated **Year Dimension Table** (unique years)
* One-to-many relationship: `Year Table → Licensees`
* Single-direction filtering (best-practice time intelligence model)

### Analytical Techniques

* DAX-based measures for capacity, operational status, and fuel segmentation
* Year-on-Year (YoY) trend analysis
* Renewable vs Fossil fuel classification
* Geographic aggregation by state

### Tools

* Power BI Desktop
* DAX (Data Analysis Expressions)

---

## 🧠 Skills Demonstrated

* Power BI Data Modelling (Star Schema)
* Advanced DAX & YoY Time Intelligence
* Energy & Utilities Sector Analytics
* Regulatory & Policy Reporting
* Executive Dashboard Design
* Smart Narrative Development

---

## 📊 Dashboard Pages Overview

### 1️⃣ Executive Overview
### KPIs (top row)
* Total Installed Capacity (MW)
* YoY Capacity Change
* Total Installed Capacity (MW)
* Total Licensees
* % Operational Licensees
* % Non-Operational Licensees
* Renewable Capacity (MW)
* Fossil Fuel Capacity (MW)
  
* Operational Status Breakdown
* Capacity by License Type
* Capacity Trend by Fuel Type
* Top 10 Licensees by Capacity

### 2️⃣ Capacity & Operational Performance

* Licencee Performance
* Trend of Total Licencees Year on Year
* Sum of Total Capicty by Year
* Slicer: Fuel Type | State | Operational Status | Type of Licensee 

### 3️⃣ Fuel Mix & Energy Transition

* Fuel Mix Trend
* Renewable vs Fossil Capacity
* Operational Status by Fuel Type
* Total Licencees by Fuel Type

### 4️⃣ Geographic Insights

* Capacity by State (MW)
* Licensees per State
* State Reliability Score (Advanced KPI)
* Top 5 State by Total Licencee

### 5️⃣ Regulatory Insights & Narratives

* Smart narrative summaries auto-generated using DAX
* Policy-relevant interpretations for management and regulators

---

## 📈 Results & Business Recommendations

### Key Findings

* Installed capacity growth is uneven across years, indicating inconsistent investment patterns.
* A measurable gap exists between licensed and operational capacity.
* Renewable energy adoption is increasing but remains significantly lower than fossil fuel capacity.
* Certain states dominate generation growth, creating geographic imbalance.
* Continued fossil fuel reliance exposes the sector to supply, pricing, and infrastructure risks.

### Recommendations

* Strengthen enforcement and monitoring of non-operational licences.
* Introduce targeted incentives for renewable energy investments.
* Encourage state-level diversification of generation infrastructure.
* Use YoY performance metrics as regulatory benchmarks.

---

## 🚀 Next Steps

* Integrate generation output (MWh) for efficiency analysis
* Add tariff and pricing data for economic impact assessment
* Develop forecasting models for capacity planning
* Implement RAG (Red-Amber-Green) regulatory KPIs
* Publish an executive-facing regulatory dashboard

---

