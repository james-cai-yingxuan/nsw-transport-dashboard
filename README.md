# nsw-transport-dashboard
Tableau dashboard analysing NSW public transport performance and usage trends.
# NSW Public Transport Analysis | Tableau Dashboard

**Transport Demand Analysis | Trend Monitoring | Operational Insights | Business Intelligence**

## 1. Project Overview

This project analyses public transport usage across New South Wales (NSW), Australia, using an interactive Tableau dashboard to explore passenger demand, transport mode preferences, peak and off-peak travel patterns, and station-level activity.

The analysis covers available transport data from approximately 2016 to 2025, incorporating train, bus, light rail, ferry and metro services.

The objective is to transform transport usage data into actionable business insights that can support service planning, resource allocation and operational decision-making.

**Key analytical objectives:**
- Examine long-term passenger demand trends and identify changes in travel behaviour.
- Compare transport mode usage to understand demand distribution across the network.
- Evaluate peak and off-peak travel patterns to identify potential capacity requirements.
- Identify high-demand railway stations and assess passenger flow.
- Develop an interactive dashboard to support data-driven transport planning.

## 2. Business Problem

Public transport operators must continuously balance passenger demand, service availability and operational efficiency.

Fluctuating passenger volumes, uneven station demand and changing travel patterns can lead to inefficient resource allocation, overcrowding during peak periods and underutilised services during quieter hours.

The COVID-19 pandemic also significantly disrupted transport demand, creating additional challenges for forecasting and service planning.

This project addresses four key business questions:

1. **Demand Trends:** How has public transport usage changed over time, particularly before and after COVID-19?
2. **Transport Mode Performance:** Which transport modes account for the highest passenger volumes, and how has their relative demand evolved?
3. **Capacity Planning:** How does passenger demand differ between peak and off-peak periods?
4. **Network Efficiency:** Which railway stations experience the greatest passenger activity, and how balanced are passenger entries and exits?

By addressing these questions, the dashboard provides an analytical foundation for identifying potential improvements in transport capacity, scheduling and resource utilisation.

## 3. Dataset Description

The project uses NSW public transport patronage data, covering multiple transport modes and railway stations across the network.

The dashboard incorporates the following analytical dimensions:

| Data Category | Description |
|---|---|
| Time Period | Monthly observations from approximately 2016–2025 |
| Transport Mode | Train, Bus, Light Rail, Ferry and Metro |
| Passenger Demand | Number of recorded passenger trips |
| Travel Period | Peak and off-peak passenger activity |
| Station Information | Railway station names and passenger volumes |
| Station Activity | Passenger entries and exits over 24 hours |

**Data characteristics:**

- Time-series data supporting the identification of long-term demand patterns.
- Categorical data enabling comparisons between transport modes.
- Station-level data supporting identification of high-demand locations.
- Peak and off-peak travel metrics supporting operational capacity analysis.

The dashboard also contains an unallocated transport category, which should be considered when evaluating data completeness and categorisation.

*Data limitations:* The dashboard provides aggregated observations rather than individual passenger journey records. Different transport modes may have different reporting periods, and the underlying data would need to be reviewed to confirm dataset completeness, calculation definitions and comparability.

## 4. Analysis Approach

The analysis follows a structured business intelligence workflow, progressing from data preparation to visualisation and business interpretation.

### Step 1: Data Preparation and Validation

- Organised public transport records by date, transport mode and station.
- Reviewed transport mode classifications to support consistent reporting.
- Considered missing values, unallocated records and differences in reporting coverage.
- Structured the dataset to support time-series, categorical and station-level comparisons.

### Step 2: Transport Demand Trend Analysis

Developed a monthly time-series visualisation to examine passenger demand across transport modes.

The analysis focused on:

- Identifying long-term demand patterns.
- Detecting significant changes in passenger activity.
- Assessing the impact of COVID-19 disruptions.
- Comparing demand recovery between transport modes.

### Step 3: Transport Mode Comparison

Created a horizontal bar chart to compare recorded passenger trips across transport modes.

This analysis identifies the modes responsible for the largest share of recorded usage and provides a basis for evaluating differences in network demand.

### Step 4: Peak vs Off-Peak Analysis

Used a stacked bar chart to compare passenger activity during peak and off-peak periods.

This analysis supports the identification of demand concentration and potential opportunities to improve service scheduling and capacity allocation.

### Step 5: Station-Level Demand Analysis

Ranked railway stations by passenger entries to identify high-demand transport locations.

Additionally, developed a scatter plot comparing passenger entries and exits to examine the relationship between inbound and outbound passenger activity.

### Step 6: Dashboard Development

Consolidated the analysis into an interactive Tableau dashboard containing:

- Monthly transport usage trends.
- Total trips by transport mode.
- Peak vs off-peak comparisons.
- Highest-volume railway stations.
- Passenger entries vs exits.

