# ⚡ Distribution Network Analysis: Capacity Planning for Electric Vehicle (EV) Adoption

## 📌 Project Overview

**PowerCharge Utilities** is a leading electric utility company operating in an evolving energy landscape. With the rapid adoption of electric vehicles (EVs), the company faces increasing stress on its distribution network. This project leverages data analysis to assess current grid capacity, detect potential risks, and propose optimization strategies to ensure reliable service while supporting sustainability goals.

---

## 🧠 Business Problem

The EV transition introduces several critical challenges for PowerCharge Utilities:

- **🔺 Increased Load Demand** from widespread EV adoption, especially during peak hours.
- **🧯 Grid Overloads** causing voltage fluctuations and localized outages.
- **🙍‍♂️ Customer Expectations** for reliable, convenient charging experiences.
- **💸 Cost Pressures** to upgrade infrastructure efficiently without overspending.

---

## 🎯 Project Objectives

- ✅ Evaluate current network capacity using historical EV and power usage data.
- 🚨 Detect grid vulnerabilities and bottlenecks due to charging station distribution.
- 🛠️ Recommend upgrade strategies to balance demand and reliability.
- 📊 Provide data-driven insights for executive planning and sustainability alignment.

---

## 🔍 Why This Project Matters

| Reason | Description |
|--------|-------------|
| 💡 Customer Retention | Reliable EV charging keeps customers satisfied and loyal. |
| 📈 Revenue Growth | Expanding EV support unlocks new revenue streams. |
| 🌱 Sustainability Goals | Supports emission reduction and green energy adoption. |
| ⚖️ Regulatory Compliance | Meets grid performance and planning standards. |
| 🧪 Innovation | Utilizes data analytics for proactive energy management. |

---

## 🧾 Data Description

### 📊 A. Electric Vehicle (EV) Distribution Data

- `Timestamp` — Date/time of usage
- `Geographical Area` — Region of consumption
- `Customer Type` — Residential / Commercial
- `Electricity Consumption (kWh)`
- `EV Charging Station Location` — Lat/Long
- `Charging Specifications` — Power ratings, charger type
- `EV Type` — e.g., Scooter, Sedan, SUV
- `Charging Habit` — Daily, Weekly, etc.
- `Number of EVs` — Vehicle count by area

### 🗺️ B. Geospatial Data

- `Substation ID`
- `Substation Location` — Coordinates
- `Transmission Line Capacity (MW)`

### 🌦️ C. Weather Data

- `Temperature (°C)`
- `Precipitation (mm)`
- `Weather Conditions` — Clear, Rainy, etc.

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| `Python` | Programming language |
| `NumPy` | Numerical computing |
| `Pandas` | Data manipulation |
| `Matplotlib`, `Seaborn` | Data visualization |
| `GeoPandas` | Geospatial data analysis |
| `Jupyter Notebook` | Interactive reporting |

---

## 🧪 Methodology

1. **Exploratory Data Analysis (EDA):**
   - Identify consumption patterns
   - Examine EV behavior and customer profiles

2. **Capacity Assessment:**
   - Calculate Consumption-to-Capacity Ratios for each substation
   - Identify overloaded or at-risk substations

3. **Geospatial Visualization:**
   - Map EV stations and substations
   - Analyze spatial mismatch or inefficiencies

4. **Weather Correlation:**
   - Evaluate relationship between consumption and weather conditions

5. **Insights Generation & Visualization:**
   - Develop clear, actionable charts and maps for stakeholders

---

## 📈 Key Insights & Findings

1. ⚡ **Electricity Consumption**: Centered around **500 kWh**, with significant variation indicating unequal demand distribution across regions.

2. 🚗 **EV Types & Charging Habits**: **Electric scooters** dominate. Most users charge **daily**, placing consistent demand on the network.

3. 🏢 **Consumer Type**: The majority are **commercial users**, typically with higher power needs.

4. 🗺️ **Geospatial Mismatch**: Some **EV charging stations are too far** from corresponding substations, potentially leading to transmission inefficiencies.

5. 🚨 **Network Capacity**: Substations with a **high Consumption-to-Capacity Ratio** signal risk of overload. Interestingly, **EV count alone does not predict overload**, suggesting other demand factors at play.

6. 🌦️ **Weather Conditions**: Weak correlation between weather variables and electricity use, indicating behavioral or structural drivers are more significant.

---

## 🧭 Business Recommendations

Based on analysis and business context, the following steps are recommended for **PowerCharge Utilities**:

1. **📍 Prioritize Substation Upgrades**  
   Upgrade substations and transmission lines with high **Consumption-to-Capacity Ratios**, especially those serving remote EV stations.

2. **🗺️ Geospatial Planning for Infrastructure**  
   Leverage geospatial analysis to identify optimal locations for **new substations** or **upgrades** near high-demand clusters.

3. **🔄 Demand Side Management**  
   Implement strategies like **time-of-use pricing** to encourage EV users to charge during **off-peak hours**, reducing peak load stress.

4. **📡 Advanced Monitoring & Predictive Analytics**  
   Deploy real-time monitoring systems to detect **load anomalies**, and use predictive models for **preventive maintenance** and **capacity forecasting**.

5. **💰 Cost-Benefit Analysis for Upgrades**  
   Assess upgrade scenarios using a detailed CBA, considering:  
   - Infrastructure costs  
   - Expected increase in capacity  
   - Revenue potential from new EV users  
   - Reliability impact  

6. **🤝 Customer Engagement**  
   Communicate clearly with customers about ongoing upgrades and **how changes will improve service reliability** and EV support.

> By implementing these strategies, PowerCharge Utilities can strengthen its distribution network, ensure reliable power delivery in the EV era, and align with sustainability and cost-efficiency goals.



