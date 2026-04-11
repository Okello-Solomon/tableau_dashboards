# 1. US Candy Sales & Distribution Performance Dashboard

## Project Overview

This interactive dashboard provides a comprehensive, data-driven analysis of sales performance, profitability, and logistics operations for a US-based candy distributor.

The dataset combines sales transactions and geospatial shipment data, capturing the full journey from factory locations to customer destinations. It includes detailed information on customer distribution, product categories, shipping modes, and sales targets.

<details>
<summary><strong> View Project Details</strong></summary>
  
## The primary objective of this dashboard is to enable stakeholders to:

- Evaluate overall business performance
- Identify high and low performing products
- Analyze regional sales distribution
- Assess shipping efficiency
- Compare actual sales against targets

The dashboard is designed to transform raw operational data into actionable insights for strategic decision-making and performance optimization.

## Key Performance Indicators (KPIs)

The dashboard provides a high-level snapshot of overall business performance:

- **Total Sales:** 141,784
- **Total Cost:** 48,341
- **Total Gross Profit:** 93,443
- **Profit Margin:** 66%
- **Total Customers:** 5,044
- **Total Units Sold:** 38,654
- **Total Products:** 15
- **Total Cities:** 542
- **Total States:** 59

These KPIs dynamically respond to filters, enabling quick performance evaluation across different dimensions.

## Core Analytical Visualizations
### Sales vs Profit Analysis (Scatter Plot)

A scatter plot visualizes the relationship between Sales and Profit, segmented by Region and Order Volume.

- X-Axis: Sales
- Y-Axis: Profit
- Color: Region
- Size: Volume
**Key Insights:**
- Identifies high-revenue but low-profit regions
- Highlights high-performing regions with strong profitability
- Detects inefficiencies in sales-volume conversion
- Shipping Mode Performance (Tree Map)

## A treemap illustrates the contribution of each shipping mode to total sales:

- Standard Class: 85,490
- Second Class: 27,860
- First Class: 21,319
- Same Day: 7,114

## Regional Sales Trends (Line Chart)

A line chart compares regional performance over time (United States vs Canada).

**Key Insights:**
The Geographic Sales Distribution map provides a clear view of how sales are spread across different cities, enabling stakeholders to track regional sales growth, identify demand patterns and seasonal fluctuations, and compare performance across locations to support data-driven market expansion and resource allocation decisions.

## A filled map displays city-level sales distribution across the United States.

**Key Insights:**
The filled map of city-level sales distribution highlights key demand patterns across the United States by identifying high-performing cities and major sales hotspots, while also revealing underserved or low-performing regions that may require strategic attention. These insights support more informed decision-making in logistics planning, resource allocation, and market expansion by showing where demand is strongest and where growth opportunities exist.

## Product Performance vs Average (Bar Chart)
This bar chart compares product-level sales against the average benchmark of 9,452.
Products performing above average are highlighted in blue, while those below average are shown in gray.
This makes it easy to quickly identify strong-performing and underperforming products.
It supports better decision-making for product improvement and sales optimization.

**Key Insights:**

The visualization identifies top-performing products by comparing sales against the average benchmark. It highlights underperforming products that need attention for improvement. These insights support better inventory planning and marketing optimization.

## State-Level Sales Analysis (Dynamic Bar Chart)

A horizontal bar chart enables interactive analysis by allowing users to filter and explore the data based on key dimensions. It allows selection of the Top N states and filtering by product division (Chocolate, Other, Sugar), making it easier to identify top-performing states and compare sales performance across different product categories.

**Key Insights:**

The visualization identifies top-performing states based on total sales performance.
It enables comparison of sales across product divisions within each state.
This helps support targeted regional strategies and better resource allocation.

## Profit by Division (Bubble Chart)

A bubble chart visualizes profit contribution by product division:

- Chocolate: 88,825
- Other: 4,333
- Sugar: 285

**Key Insights:**
The analysis shows that Chocolate dominates overall profitability, contributing the largest share of returns. In contrast, the Other and Sugar divisions contribute minimally, indicating weaker performance. This highlights potential opportunities for diversification strategies or cost optimization to improve overall business balance and efficiency.

## Target vs Actual Performance (Bullet Chart)

The bullet chart compares actual sales against set targets, showing that Chocolate and Other significantly exceeded their goals, while Sugar fell below its target, highlighting strong performance in some divisions and a need for improvement in others.

