

**Global CO₂ Emissions Dashboard**
📊 Project Overview

This Tableau project visualizes global carbon dioxide (CO₂) emissions trends from 1960 to 2023 using historical data from various countries. The dashboard provides insights into emission levels, top contributors, year-over-year changes, and global patterns, supporting environmental research and policy analysis.

📂 Dataset

Dataset Name: Global CO₂ Emissions Dataset

Rows: 13,953

Columns: 4

Time Period: 1960–2023

**Column Description**

1.country_code – ISO 3-letter country code

2.country_name – Full country name

3.year – Year of emission data

4.value – CO₂ emissions in kilotonnes (kt)

🧹 Data Cleaning & Preprocessing

1.Renamed value to CO2_Emissions_kt for clarity.

2.Ensured year is treated as a dimension for trend analysis.

3.Removed records where emissions data was missing (NULL).

4.Created calculated fields:

  -CO2_Emissions_mt (megatonnes) = CO2_Emissions_kt / 1000

  -Year-on-Year % Change = (Current Year - Previous Year) / Previous Year * 100

📈 Visual Analysis

1.Bar Chart – Top 10 CO₂ Emitting Countries (Latest Year)

2.Scatter Plot – Global CO₂ Emissions Trend (1960–2023)

3.Map Visualization – CO₂ Emissions by Country (Latest Year)

4.Area Chart – Stacked Emissions by Continent/Region

🖥 Interactive Dashboards

1.Filters & Slicers:

  -Year range slider

  -Dropdown for country_name selection

2.Highlight Table – Emissions Heatmap by Country and Year

3.Interactive Scatter Plot – Emissions vs. Year with trend insights

🚀 Key Insights

1.Identifies top emitters and their contribution over time.

2.Highlights global trends and regional variations.

3.Provides a dynamic and interactive dashboard for deeper exploration.

📌 How to Use

1.Open the Tableau workbook.

2.Navigate through the dashboard tabs:

     -Overview – Global trend visualization

     -Country Analysis – Top emitters and year-over-year changes

     -Map View – Geographic emission patterns

3.Use filters to explore specific countries and time ranges.

