# 🏡 Real Estate Sales Dashboard

![Excel Dashboard](https://img.shields.io/badge/Excel-Dashboard-brightgreen) ![Version](https://img.shields.io/badge/Version-1.0-blue) 

Welcome to the **Real Estate Sales Dashboard** project! This interactive Excel dashboard provides a comprehensive analysis of real estate sales data from 2006 to 2022. The dashboard is designed to help stakeholders understand market trends, property performance, and the impact of special circumstances on sales.

---

## 📊 Project Overview

This dashboard visualizes real estate sales data with **seven interactive charts**, key performance indicators (KPIs), and detailed breakdowns. It allows users to explore sales trends, property types, town performance, and more through slicers and drill-down features.

### Key Features
- **Interactive Slicers**: Filter by List Year, Town, Property Type.
- **Seven Insightful Charts**: From sales ratio trends to non-use code impacts, the dashboard covers a wide range of analyses.
- **KPIs**: Quick insights into average sales ratio, total sale amount, number of properties sold, and top Twon based on average sales ratio.
- **Visually Appealing Design**: Uses a teal, coral, navy blue, and soft yellow color scheme for a professional look.
- **Drill-Down Capability**: Click on chart elements (e.g., a pie chart slice) to filter related data.

---

## 📈 Dashboard Components

### Layout
- **Top Section**: Title ("Property Trends") and slicers for filtering.
- **Middle Section**: Four charts in a 2x2 grid for trends and distributions.
- **Bottom Section**: Four additional charts in a 2x2 grid for deeper insights.


### Color Scheme
- **Background**: Light gray (#F5F5F5)
- **Charts/KPIs**: Teal (#26A69A), coral (#FF6F61), navy blue (#1A237E), soft yellow (#FFCA28)
- **Text**: Dark gray (#333333) with white text on colored backgrounds

### Components Breakdown
1. **KPIs**  
   - 🟢 **Average Sales Ratio**
   - 🟠 **Total Sale Amount**  
   - 🔵 **Number of Properties Sold**
   - 🟡 **Top Town**

2. **Middle Section Charts**  
   - 📉 **Sales Ratio Trend Over Time (Line Chart)**: Tracks sales ratio changes from 2006 to 2022.  
   - 📊 **Total Sale Amount by Year (Column Chart)**: Compares sale amounts between 2006 and 2022.  
   - 🥧 **Property Type Distribution (Pie Chart)**: Shows contribution of each property type based on sum of sale amount.
   - 📍 **Assessed Value vs. Sale Amount (Scatter Plot)**: Reveals weak correlation between assessed and sale values 

3. **Bottom Section Charts**  
   - 🏆 **Top Towns by Average Sale ratio**: Shows Top 10 towns based on average sales ratio.  
   - 🏘️ **Residential Type Breakdown**: A funnel chart showing contribution of each residential type.  
   - 🔍 **Non-Use Code Impact on Sale Ratio**:Shows impact of each non-use code using an area chart.

---

## 🔍 Key Insights

- **Market Variability**: Sales ratios vary widely.
- **Yearly Trends**: 2020 had the highest sales and 2010 had the lowest sales.
- **Property Preference**: Single Family homes dominate, reflecting buyer preferences.
- **Town Performance**: Salisbury leads in sale amounts.

---

## 🛠️ How to Use

1. **Download the Excel File**: Clone this repository or download the `.xlsx` file.
2. **Open in Excel**: Ensure you have Microsoft Excel installed.
3. **Interact with Slicers**: Use the slicers at the top to filter by year, town, property type, etc.
4. **Explore Charts**: Click on chart elements (e.g., a pie chart slice) to drill down into specific data.


---

## 📋 How to Recreate the Dashboard

1. **Prepare the Data**  
   - Copy the dataset into Excel and convert it into a Table (Insert > Table).  
   - Ensure the "Date Recorded" column is in MM/DD/YYYY format.

2. **Create Pivot Tables and Charts**  
   - Use Insert > Pivot Table to create pivot tables for each chart and KPI.  
   - Follow the chart descriptions in the "Dashboard Components" section to set up fields and chart types.

3. **Add Slicers**  
   - Insert slicers for List Year, Town, Property Type.  
   - Connect them to all pivot tables (Slicer > Report Connections).

4. **Design the Layout**  
   - Arrange charts, tables, and slicers as described.  
   - Apply the color scheme using Format Shape.

5. **Add Interactivity**  
   - Enable drill-down by clicking on chart elements.  
   - Apply conditional formatting to tables (e.g., highlight sales ratios >1 in green).

---

## 📂 Repository Structure

- `Real_Estate_Sales_Dashboard.xlsx`: The Excel file containing the dashboard.
- `README.md`: This file.
- `data/`: Folder containing the raw dataset (if applicable).
- `screenshots/`: Folder with dashboard screenshots (add your own).

---

---

## 📧 Contact

For questions or feedback, reach out via [mansityagi472@gmail.com](mailto:mansityagi472@gmail.com) or open an issue on GitHub.

---

**Happy Analyzing!** 🚀