- Chocolate: Target = 27,000 | Actual = 131,693
- Other: Target = 3,000 | Actual = 9,663
- Sugar: Target = 1,500 | Actual = 427
  
**Key Insights:**
The analysis shows that Chocolate significantly exceeds expectations, indicating very strong performance. The “Other” category also performs above target, reflecting positive results, while Sugar underperforms and requires strategic attention to improve its performance.


## Dataset: [US Candy Distributor](https://mavenanalytics.io/data-playground/us-candy-distributor)


</details>

![image alt](https://github.com/Okello-Solomon/tableau_dashboards/blob/ee15fd6ae6ebed0b43394d32e287d654ef9ff588/Candy%20Performance%20Dashboard%201.png)

![image alt](https://github.com/Okello-Solomon/tableau_dashboards/blob/105cfce5b12a656e2a2b9c5168e8343bd1cb3dd1/Candy%20Performance%20Dashboard%202.png)

# 2. Netflix Content Analytics Dashboard

## Project Overview

This dashboard provides a deep-dive analysis of the Netflix content library, tracking key metrics, release trends, and geographical distribution.  
The goal is to visually represent the evolution and composition of content on the world's leading streaming platform, offering insights into content strategy and library demographics.

<details>
<summary><strong> View Project Details</strong></summary>

### Key Insights & Metrics
The dashboard immediately highlights the scale of the content library and its structure:

- **Total Programs:** 8,807  
- **Total Titles:** 8,804  
- **Movie Count:** 6,131  
- **TV Show Count:** 2,676  
- **Overall Dominance:** Movies make up the majority of the content  
- **Average Duration (Movies):** 124 min

### Detailed Visualizations and Analysis
The dashboard segments the content data to deliver actionable insights:

#### Content Volume and Growth (Total Movies and TV Shows by Year Added)
- The platform saw explosive growth in content added starting around 2014-2015  
- The largest volume of both Movies and TV Shows was added in the 2019-2020 timeframe  
- A significant drop in added content is observed in 2021

#### Top 10 Rating Distribution
- The most common rating on the platform is TV-MA (2,931 titles), followed by TV-14 (1,930 titles), and R (788 titles)  
- This indicates a high proportion of content aimed at mature audiences

#### Global Content Production (Total Movies and TV Shows by Country)
- The visualization highlights the primary geographical sources of the content, with a clear focus on certain regions

### Tools Used
- **Visualization Platform:** Tableau

### Data Source
- [Netflix Titles Data Set on Kaggle](https://www.kaggle.com/datasets/shailajakodag1/netflix-titlescsv)

</details>



![image alt](https://github.com/Okello-Solomon/tableau_dashboard/blob/b638811e1f00971600757371807d785c8dd36894/netflix_analysis_dashboard.png)



# 3. HR Analytics Insights Dashboard: Driving Strategic Workforce Decisions

## Project Overview

This interactive dashboard was developed to provide a comprehensive, real-time view of key Human Resource metrics, enabling data-driven decision-making for workforce planning, talent acquisition, and employee retention strategies.

<details>
<summary><strong> View Project Details</strong></summary>

### Project Goal
The dashboard consolidates and tracks critical HR KPIs to provide actionable insights for organizational strategy and workforce planning.

### Key Performance Indicators (KPIs)
The dashboard consolidates and tracks critical HR KPIs:

- **Total Employees:** 311  
- **Active Employees:** 207  
- **Attrition Count:** 104  
- **Attrition Rate:** 33.44%  
- **Average Salary:** $69,021  
- **Maximum Salary:** $250,000  
- **Minimum Salary:** $45,046  

### Detailed Visualizations and Analysis
The dashboard segments the workforce data to deliver actionable insights on organizational health:

#### Employee Demographics
- **Marital Status:** Provides a clear breakdown, showing 137 Single employees and 124 Married employees.  
- **Gender Distribution:** Visualizes the gender split, indicating 43.41% Male (135) and 56.53% Female (176).

#### Recruitment Analysis
- **Employee Count by Recruitment Source:** Identifies the most effective talent channels, with Indeed (87) and LinkedIn (76) leading the recruitment source count.  
- **Performance Distribution by Recruitment Source:** Allows analysis of the performance of employees based on their origin.

#### Workforce Stability (Attrition)
- **Employment Status Breakdown:** Details the separation reasons, showing 88 Voluntarily Terminated employees and 16 Terminated for Cause.

#### Geographical Distribution
- **Geographical Distribution of Employees:** Maps the employee concentration across the United States.

### Tools Used
- **Visualization Platform:** Tableau

### Data Source
- [Human Resources Data Set on Kaggle](https://www.kaggle.com/datasets/rhuebner/human-resources-data-set)

</details>



![image alt](https://github.com/Okello-Solomon/tableau_dashboard/blob/ca5e7e7e57794b4e4c7a3a2dca457a573fdb0905/HR%20Analytics%20Dashboard.png)



# 4. Airbnb NYC Market Analysis Dashboard


## Project Overview

This interactive Tableau dashboard delivers a real-time, in-depth analysis of the New York City Airbnb marketplace. Analyzing over 48,895 active listings across all five boroughs, the project provides a comprehensive view of urban hospitality trends, host professionalization, availability patterns, and pricing dynamics.

The primary objective is to translate complex market data into clear, actionable insights that help stakeholders understand regional supply-and-demand dynamics within the short-term rental ecosystem.

<details>
<summary><strong> View Project Details</strong></summary>

### Key Insights & Metrics

The dashboard provides an immediate snapshot of market scale and performance benchmarks:

Total Market Volume: 48,895 unique Airbnb listings across New York City


### Inventory Composition:

- **Entire Home/Apt:** 51.97% (dominant category)

- **Private Room:** 45.66%, reflecting a strong secondary market presence

### Detailed Visualizations and Analysis
A KPI header allows users to toggle between Average Host Listings, Average Availability (365), and other selected averages, revealing how performance trends vary across boroughs in real time.

**Description:**
Displays real-time average metrics based on the current dashboard selection.

**Functional Logic:**
KPIs dynamically update to provide a high-level performance summary. Users can switch between selected averages to gain a consolidated view of pricing, availability, and host activity across neighbourhood groups.

### Market Share by Room Type (Donut Chart)

**Description:**
A proportional breakdown of Airbnb accommodation categories, including Entire Home/Apt, Private Room, and Shared Room.

**Strategic Insight:**
This visualization highlights dominant accommodation types, offering insights into host strategies, market structure, and the diversity of stay options within the selected boroughs.

### Availability 365 Analysis (Packed Bubble Chart)

**Description:**
Measures listing availability across a 365-day calendar year, with bubble size representing total availability.

**Analytical Logic:**

Larger bubbles indicate listings that are frequently open for booking, suggesting higher vacancy or lower occupancy

Smaller bubbles often reflect high-demand areas with consistently booked properties

This view serves as a proxy for demand intensity and occupancy behavior across neighbourhood groups.

### Market Dynamics by Neighbourhood (Stacked Bar Chart)

**Description:**
Displays the distribution of Airbnb activity across neighbourhood groups, segmented by room type.

**Interactive Feature:**
Includes a "Selected Measures" parameter that allows users to dynamically switch the Y-axis between:

Number of Listings

Number of Reviews

Host Listings Count

Average Price

**Analytical Purpose:**
Enables exploration of how inventory volume, demand intensity, and pricing power vary across boroughs and room types.

### Host & Regional Dominance (Top 10 Leaderboard)

**Description:**
Ranks the Top 10 Host Names or Neighbourhood Groups by total number of listings.

**Professional Insight:**
A "Chosen Dimension" parameter dynamically updates the leaderboard to reveal:

**Dominant professional hosts**

Boroughs with the highest concentration of Airbnb inventory

This analysis highlights market concentration and professionalization trends within the NYC Airbnb ecosystem.

### Technical Features

**Global Interactive Slicer:**
Neighbourhood Group filter (Bronx, Brooklyn, Manhattan, Queens, Staten Island) applied consistently across all visuals

**Parameter-Driven Exploration:**
"Chosen Dimension" and “Averages” parameters allow users to pivot analytical perspectives without leaving the dashboard

**Visualization Platform:**
Built entirely in Tableau, leveraging donut charts, packed bubbles, stacked bar charts, calculated fields, and advanced dashboard actions

### Data Source

- [NYC Airbnb Open Data - Kaggle / Inside Airbnb](https://www.kaggle.com/datasets/arianazmoudeh/airbnbopendata)
  
</details>


![image alt](https://github.com/Okello-Solomon/tableau_dashboards/blob/8b019a46677c2723d70885c9d22632a2b78dc5db/Airbnb%20NYC%20Market%20Analytics%20Dashboard.PNG)
