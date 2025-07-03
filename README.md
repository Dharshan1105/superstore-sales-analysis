# superstore-sales-analysis
Interactive EDA of Global Superstore dataset using Python and Plotly
# Superstore Sales Analysis

A comprehensive data analysis project that explores and visualizes sales data from a global superstore using interactive Plotly charts to derive actionable insights.


## Project Structure

Superstore-Analysis/
├── data/
│ └── Global_Superstore2.csv
├── notebooks/
│ └── Superstore_Analysis.ipynb
├── outputs/
│ └── Updated_File.csv
└── README.md

## Objective

The goal of this project is to:
- Clean and preprocess the superstore sales dataset.
- Extract meaningful business insights regarding sales, profits, delays, and customer segments.
- Identify top-performing products and regions.
- Discover trends based on time-related features such as month and year.
- Provide dynamic and interactive data visualizations using Plotly.

---

## Dataset

- **Source**: `Global_Superstore2.csv`
- **Description**: Contains transaction-level data including sales, profit, shipping details, customer information, and product categories across various regions.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Plotly (for visualizations)
- Jupyter Notebook

---

## Features

- **Data Cleaning**:
  - Dropped irrelevant and missing fields (e.g., Postal Code)
  - Removed duplicate entries
- **Feature Engineering**:
  - Converted date columns to datetime format
  - Calculated shipping delays
  - Extracted month and year from order dates
- **Data Aggregation**:
  - Top 5 cities by sales
  - Top 5 products by profit
  - Segment-wise and region-wise summaries
- **Interactive Visualizations**:
  - Sales and profit analysis using Plotly bar and pie charts
  - Shipping delay trends across regions
  - Yearly and monthly trends using pivot tables and dynamic plots
- **Exported Output**:
  - Cleaned dataset saved as `Updated_File.csv` in the outputs folder

---

## Insights

- Cities such as New York and Los Angeles lead in overall sales.
- High-profit products include those in the furniture and office supplies categories.
- The consumer segment generates the highest sales among all segments.
- Shipping delays differ across regions, pointing to potential logistical optimizations.

---

