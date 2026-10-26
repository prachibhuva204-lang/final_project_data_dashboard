# Final Project – Data Intelligence Dashboard

# Project Overview
This project focuses on analyzing customer transaction data using Microsoft Excel. The main objective is to organize raw data, perform data analysis, 
create PivotTables and charts, and build an interactive-looking dashboard to summarize important business insights.

# Objectives
- Organize and format the raw transaction dataset.
- Calculate additional information using Excel formulas.
- Filter data based on Region and Customer Segment.
- Apply Conditional Formatting to highlight transaction values.
- Analyze revenue and sales using PivotTables and charts.
- Present key performance indicators (KPIs) in a dashboard.

# Dataset Description
The dataset contains customer transaction information, including:

- Transaction_ID
- Date
- Customer_ID
- Customer_Name
- Product_ID
- Product_Name
- Category
- Quantity
- Unit_Price
- Payment_Method
- Region
- Customer_Segment
- Customer_Since
- Total_Amount

Additional calculated columns include Current_Date, Current_Time, Customer_Age_Years, and Month_End.

# Tools Used
- Microsoft Excel
- Excel Tables
- Excel Formulas
- FILTER Function
- Conditional Formatting
- PivotTables
- PivotCharts
- Dashboard and KPI formatting

# Data Preparation
The original dataset was organized in the **Raw Data** worksheet and formatted as an Excel Table.

The following formulas were used to calculate additional information:

- Current Date: `=TODAY()`
- Current Time: `=NOW()`
- Customer Age in Years: `=DATEDIF(M2,TODAY(),"Y")`
- Month End: `=EOMONTH(B2,0)`

Conditional Formatting with Data Bars was applied to the Total_Amount column to make transaction values easier to compare.

# Filtered Data
A separate worksheet named **Filtered Data** was created to display transactions where:

- Region = West
- Customer_Segment = Premium

The Excel FILTER function was used to extract matching records from the Raw Data worksheet.

# Data Analysis
PivotTables and charts were created to analyze:

1. Region-wise Revenue
2. Category-wise Revenue
3. Product-wise Sales
4. Payment Method Analysis

These analyses help summarize transaction performance across regions, product categories, products, and payment methods.

# Dashboard and KPIs
A separate **Dashboard** worksheet was created to present the charts and key performance indicators.

The dashboard includes the following KPIs:

- Total Revenue
- Total Transactions
- Total Quantity Sold
- Average Order Value

These KPIs provide a quick summary of overall transaction performance.

# Project Structure
The Excel workbook contains the following worksheets:

- Raw Data
- Filtered Data
- Region-wise Revenue analysis
- Category-wise Revenue analysis
- Product-wise Sales analysis
- Payment Method Analysis
- Dashboard

# Conclusion
This project demonstrates how Microsoft Excel can be used to prepare, analyze, and visualize customer transaction data. The PivotTables, charts, formulas, 
conditional formatting, and dashboard help present business information in a clear and organized way.

<img width="1853" height="598" alt="Screenshot 2026-10-26 184821" src="https://github.com/user-attachments/assets/86785e5d-21bd-443f-aba4-cdad2b879b0d" />
<img width="1253" height="570" alt="Screenshot 2026-10-26 184835" src="https://github.com/user-attachments/assets/b573d552-bd13-4f9b-8f51-745e272453ac" />
<img width="982" height="450" alt="Screenshot 2026-10-26 184848" src="https://github.com/user-attachments/assets/6d0c9149-6914-4816-b025-c2df7c6e599e" />
<img width="940" height="456" alt="Screenshot 2026-10-26 185029" src="https://github.com/user-attachments/assets/3b762978-6ba5-418a-8610-3dfc9be07bb0" />
<img width="985" height="427" alt="Screenshot 2026-10-26 185041" src="https://github.com/user-attachments/assets/935039f8-eeee-4b7e-a572-c72ff817cd38" />
<img width="982" height="407" alt="Screenshot 2026-10-26 185051" src="https://github.com/user-attachments/assets/f67baf0e-d4d2-4b78-aa57-aa029698f731" />
<img width="815" height="512" alt="Screenshot 2026-10-26 185111" src="https://github.com/user-attachments/assets/ece10d8f-8ba9-4918-a0a9-bfb8bec0ddfe" />
