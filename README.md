# Power BI Call Center Analysis Project

## Overview
ServiceSpot, an IT company, needed a solution to analyze their call center data effectively. The data was spread across multiple files, making it difficult to extract valuable insights. This project provides a **Power BI-based analytical solution**, offering interactive and visually appealing reports to help ServiceSpot make data-driven decisions.

## Additional Documentation
For detailed project insights, execution steps, and findings, refer to:
- [Power BI Project Explanation.pdf](https://github.com/nguyenpham0297/power-bi-service-spot/blob/main/1.%20Instruction%20%2B%20Data%20%2B%20Dictionnary/Power%20BI%20Project%20Project%20Explanation.pdf) – Project objectives, methodology, and evaluation criteria.
- [call_centre_data_final.pbix](https://github.com/nguyenpham0297/power-bi-service-spot/tree/main/2.%20Solution) - reports and dashboards file
- [ServiceSpot_Report_Finding.pdf](https://github.com/nguyenpham0297/power-bi-service-spot/blob/main/2.%20Solution/ServiceSpot_Report_Finding.pdf) – Summary of key insights derived from the reports.

## Project Structure
The project consists of two main folders:
1. **Instruction + Raw Data + Data Dictionary** – Contains documentation, raw data files, and the data dictionary.
2. **Solution** – Includes the Power BI solution file [`call_centre_data_final.pbix`](https://github.com/nguyenpham0297/power-bi-service-spot/blob/main/2.%20Solution/call_centre_data_final.pbix).

## Data Sources & Model
The dataset consists of multiple files capturing call center operations, employee details, revenue, and performance metrics. **Power Query** was used for data cleaning and transformation, while a **star schema** was implemented to optimize reporting.

### Key Data Elements
- **Call Records**: Contains call timestamps, duration, type, employee ID, and wait times.
- **Call Types**: Categorizes calls into Tech Support, Billing, and Sales.
- **Employees**: Includes employee details and performance metrics.
- **Revenue Data**: Tracks revenue generated by call type, location, and employee.
- **Geographical Data**: Call centers located in Florida, Colorado, and Washington.

## Key Findings
### 1. Call Center Overview
- Total calls: **131,821**
- Average call duration: **12.53 minutes**
- Average wait time: **30 seconds**
- **6%** of calls are abandoned.

### 2. Revenue Insights
- Revenue increased from **$463,265 (2018)** to **$555,441 (2021)** despite a slight decline in total calls.
- Florida generated the highest revenue (**$728,874**) followed by Colorado (**$696,664**) and Washington (**$598,245**).
- **Tech Support** and **Billing calls** contributed nearly **80%** of total revenue.
- **Top Employee:** Noella Valentin led in revenue generation over 4 years (**$33,782**), but Sheila Garcia was the top performer in the last 2 years.

### 3. Call Abandonment Analysis
- **7,923** calls were abandoned (6% of total calls).
- **Billing calls** had the highest abandonment rate (**6.21%**).
- **Tech Support** had the most abandoned calls (**3,967**).
- **No strong correlation** between wait time and abandonment rate.
- **Employee Training Needed**: Debora Wilker had the highest abandonment rate (**7.32%**).

### 4. Employee Performance
- **64 employees** distributed evenly across the three locations.
- **Average workload per employee:** **515 calls per year**.
- **Average revenue per employee:** **$31,622 per year**.

## Power BI Features Implemented
- **Data Integration:** Combined multiple sources into a single analytical model.
- **Data Cleaning:** Used Power Query to transform raw data.
- **Data Modeling:** Implemented relationships between fact and dimension tables.
- **DAX Measures:** Created KPIs for revenue, call performance, and employee analysis.
- **Interactive Dashboards:** Developed insightful visualizations for easy decision-making.

## Deployment & Usage
To explore the reports:
1. Open `call_centre_data_final.pbix` in **Power BI Desktop**.
2. Navigate through different report pages to analyze KPIs, trends, and performance.
3. Use slicers and filters to customize the analysis based on date range, employee, or call type.

## Contributors
- **Patrick Githendu**
- **Phuc Nguyen Pham**
- **Mohammed Danish Mustafa**
- **Trung Nguyen**

