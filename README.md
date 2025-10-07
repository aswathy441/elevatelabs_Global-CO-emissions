Global CO₂ Emissions Tracker by Sector
Project Overview

This project is an interactive dashboard to analyze global CO₂ emissions across countries and sectors. It provides insights into total emissions, per-capita trends, and top polluters, enabling policymakers, researchers, and the public to make data-driven decisions for climate action.

Features

Slicers: Filter by country and year to analyze trends interactively.

World Map (Choropleth): Displays CO₂ emissions per capita by country.

Treemap: Shows share of global CO₂ emissions by country.

Pie Chart: Visualizes CO₂ contributions by country.

KPI Cards: Display total CO₂ emissions, coal CO₂ emissions, and total emissions.

Dataset

Source: Our World in Data (OWID)

Data Details: Multi-year CO₂ emissions data by country and sector.

Tools Used

Data Cleaning & Preparation: Python (Pandas, NumPy)

Dashboard & Visualization: Power BI

Steps to Build

Data Collection: Download dataset from OWID.

Data Cleaning:

Handle missing values (median for numeric, mode for categorical).

Drop unnecessary columns with too many missing values.

Derived Metrics:

Calculate per-capita CO₂ and per-GDP CO₂.

Convert sector columns to long format with sector and co2_emissions.

Dashboard in Power BI:

Add slicers for Country & Year.

Create World Map, Treemap, Pie Chart, and KPI Cards.

Ensure interactive filtering between visuals.

Testing: Validate calculations and interactivity.

Key Insights

Identify top CO₂ emitting countries.

Visualize sector-wise contribution to global CO₂ emissions.

Observe CO₂ trends over time for countries and sectors.

How to Use

Open the Power BI dashboard file.

Use slicers to select a year or country.

Explore visuals to analyze CO₂ emissions per capita, sector-wise, and globally.

Output

Interactive Power BI dashboard.

PDF report summarizing methodology, insights, and visuals.
