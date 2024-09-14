# **Power BI Interactive Dashboard for Business Decision-Making**

## **Project Overview**
This project showcases my proficiency in Power BI by developing an interactive dashboard that helps business stakeholders make data-driven decisions for business growth. The dashboard is built using data from a company’s ERP system, with some dummy data for confidentiality. 

The dashboard was designed to provide insights into key business areas, including **Profit Summary**, **Customer Insights**, and **Product and Price Insights**. It incorporates advanced data modeling techniques, custom measures using DAX, and visually compelling charts to enhance decision-making.

---

## **Data Source**
- **Source**: The data used in this dashboard is sourced from a **MySQL database**, which contains various tables related to the company's ERP system. 
- **Data Sensitivity**: Some data in the project has been anonymized or replaced with dummy data to maintain confidentiality.
- **Data Preprocessing**: Before importing data into Power BI, extensive data cleaning, transformation, and modeling were performed to ensure accuracy and consistency for business analysis.

---

## **Purpose of the Dashboard**
The dashboard is designed to support executives, product managers, and analysts in making informed business decisions by providing insights into:
1. **Profitability**
2. **Customer behavior and segmentation**
3. **Product pricing and performance trends**

### **Business Objectives**:
- To monitor revenue and profitability across various business segments.
- To analyze customer purchase behavior and identify opportunities for customer growth and retention.
- To assess product performance and optimize pricing strategies for higher profitability.

---

## **Key Features and Insights**

### 1. **Profit Summary**:
   - **Metrics**: Total Revenue, Total Profit, Profit Margin (%), Average Revenue per Order.
   - **Advanced Calculations**: Custom DAX measures were created for metrics like profit margin, average order value (AOV), and monthly revenue growth rate, enhancing financial insight.
   - **Dynamic Filtering**: Users can filter the data by time period (month, quarter), product category, and region to track profitability trends over time.

### 2. **Customer Insights**:
   - **Metrics**: Total Customers, Repeat Customer Rate, Churn Rate, Customer Lifetime Value (CLV), Lost Customers.
   - **Advanced Calculations**: DAX measures like average customer lifetime, churn rate, and purchase frequency provide deeper insight into customer retention and acquisition trends.
   - **Interactive Drill-downs**: Analyze customer data by segments such as new vs. returning customers, or by regions to understand demographic behavior.
   - **Focus on Retention**: CLV and churn rate are used to track long-term customer relationships, helping to target retention strategies.

### 3. **Product and Price Insights**:
   - **Metrics**: Best-Selling Products, Average Product Price, Top Products by Revenue and Profit Margin.
   - **Additional Calculations**: DAX measures like average order fulfillment time and revenue per customer help management make product and pricing decisions based on sales and operational efficiency.
   - **Product Performance**: Identifies high-performing and low-performing products to help management optimize inventory and marketing efforts.

---

## **Technical Details**

### **Power BI Features Used**:
1. **Data Modeling**:
   - Created calculated columns and tables in Power BI for better data representation and transformation.
   - Relationships between tables were carefully structured to ensure seamless analysis across multiple datasets.

2. **DAX (Data Analysis Expressions)**:
   - **Custom Measures**: Advanced DAX was used for key calculations, such as:
     - **Profit Margin (%)**: `Profit Margin = (Total Profit / Total Revenue) * 100`
     - **Average Revenue Per Order**: `Total Revenue / Number of Orders`
     - **Monthly Revenue Growth**: `([Current Month's Revenue] - [Previous Month's Revenue]) / [Previous Month's Revenue]`
     - **Average Order Value (AOV)**: Calculation of revenue per order.
     - **Churn Rate**: Measures customer retention and loss.
     - **Average Customer Lifetime**: Calculated to understand how long customers remain active.
     - **Purchase Frequency**: Number of purchases divided by the number of customers.
     - **Day of Week Analysis**: To analyze sales trends by the day of the week.
     - **Average Order Fulfillment Time**: Measures efficiency in processing customer orders.
   - Created dynamic measures to allow users to slice and filter data in real-time.

3. **Interactive Visuals**:
   - **Decomposition Tree**: Enables users to drill down into profitability by product, region, and customer segment, supported by AI insights.
   - **Dynamic Cards and KPIs**: Key metrics like revenue, profit margin, and customer metrics are displayed as dynamic cards that update based on user filters.

4. **Reset Button**:
   - Implemented a **Reset Icon** that allows users to clear filters and restore the dashboard to its default state with a single click.

---

## **Usage Instructions**

### **How to Use the Dashboard**:
1. **Navigate Through the Pages**: The dashboard is divided into three primary sections:
   - **Profit Summary**: Get a high-level view of revenue, profit, and margin metrics.
   - **Customer Insights**: Analyze customer behavior, lifetime value, and retention rates.
   - **Product & Price Insights**: Explore product performance and pricing strategies.
   
2. **Filters**: Use filters to slice the data by different time periods (monthly, quarterly), regions, and product categories.
   - Examples of filters include Date, Customer Segment, Product Category, and Price Range.

3. **Reset Filters**: Use the reset button to clear all filters and return the dashboard to its default state.

---

## **Project Challenges and Solutions**

1. **Data Confidentiality**:
   - Addressed by anonymizing and using dummy data to maintain the integrity and confidentiality of sensitive company information.

2. **Complex Data Relationships**:
   - Carefully structured relationships between different tables in Power BI to ensure seamless cross-filtering and accurate aggregation.

3. **Dynamic Calculations**:
   - Leveraged advanced DAX functions to create real-time dynamic calculations, allowing end-users to interact with and analyze the data effectively.

---

## **Skills Demonstrated**

- **Data Modeling**: Developed a robust data model with accurate relationships to support advanced analysis.
- **Power BI Proficiency**: Expert-level use of Power BI's capabilities, including visualizations, DAX, and data modeling.
- **Business Analytics**: Provided meaningful insights to support critical business decision-making.
- **Interactivity**: Created an interactive, user-focused dashboard that allows for dynamic analysis and filtering.
- **Problem-Solving**: Overcame challenges related to data integration and confidentiality with smart solutions.

---

## **Contact Information**
Feel free to explore the dashboard and reach out if you have any questions or would like to discuss further!

- **Email**: [sharifashik591@gmail.com](mailto:sharifashik591@gmail.com)
- **LinkedIn**: [Sharif Ashik](https://www.linkedin.com/in/sharif-ashik/)

---

**Thank you for taking the time to explore this project!**
