# Cultivating Change: Data Insights on Agrifood Emissions

## Project Background
This project analyzes data related to agrifood emissions, aiming to provide actionable recommendations for policymakers, producers, and consumers to adopt more sustainable practices. The study covers:
- The environmental impact of different agricultural activities and food production processes.
- Data-driven insights to encourage greener practices within the agrifood sector.

The analysis provides insights and recommendations on the following key areas:
- **CO2 Emissions & Population Trends** – Examining the link between global CO₂ emissions, temperature rise, and urbanization.
- **Major and Minor CO2 Emitters** – Identifying the countries and factors contributing most to emissions.
- **Forestland & Fire-Related Emissions** – Assessing deforestation and wildfire-related carbon emissions.
- **Barriers to CO2 Reduction & Solutions** – Exploring economic, policy, and behavioral challenges along with mitigation strategies.

The exploratory data analysis used to inspect and clean the data for this analysis can be found [here](https://github.com/GiorgosKastoras/agrifood-co2-emission-analysis/blob/main/Analysis/Exploratory_Data_Analysis.ipynb).

An interactive PowerBI dashboard used to report and explore agrifood emission trends can be found [here](https://github.com/GiorgosKastoras/agrifood-co2-emission-analysis/tree/main/PowerBI_Dashboard).

---

## Data Structure & Initial Checks
The dataset utilized in this project consists of **one main table** with **31 columns**, covering agrifood emissions, population trends, temperature shifts, and forest area data. The primary data sources include FAO and climate research databases.

### Table Overview
- **Agrifood_co2_emission:** Agrifood Emissions Data
- **Number of Columns:** 31
- **Key Fields:** CO2 emissions, population growth, temperature changes, deforestation rates, agricultural production, and urbanization metrics.

---

## Executive Summary
### Overview of Findings
- **~50% of total CO2 emissions come from Asia, making it the largest contributing region.**
- **56% of CO2 emissions are attributed to agrifood system-related practices, indicating the sector's significant impact.**
- **CO2 emissions and urban population have exhibited a consistent upward trend, suggesting a strong correlation between urbanization and emissions.**

![CO2 Emissions by Continent and Category](Images/co2_emissions_overview.png)
![Urbanization and Temperature Trends](Images/urban_temp_trends.png)

---

## Insights Deep Dive
### CO2 Emissions & Population Trends
- **Strong Correlation (0.905):** Over time, global CO₂ emissions and temperature rise together.
- **Population Influence (0.982):** More people mean more emissions, mainly from food production.
- **Urbanization & Temperature (0.912):** Growing populations and rising temperatures are strongly linked.
- **Long-Term Trend:** Emissions increase over years, aligning with industrialization and deforestation.
- **Policy Implication:** Global trends emphasize the need for sustainable agro-food policies.

![Climate Equation: CO₂, Population, and Temperature Shifts](Images/climate_equation.png)


### Major and Minor CO2 Emitters

- **China is the top emitter, contributing 146M total CO2 emissions.**
- **New Caledonia is the lowest emitter, with just 27K total CO2 emissions.**
- **Only Congo, among the top emitters, is not within the 10 most populous countries.**

![Largest & Lowest CO2 Emitters](Images/largest_lowest_emitters.png)

### Top & Bottom CO2 Emission Factors

- **Industrial processes and product use contribute the most emissions.**
- **Agrifood systems, waste disposal, and household food consumption are significant factors.**
- **Pesticide manufacturing is the least polluting factor, followed by fires in humid tropical regions.**

![Top & Bottom CO2 Emission Factors](Images/top_bottom_co2_factors.png)

### Forestland & Fire-Related Emissions

- **Forestland plays a crucial role in mitigating CO2 emissions, with countries like Russia (49.8% forest cover), Finland (73.7%), Chile (24.3%), Romania (30.1%), and Bulgaria (37.5%) leading in preservation.**
- **Countries with significant forest cover show lower net CO2 emissions, as seen with Russia, which has negative net emissions due to its large forest area.**
- **Fire-related emissions fluctuate over time, with peaks in humid tropical areas due to deforestation and wildfires.**
- **In 1997, Indonesian peat fires released 0.81 to 2.57 gigatons of CO2, accounting for 40% of global fossil fuel emissions that year.**

![Importance of Forestland](Images/importance_forestland.png)
![Fire-Related Emissions](Images/fire_emissions_trends.png)

---

## Recommendations
Based on the insights above, we recommend that policymakers and industry stakeholders consider:

- **Redirecting subsidies** to reward sustainable agrifood practices.
- **Implementing carbon pricing and taxes** to discourage high-emission activities.
- **Investing in green technologies** to modernize and decarbonize food production.
- **Expanding consumer awareness campaigns** to drive sustainable choices.
- **Improving supply chain transparency** to track and reduce emissions effectively.

