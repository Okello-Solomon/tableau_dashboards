# 1. Netflix Content Analytics Dashboard

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



# 2. HR Analytics Insights Dashboard: Driving Strategic Workforce Decisions

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



# 3. Airbnb NYC Market Analysis Dashboard


## Project Overview

This interactive Tableau dashboard delivers a real-time, in-depth analysis of the New York City Airbnb marketplace. Analyzing over 48,895 active listings across all five boroughs, the project provides a comprehensive view of urban hospitality trends, host professionalization, availability patterns, and pricing dynamics.

The primary objective is to translate complex market data into clear, actionable insights that help stakeholders understand regional supply-and-demand dynamics within the short-term rental ecosystem.

<details>
<summary><strong> View Project Details</strong></summary>

### Key Insights & Metrics

The dashboard provides an immediate snapshot of market scale and performance benchmarks:

Total Market Volume: 48,895 unique Airbnb listings across New York City


###Inventory Composition:

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

###Availability 365 Analysis (Packed Bubble Chart)

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

NYC Airbnb Open Data - Kaggle / Inside Airbnb
**Source:** [Contains detailed listing-level records for the New York City region](https://www.kaggle.com/datasets/arianazmoudeh/airbnbopendata)

</details>


![image alt](https://github.com/Okello-Solomon/tableau_dashboards/blob/8b019a46677c2723d70885c9d22632a2b78dc5db/Airbnb%20NYC%20Market%20Analytics%20Dashboard.PNG)
