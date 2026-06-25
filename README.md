# Maddoxpay-Transaction-Analysis
## Objective of the Project:
MaddoxPay is a digital financial services platform that provides payment, banking, and financial solutions across India. It offers services such as AEPS, money transfer, bill payments, and recharges through its extensive retailer network. 
The primary objective of this project was to analyze a transaction dataset from MaddoxPay using Python-based data analysis tools. The analysis aimed to:
Understand transaction patterns and trends over time (daily, monthly, and quarterly).
Evaluate the performance of different payment methods.
Examine location-wise activity in terms of both transaction count and value.
Study the distribution of transaction statuses (success, failed, pending).
Identify the top merchants and customers contributing to transaction activity.
Export findings in structured formats (Excel reports, PDF of visualizations).
## Technology used:
### 1. Python: 
Python was the primary programming language used in this project. Its simple syntax and extensive libraries made it suitable for data analysis, visualization, and report generation.

**Features:**
 - Easy and readable syntax
 - Large library support
 - Efficient data analysis and visualization
### 2. Pandas:
Pandas was used for data manipulation and analysis of the MaddoxPay transaction dataset.

**Features:**
 - Importing CSV files
 - Data cleaning and preprocessing
 - Grouping and aggregating data
 - Calculating KPIs
 - Exporting results to CSV and Excel files
### 3. Matplotlib:
Matplotlib was used to create visualizations such as:
 - Bar charts
 - Line graphs
 - Pie charts
 - Trend analysis graphs
   
It was also used to save graphs as images and generate PDF reports.
### 4. PdfPages (Matplotlib Backend):
PdfPages, available in Matplotlib, was used to combine multiple graphs into a single PDF file. This allowed all charts and visualizations to be stored and shared in one professional report.

**Features:**
 - Combines multiple graphs into one PDF.
 - Simplifies sharing of results.
 - Provides a professional reporting format.
### 5. openpyxl:
openpyxl was used to create formatted Excel reports containing multiple analysis tables.

**Features:**
 - Writing multiple tables into one Excel file.
 - Adding titles and spacing between tables.
 - Applying formatting such as fonts, colors, and column widths.

### 6. Google Colab:
Google Colab was used as the development environment for the project. It allowed the execution of Python code in the browser without local installation.

**Features:**
 - Cloud-based environment.
 - Access to pre-installed libraries.
 - Easy integration with Google Drive.
 - Simple sharing and collaboration.

## Dataset Description:
The dataset used in this project contained transaction records with the following key fields:
 - **Transaction ID:** Unique identifier for each transaction.
 - **Date:** The date on which the transaction occurred.
 - **Transaction Amount:** Value of the transaction in INR.
 - **Customer ID:** Identifier for the customer making the transaction.
 - **Merchant:** Identifier for the merchant processing the transaction.
 - **Payment Method:** Mode of payment (e.g., UPI, Card, Wallet, Net Banking).
 - **Location:** The geographical location where the transaction took place.
 - **Transaction Status:** Outcome of the transaction (Success, Failed, Pending).

## Approach/Steps:
### 1. Data Import and Cleaning: 
 - Imported the transaction dataset from a CSV file.
 - Converted the Date column into proper datetime format for accurate time-based analysis.
 - Checked and removed duplicate entries to ensure data consistency.
 - Handled missing or invalid values to maintain data integrity.

### 2. Key Performance Indicators (KPIs):
 - **Total Transactions:** Count of all transactions processed.
 - **Total Transaction Value:** Sum of transaction amounts across the dataset.
 - **Average Transaction Value:** Mean value of transactions, highlighting customer spending behavior.
 - **Success Rate:** Percentage of successful transactions out of total transactions.
 - These KPIs provided a bird’s-eye view of the company’s digital transaction performance.

### 3. Trend Analysis:
 - **Daily Analysis:** Count of transactions per day revealed fluctuations, with peaks on weekends and festive periods.
 - **Monthly Analysis:** Identified steady growth in transaction volumes, with certain months contributing significantly higher transaction values.
 - **Quarterly Analysis:** Showed clear upward trends.

### 4. Categorical Analysis:
 - **Payment Method Usage:** It showed us the most popular methods for transactions. The result suggested that the consumers and Indian public is using more and more digital payment methods such as UPI etc.
 - **Location-Wise Insights:** Urban regions contributed higher transaction values, while rural areas showed more transaction counts but smaller average values — a reflection of MaddoxPay’s inclusive outreach.
 - **Transaction Status:** Most transactions were successful, while a small portion of failed and pending transactions highlighted opportunities for technical improvement.

### 5. Entity-Based Insights:
 - **Top Merchants:** The top 5 merchants processed the largest number of transactions, contributing significantly to the platform’s success.
 - **Top Customers:** The top 10 customers were identified as repeat users with high-frequency transactions, indicating customer loyalty.

### 6. Visualization and Reporting:
 - Created bar graphs, line plots, and pie charts to visually represent trends and comparisons.
 - Exported all graphs into a single consolidated PDF report using Matplotlib’s PdfPages.
 - Compiled all tabular data into an Excel report with multiple sheets and formatted tables using openpyxl for readability.
 - Exported all graphs into PNG images, all tables into CSV files.

## Key Findings:
### 1. Overall KPIs:
 - The dataset showed a steady growth in transaction volumes over the observed period.
 - The success rate of transactions was high, indicating reliability of the payment system.
 - The average transaction value remained within a consistent range, reflecting stable customer spending behavior.

### 2. Transaction Trends:
 - Daily trends revealed fluctuations in transaction counts, often peaking during weekends and festive seasons.
 - Monthly and quarterly analysis showed upward growth.
 - The increasing trend suggests growing adoption of MaddoxPay services among customers and merchants.
 - High valued transactions were also found out.

### 3. Payment Method Usage:
 - It showed us the most popular methods for transactions.
 - The result suggested that the consumers and Indian public is using more and more digital payment methods such as UPI etc.
 - The increasing trend suggests growing adoption of MaddoxPay services among customers and merchants.
 - High valued transactions were also found out.

### 4. Location-wise Analysis:
 - Certain urban locations contributed a disproportionately high transaction value, while rural locations showed a higher transaction count but lower average value.
 - This suggests that MaddoxPay is succeeding in reaching rural consumers, though transaction sizes there remain smaller.
 
### 5. Transaction Status:
 - A majority of the transactions were marked Successful.
 - A small proportion of Failed and Pending transactions highlighted potential areas for technical improvement.

### 6. Merchant and Customer Insights:
 - The top 5 merchants accounted for a major share of overall transactions, indicating strong partnerships.
 - The top 10 customers were identified as frequent, high-value users—signifying loyal customer segments.

### 7. Reports and Visualizations:
 - An Excel workbook was generated with detailed tables for each analysis (daily, monthly, quarterly, location-wise, status-wise).
 - A consolidated PDF report was generated containing all graphs (bar charts, pie charts, and line graphs) for ease of presentation.
 - Also, individual png images of the graphs, pie charts etc. separately generated. And the each table corresponding to graphs, pie charts etc is also generated as a csv file.



