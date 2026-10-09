# 🎮 Gaming Industry Analytics Dashboard

An interactive data analytics portfolio project exploring video game sales across genres, gaming platforms, release years, publishers, and regions using **Power BI, DAX, and an interactive HTML dashboard**.

> **Data Disclaimer:** This project uses a synthetic dataset created for portfolio practice. Game names, publishers, and sales values are fictional and do not represent actual gaming industry statistics.

## 📊 Project Overview

The objective of this project is to explore sales patterns in a gaming dataset and present the findings through interactive visualizations and KPI metrics.

### Key Features

- **KPI Cards:** Total Global Sales, Game-Platform Records, Average Global Sales, and Distinct Platforms.
- **Genre Analysis:** Compare global sales across game genres.
- **Platform Analysis:** Examine sales across gaming platforms.
- **Yearly Trends:** Explore global sales by release year.
- **Regional Analysis:** Compare North America, Europe, Japan, and other regions.
- **Interactive Filters:** Filter results by release year, genre, platform, and publisher.
- **Top 10 Records:** Identify the highest-selling game-platform records in the selected data.

## 🛠️ Tools & Technologies

- Microsoft Power BI Desktop
- DAX (Data Analysis Expressions)
- CSV dataset
- HTML, CSS, and JavaScript
- Plotly.js for interactive charts

## 📁 Project Structure

```text
gaming-industry-analytics/
├── Dashboard/
│   └── Gaming_Industry_Analytics_Full_Dashboard.html
├── Dataset/
│   └── Gaming_Industry_Synthetic_Dataset.csv
├── PowerBI/
│   ├── Gaming_Industry_Analytics.pbix
│   ├── Gaming_Analytics_Professional_Theme.json
│   └── All_DAX_Measures.txt
├── Documentation/
│   └── Full_PowerBI_Dashboard_Build_Guide.txt
└── README.md
```

*The exact files in your repository may vary depending on which files were uploaded.*

## 🚀 How to Run the Project

### Interactive HTML Dashboard

1. Open the `Dashboard` folder.
2. Open `Gaming_Industry_Analytics_Full_Dashboard.html` in Google Chrome or Microsoft Edge.
3. Use the filters to explore the charts and KPI metrics.

An internet connection is required to load Plotly.js from its CDN.

### Power BI Dashboard

1. Open `PowerBI/Gaming_Industry_Analytics.pbix` in Power BI Desktop.
2. Review the existing report and data model.
3. Refer to `All_DAX_Measures.txt` and the dashboard build guide when developing the native Power BI report.

**Note:** The included PBIX file is the original supplied file and has not been programmatically modified as part of this package.

## 📈 Dataset Information

The dataset contains **1,000 synthetic game-platform records** and 11 columns.

| Column | Description |
|---|---|
| `Game_ID` | Unique record identifier |
| `Game_Name` | Fictional game name |
| `Platform` | Gaming platform |
| `Genre` | Game genre |
| `Publisher` | Fictional publisher |
| `Release_Year` | Release year |
| `North_America_Sales_M` | North American sales, in millions |
| `Europe_Sales_M` | European sales, in millions |
| `Japan_Sales_M` | Japanese sales, in millions |
| `Other_Regions_Sales_M` | Sales in other regions, in millions |
| `Global_Sales_M` | Total global sales, in millions |

## 🧮 Data Analysis & DAX

The project includes measures for:

- Total Global Sales
- Total Game Records
- Average Global Sales
- Platform Sales
- Regional Sales
- Distinct Platforms

These measures support KPI reporting, comparisons, and interactive analysis.

## 🎯 Skills Demonstrated

- Data validation and data quality checks
- Data modeling and DAX measures
- KPI design and dashboard development
- Data visualization and comparison
- Interactive filtering
- Data storytelling
- Organizing a data analytics portfolio project

## ⚠️ Limitations

- The dataset is synthetic and must not be used to draw conclusions about real market performance.
- The HTML dashboard loads Plotly.js from an external CDN.
- The native Power BI report may require additional development to match all the features described in the project documentation.

## 👤 Author

**Syed Muzzamil Hussain**

Aspiring Data Analyst