The dashboard brings together network-wide and station-level perspectives to support exploration of operational performance.

## 5. Key Insights

### Insight 1: COVID-19 Caused a Significant Disruption to Public Transport Demand

The transport usage trend shows a substantial decline in passenger activity around early 2020 across major transport modes.

Train usage declined from approximately 20–25 million monthly trips immediately before the disruption to around 5 million during the initial decline, while bus patronage also experienced a significant reduction.

Although passenger activity subsequently recovered, the dashboard indicates that demand remained below pre-pandemic levels for much of the observed recovery period.

**Business implication:** Historical demand assumptions may no longer accurately reflect current travel behaviour. Transport planning should incorporate more recent patterns rather than relying exclusively on pre-pandemic passenger volumes.

### Insight 2: Train and Bus Services Dominate Recorded Public Transport Usage

The transport mode comparison indicates that train and bus services account for the largest recorded passenger volumes.

Across the displayed reporting data:

- Train services recorded approximately 2.2 billion trips.
- Bus services recorded approximately 2.1 billion trips.
- Light rail, ferry and metro services recorded substantially lower cumulative volumes.

These differences should be interpreted alongside route coverage, system maturity and reporting-period availability.

**Business implication:** Train and bus networks represent major areas for demand management and operational planning. Improvements to their scheduling and capacity utilisation could affect a substantial proportion of recorded passenger journeys.

### Insight 3: Peak Travel Demand Is Substantially Higher Than Off-Peak Demand

The peak vs off-peak comparison indicates that peak-period passenger activity is approximately twice the off-peak volume within the displayed comparison.

This demonstrates a concentration of travel demand during particular periods.

**Business implication:** Transport operators may benefit from aligning service frequency, vehicle capacity and staffing requirements more closely with actual passenger demand.

### Insight 4: Passenger Demand Is Concentrated at Major Railway Stations

The station-level analysis identifies several major locations with high passenger entry volumes.

The highest recorded stations in the displayed ranking include:

| Station | Recorded Entries |
|---|---:|
| Town Hall Station | 6,053,280 |
| Central Station | 6,008,880 |
| Wynyard Station | 4,595,440 |
| Parramatta Station | 2,581,120 |
| North Sydney Station | 1,763,120 |

Town Hall, Central and Wynyard account for a substantial proportion of passenger activity among the highest-ranked stations shown.

**Business implication:** High-demand stations may require greater operational attention, particularly regarding crowd management, passenger movement and service coordination.

### Insight 5: Passenger Entries and Exits Exhibit a Strong Positive Relationship

The entries vs exits scatter plot demonstrates a strong positive relationship between station entry and exit volumes.

Higher-entry stations generally exhibit correspondingly higher exit volumes, with most observations located close to the equal-volume reference line.

**Business implication:** Entry and exit data can be used to establish baseline station activity patterns. Significant deviations from the expected relationship may warrant further investigation into passenger movement, reporting differences or station-specific operational characteristics.

## 6. Recommendations

Based on the observed patterns, the following recommendations could support improved transport planning and operational efficiency.

### Recommendation 1: Adopt Demand-Responsive Service Scheduling

Review service frequency and vehicle allocation using recent monthly patronage trends rather than relying solely on historical timetables.

**Potential business value:**
- Improve alignment between transport supply and passenger demand.
- Reduce unnecessary service capacity during lower-demand periods.
- Support more efficient use of operational resources.

### Recommendation 2: Prioritise Capacity Planning During Peak Periods

Use peak and off-peak demand analysis to identify opportunities for targeted capacity adjustments.

**Potential business value:**
- Reduce overcrowding risks during high-demand periods.
- Improve passenger experience and network reliability.
- Support more effective vehicle and workforce allocation.

### Recommendation 3: Focus Operational Monitoring on High-Demand Stations

Prioritise major stations, including Town Hall, Central and Wynyard, for more detailed operational assessment.

Consider reviewing passenger circulation, station staffing, platform activity and interchange requirements.

**Potential business value:**
- Improve passenger flow management.
- Identify opportunities to mitigate congestion.
- Support prioritisation of infrastructure and operational investment.

### Recommendation 4: Strengthen Post-Pandemic Demand Forecasting

Incorporate recent transport usage patterns into forecasting models and evaluate demand separately by transport mode.

**Potential business value:**
- Improve the relevance of passenger demand forecasts.
- Support more informed timetable planning.
- Reduce the risk of capacity decisions based on outdated assumptions.

### Recommendation 5: Implement Ongoing Performance Monitoring

Extend the dashboard to track relevant operational metrics such as:

- Monthly and year-on-year patronage growth.
- Peak-to-off-peak demand ratios.
- Station-level demand changes.
- Passenger entries and exits.
- Transport mode demand recovery.

**Potential business value:**

Establish a repeatable reporting framework that improves visibility of
