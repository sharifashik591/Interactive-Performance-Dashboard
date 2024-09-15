# Power BI Interactive Dashboard for Business Decision-Making

## Project Overview
This project demonstrates my expertise in Power BI by building an interactive dashboard for business stakeholders to make data-driven decisions aimed at growth. Data comes from a company’s ERP system, Google Sheets, and Excel, with some dummy data for confidentiality. The dashboard provides insights into key business areas: **Profit Summary**, **Customer Insights**, and **Product & Price Insights**. It employs advanced data modeling, custom DAX measures, and dynamic visuals to support decision-making.

## Data Source and Automation
- **Source**: Data is sourced from various systems, including the company’s ERP system, Google Sheets, and Excel files.
- **Data Collection Process**: I developed Python scripts to automatically scrape, process, and update data into a database on a daily basis. A scheduler is used to trigger the scripts every day to ensure that the data remains up-to-date. This automation streamlines the process and feeds fresh data into the Power BI dashboard.
- **Data Sensitivity**: Some data in the project has been anonymized or replaced with dummy data to maintain confidentiality.
- **Data Preprocessing**: The Python scripts perform data cleaning, transformation, and processing to ensure accuracy and consistency for business analysis before being ingested by Power BI.

## Purpose of the Dashboard
This dashboard supports executives, product managers, and analysts in:
- **Monitoring profitability**
- **Analyzing customer behavior** to enhance retention
- **Optimizing product performance and pricing** strategies

## Business Objectives
- Track revenue and profitability across segments.
- Identify opportunities for customer growth and retention.
- Assess product performance for higher profitability.

## Key Features and Insights

### 1. Profit Summary
- **Metrics**: Total Revenue, Profit, Profit Margin, Avg. Revenue per Order.
- **Advanced Calculations**: DAX measures for Profit Margin (%), AOV, and Monthly Revenue Growth.
- **Dynamic Filtering**: Time period, product category, and region.

### 2. Customer Insights
- **Metrics**: Total Customers, Repeat Customer Rate, Churn Rate, CLV, Lost Customers.
- **Advanced Calculations**: Average Customer Lifetime, Churn Rate, Purchase Frequency.
- **Drill-Downs**: Segment analysis, regional behavior, retention strategies.

### 3. Product & Price Insights
- **Metrics**: Best-Selling Products, Avg. Product Price, Revenue, Profit Margin.
- **Additional Calculations**: Avg. Order Fulfillment Time, Avg. Revenue per Customer.
- **Performance Analysis**: Identifying high- and low-performing products.

## Technical Details

### Power BI Features Used:
1. **Data Modeling**:
   - Calculated columns and tables in Power BI.
   - Accurate relationships across datasets.

2. **DAX Measures**:
   - **Profit Margin** = `(Total Profit / Total Revenue) * 100`
   - **AOV** = `Total Revenue / Number of Orders`
   - **Churn Rate**: Measures retention and loss.
   - **Customer Lifetime**: Tracks how long customers remain active.
   - **Monthly Revenue Growth**: `([Current Month's Revenue] - [Previous Month's Revenue]) / [Previous Month's Revenue]`

3. **Interactive Visuals**:
   - **Decomposition Tree**: Drill down by product, region, and customer segment.
   - **Dynamic Cards and KPIs**: Real-time metric updates based on filters.

4. **Reset Button**: Clears filters and restores default dashboard state.

## Python Automation Process
- **Data Collection**: Automated Python scripts scrape data from multiple sources like Google Sheets, Excel files, and the ERP system.
- **Data Processing**: The scripts clean, process, and format the data before updating it in the database used by Power BI.
- **Daily Automation**: A scheduler runs the Python scripts daily, ensuring the dashboard is always up-to-date with the latest data.

## Usage Instructions
### How to Use the Dashboard:
1. **Navigation**:
   - **Profit Summary**: Overview of revenue, profit, and margins.
   - **Customer Insights**: Customer behavior and retention.
   - **Product & Price Insights**: Product performance and pricing strategies.

2. **Filters**: Slice data by Date, Customer Segment, Product Category, Price Range.
   - **Reset Filters**: Use the reset button to clear selections.

## Project Challenges and Solutions

1. **Data Confidentiality**: Resolved through data anonymization and dummy values.
2. **Complex Data Relationships**: Properly structured for seamless analysis.
3. **Dynamic Calculations**: Used advanced DAX for real-time insights.
4. **Automation**: Automated daily data scraping and processing with Python scripts.

## Skills Demonstrated
- **Data Modeling**: Structured data relationships to enhance analysis.
- **Power BI Proficiency**: Expert use of visualizations, DAX, and data modeling.
- **Python Automation**: Developed and automated scripts to collect, process, and update data daily.
- **Business Analytics**: Delivered actionable insights for decision-making.
- **Interactivity**: Designed a user-friendly, dynamic dashboard.
- **Problem-Solving**: Addressed data confidentiality and integration challenges effectively.

## Project Flowchart

```plaintext
[Data Sources] 
   ↓
(ERP System, Google Sheets, Excel)
   ↓
[Python Scripts for Data Collection] 
   ↓
(Daily Automation for Scraping and Processing Data)
   ↓
[Data Cleaning & Transformation]
   ↓
(Ensure Data Quality)
   ↓
[Data Loading into MySQL Database]
   ↓
(Processed Data Stored in MySQL)
   ↓
[Connect Power BI to MySQL Database]
   ↓
(Import Data into Power BI)
   ↓
[Data Modeling & DAX Calculations]
   ↓
(Create Relationships, AOV, Profit Margin, Churn Rate, etc.)
   ↓
[Interactive Dashboard Design]
   ↓
(Pages: Profit Summary, Customer Insights, Product & Price Insights)
   ↓
[Publish Dashboard & Automation]
   ↓
(Daily Updates Using Python Scripts & Scheduled Refreshes)
```


## Contact Information
Feel free to reach out with questions!

- **Email**: [sharifashik591@gmail.com](mailto:sharifashik591@gmail.com)
- **LinkedIn**: [Sharif Ashik](https://www.linkedin.com/in/sharif-ashik)



![Green Minimalist Happy Birthday Photo Collage](https://github.com/user-attachments/assets/4b93b737-6fc6-46b7-9bfb-e56151896c5e)
