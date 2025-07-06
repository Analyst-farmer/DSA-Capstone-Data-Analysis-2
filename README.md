# DSA-Capstone-Data-Analysis-2

## Palmoria Group Employee Data Analysis

## Project Title: Employee Demographic, Performance, and Compensation Analysis – Palmoria Group

### Executive Summary
This report documents the end-to-end analysis conducted on Palmoria Group’s employee data to provide actionable insights around workforce distribution, performance evaluation, salary structure, and compliance with new wage regulations. A secondary dataset containing bonus payment rules was also integrated to compute total compensation packages.

### Data Sources
* Employee Dataset (CSV) – 1,015 records
* Bonus Rules (Excel) – Bonus multipliers based on department and rating

### Data Cleaning and Preparation
Missing Gender: Replaced with _"Undisclosed"_
* Removed Records:
  * Employees with no salary (ex-employees)
  * Departments marked as _NULL_
  * Final cleaned dataset: 946 valid employee records

### Key Analyses & Visual Insights
**Gender Distribution**
* Overall: 465 Male, 441 Female, 40 Undisclosed
* By Region: Fairly balanced across Lagos, Kaduna, and Abuja
* By Department: Slight male dominance in Legal and Accounting; more parity in Engineering and HR
**Performance Rating by Gender**
* Ratings included: Very Good, Good, Average, Poor, Not Rated
* Rating distribution appeared proportional across all gender categories
* No bias detected in ratings allocation by gender
  
**Salary Structure & Gender Pay Gap**
* Mild gender pay gap observed, especially in:
  * Engineering
  * Legal
* Regionally, Lagos showed wider disparity than Kaduna and Abuja
* Suggested: Department-specific audit and pay structure adjustments
  
**Minimum Wage Compliance**
* Regulation: Minimum salary of $90,000 for manufacturing employees
* Findings:
  * Not all employees in the manufacturing-related departments meet this threshold
  * Compliance is partial and requires attention
    
**Pay Band Analysis**
* Employees grouped into $10,000 salary bands:
  * Most employees fell between $60,000–$100,000
* Visualization by region revealed:
  * Kaduna has more employees in lower salary bands
  * Lagos shows higher concentration in upper bands
    
**Bonus Calculation**
* Bonus Logic:
  * Based on employee department and performance rating
  * Bonus multipliers applied to base salary
* Output:
  * Bonus per employee calculated
  * Total compensation (Salary + Bonus) computed
* Aggregated totals:
  * Total Company Bonus Paid: $X (calculated after data reload)
  * Total Compensation Across All Employees: $Y
* Bonus by Region: Summarized for Lagos, Abuja, and Kaduna
  
**Deliverables**
* Cleaned dataset for Power BI modeling
* Bonus-integrated dataset
* Visual dashboards (Power BI visuals to be published)
* Executive summary for HR and Finance

### Tools Used
**Power BI**
* Data Cleaning and transformation
* Data review and light manipulation
* Visualizations and dashboard design

### Recommendations
* Conduct a gender pay audit in Legal and Engineering
* Review compliance with $90K regulation for manufacturing units
* Publish bonus policy across departments for transparency
* Consider flagging employees below performance targets for performance improvement planning

