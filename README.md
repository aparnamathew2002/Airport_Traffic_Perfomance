Airport Traffic Analysis: January 2025 vs January 2026


Project Overview

This project analyzes airport traffic data from January 2025 and January 2026 using SQL. The objective is to identify traffic trends, compare airport and state-level performance, evaluate arrival and departure patterns, and generate business insights through data analysis.

Objectives

 * Perform data cleaning and validation on airport traffic datasets.
 * Analyze airport and state-level flight activity.
 * Compare traffic performance between January 2025 and January 2026.
 * Identify high-performing airports and regions.
 * Apply advanced SQL techniques to solve business problems.
 * Generate actionable insights from air traffic data.


Dataset
The analysis uses two datasets:

 * Airport Traffic Data – January 2025
 * Airport Traffic Data – January 2026

Key Columns

| Column     | Description       |
| ---------- | ----------------- |
| apt_icao   | Airport ICAO Code |
| apt_name   | Airport Name      |
| state_name | State/Region      |
| flt_date   | Flight Date       |
| flt_dep_1  | Total Departures  |
| flt_arr_1  | Total Arrivals    |
| flt_tot_1  | Total Flights     |
| month_num  | Month Number      |
| month_mon  | Month Name        |


SQL Concepts Used
 * Basic SQL
   * SELECT
   * WHERE
   * ORDER BY
   * LIMIT
   * Aggregate Functions (SUM, COUNT, AVG)

 * Intermediate SQL
   * GROUP BY
   * HAVING
   * Subqueries
   * UNION ALL

 * Advanced SQL
  * Common Table Expressions (CTEs)
  * Window Functions
    * RANK()
    * DENSE_RANK()
    * LAG()
  * Running Totals
  * Year-over-Year Analysis

Analysis Performed

* Data Cleaning
  * Checked for missing values
  * Identified duplicate records
  * Validated flight count values
* Airport Analysis
  * Top airports by total traffic
  * Airport rankings using window functions
  * Arrival vs Departure ratio analysis
* State Analysis
  * State-wise traffic distribution
  * State ranking based on total flights
* Comparative Analysis
  * January 2025 vs January 2026 traffic comparison
  * Airport-level year-over-year analysis
  * State-level year-over-year analysis
* Advanced Analytics
  * Running total of flight traffic
  * Growth analysis using CTEs and window functions


Key Business Insights

* Airport traffic is concentrated among a limited number of major hubs.
* Several airports experienced significant growth between January 2025 and January 2026.
* Traffic distribution varies considerably across states.
* Most airports maintain balanced arrival and departure operations.
* Year-over-year analysis highlights changing traffic patterns and airport performance.

Tools & Technologies

* SQL (MySQL)
* MySQL Workbench
* Jupyter Notebook
* VS Code
* Python (for data loading and notebook environment)

Conclusion

This project analyzed airport traffic data from January 2025 and January 2026 using MySQL. The analysis involved data cleaning, aggregation, ranking, window functions, common table expressions (CTEs), and year-over-year comparisons. The results identified major aviation hubs, highlighted regional traffic patterns, and revealed changes in airport and state-level performance between the two years. The project demonstrates practical SQL skills for data extraction, transformation, analysis, and business reporting.
