# Comparative Analysis of Loan Default Rates in Fannie Mae: 2007 vs. 2019

### Overview
This repository presents an in-depth analysis of Fannie Mae's single-family mortgage loan performance data, focusing on key trends in default rates, borrower profiles, and loan metrics from Q4 2007 to Q4 2019. The project aims to uncover patterns in loan performance, identify factors driving default rates, and provide actionable insights that can enhance financial decision-making, risk modeling, and policy development in the mortgage industry.

### Objectives

1. Analyze trends in loan defaults between 2007 and 2019.
2. Compare borrower characteristics and loan metrics over time.
3. Identify factors influencing default rates and loan performance.
4. Generate insights to support financial decision-making.

### Repository Contents

- **Midterm_Report_Template [(HTML)][HTML]**: R Markdown template for generating the project report.
- **Loan_Performance_Report [(R)][R]**: R script containing the data analysis and visualization code.
- **Loan_Data_2007Q4 [(RDS)][RDS1]**: Dataset of single-family loans from Q4 2007.
- **Loan_Data_2019Q4 [(RDS)][RDS2]**: Dataset of single-family loans from Q4 2019.
- **Default_Rates_Timeseries [(CSV)][CSV]**: Excel file containing quarterly default rates from 2020 Q1 to 2023 Q2.

### Methodology

**1. Data Loading**: The datasets were imported using R and cleaned to ensure consistency and accuracy.

**2. Exploratory Data Analysis (EDA)**: Key statistics and trends were identified using summary statistics and initial visualizations.

**3. Visualization**: Charts and graphs were created to illustrate trends in default rates, borrower credit scores, debt-to-income ratios, and loan-to-value ratios.

**4. Interactive Analysis**: Plotly was used to create interactive charts, allowing users to explore data in depth.

**5. Reporting**: Findings were compiled into a comprehensive report using R Markdown.

### Findings
- **Default Rates**: Default rates were significantly higher in 2007 compared to 2019, reflecting the financial instability during the 2008 crisis.
- **Borrower Characteristics**: Borrowers in 2007 had higher debt-to-income ratios, lower credit scores, and higher loan-to-value ratios, increasing the likelihood of default.
- **Loan Metrics**: Loan terms and origination channels showed notable differences between the two periods, impacting overall loan performance.

### Conclusion
The analysis highlights the importance of borrower creditworthiness and economic conditions in influencing loan performance. The findings can help financial institutions refine their risk assessment models and improve decision-making processes. By leveraging interactive visualizations, stakeholders can gain deeper insights into trends and patterns in mortgage data.


[HTML]: https://github.com/ronak-shah08/Fannie_Mae_Loan_Performance_Analysis/blob/main/Loan%20Performance%20Report.html
[R]: https://github.com/ronak-shah08/Fannie_Mae_Loan_Performance_Analysis/blob/main/Loan%20Performance%20Analysis.Rmd
[CSV]: https://github.com/ronak-shah08/Fannie_Mae_Loan_Performance_Analysis/blob/main/Default%20Rate%20Timeseries.csv
[RDS1]: https://github.com/ronak-shah08/Fannie_Mae_Loan_Performance_Analysis/blob/main/Loan%20Data%202007Q4.rds
[RDS2]: https://github.com/ronak-shah08/Fannie_Mae_Loan_Performance_Analysis/blob/main/Loan%20Data%202019Q4.rds
