# Distribution Network Analysis: Capacity Planning for Electric Vehicle (EV) Adoption in North America

## Project Overview

PowerCharge Utilities is a leading electric utility company operating in an evolving energy landscape. With the rapid adoption of electric vehicles (EVs), the company faces increasing stress on its distribution network. This project leverages data analysis to assess current grid capacity, detect potential risks, and propose optimization strategies to ensure reliable service while supporting sustainability goals.
![](electric-vehicles-main-image.jpg)

---

## Business Problem

The transition to EVs introduces several critical challenges for PowerCharge Utilities:

- Increased load demand during peak charging hours
- Grid overloads causing voltage fluctuations and outages
- Customer expectations for reliable charging services
- Infrastructure upgrade costs that need careful optimization

---

## Project Objectives

- Evaluate current network capacity using historical EV and power usage data
- Detect grid vulnerabilities and potential overload points
- Recommend upgrade strategies to balance demand, cost, and reliability
- Provide data-driven insights to support strategic planning

---

## Why This Project Matters

| Reason                 | Description                                                             |
|------------------------|-------------------------------------------------------------------------|
| Customer Retention     | Reliable EV charging improves user satisfaction and loyalty             |
| Revenue Growth         | Supporting EV expansion opens new revenue streams                      |
| Sustainability Goals   | Enables reduced greenhouse gas emissions                                |
| Regulatory Compliance  | Helps meet government energy standards                                  |
| Innovation             | Empowers proactive decision-making using data and analytics             |

---

## Data Description

### A. EV Distribution Data

- `Timestamp`: Date/time of usage
- `Geographical Area`: Region of consumption
- `Customer Type`: Residential or commercial
- `Electricity Consumption (kWh)`
- `EV Charging Station Location`: Coordinates
- `Charging Specifications`: Power ratings, charger type
- `EV Type`: e.g., Scooter, Sedan, SUV
- `Charging Habit`: Frequency of charging
- `Number of EVs`: Count of vehicles per area

### B. Geospatial Data

- `Substation ID`
- `Substation Location`: Coordinates
- `Transmission Line Capacity (MW)`

### C. Weather Data

- `Temperature (°C)`
- `Precipitation (mm)`
- `Weather Conditions`: Clear, Rainy, etc.

---

## Tech Stack

- Python
  - NumPy
  - Pandas
  - Matplotlib
  - Seaborn
  - GeoPandas
- Jupyter Notebook

---

## Methodology

1. **Exploratory Data Analysis (EDA)**  
   Analyze consumption patterns, EV usage, and customer behavior.

2. **Capacity Assessment**  
   Calculate the Consumption-to-Capacity Ratio to identify overloaded substations.

3. **Geospatial Visualization**  
   Map substations and EV stations to evaluate spatial efficiency.

4. **Weather Correlation Analysis**  
   Assess the effect of weather variables on electricity consumption.

5. **Insight Extraction and Visualization**  
   Develop charts, maps, and data-driven recommendations.

---

## Key Insights

1. **Electricity Consumption**: Most values center around 500 kWh, with spikes suggesting location-based variance.
2. **EV Types & Charging Habits**: Electric scooters are the most common; most users charge daily, creating a steady load.
3. **Customer Type**: The majority of users are commercial, contributing higher overall consumption.
4. **Geospatial Distribution**: EV charging stations are widely dispersed and often far from substations.
5. **Network Capacity**: Some substations show high Consumption-to-Capacity Ratios. Surprisingly, the number of EVs doesn't correlate directly with overload risk.
6. **Weather Influence**: Minimal correlation between consumption and weather, suggesting behavioral and infrastructure-driven usage.

---

## Business Recommendations

1. **Prioritize Substation Upgrades**  
   Upgrade substations and transmission lines with high load ratios or located far from EV charging stations.

2. **Geospatial Planning for Infrastructure**  
   Use spatial analysis to guide placement of new substations or upgrades near high-demand clusters.

3. **Demand-Side Management**  
   Implement incentives (e.g., dynamic pricing) to encourage off-peak EV charging.

4. **Advanced Monitoring and Analytics**  
   Deploy smart monitoring tools for real-time performance tracking and issue prediction.

5. **Cost-Benefit Analysis**  
   Evaluate upgrade options based on financial and operational trade-offs.

6. **Customer Engagement**  
   Communicate transparently about upgrades and improvements to service reliability.

> These actions will help PowerCharge Utilities meet rising EV demands, maintain customer satisfaction, manage infrastructure costs, and ensure grid reliability.

---





