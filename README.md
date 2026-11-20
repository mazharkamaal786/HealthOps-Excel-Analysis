# HealthOps-Excel-Analysis
Excel dashboard on 51K hospital encounters: cost, utilization and readmission analysis
# HealthOps Excel Analysis

Excel dashboard analyzing hospital cost, utilization and 30-day readmission on 51,101 patient encounters (2015 to Oct 2026).

![Dashboard](dashboard.png)

## Key Numbers
- 51,101 encounters, 1,055 unique patients
- Total claim cost: $147.9M, payer coverage 73.4%
- 30-day readmission rate: 21.4% (147 of 687 inpatient stays)
- Average inpatient stay: 5.2 days

## What I Built
- Cleaned and filtered the dataset to 2015 onwards
- Helper columns: Patient Paid, High Cost
- 6 KPI cards and 6 PivotCharts (cost by class, yearly trend, average cost by age band, top 10 visit reasons, who pays, readmission by age band)
- Slicers for Year, Encounter Class and Age Band
- Calculated field for readmission rate, conditional formatting on the KPI card

## Key Insights
1. Ambulatory visits make up about 65% of total claim cost.
2. Inpatient stays are only about 1.3% of encounters but about 14.5% of cost.
3. Readmission is highest in the 35-49 (27.4%) and 50-64 (29.2%) age bands.
4. The 18-34 age band has the highest average claim cost.
5. Chronic kidney disease stage 4 is the most common visit reason (7,310 encounters).

## Limitations
- The data is synthetic (Synthea), so patterns such as the low 65-79 readmission rate may not match real hospitals.
- 2026 data runs only until October.

## Tools
Excel 2016: Tables, PivotTables, PivotCharts, Slicers, calculated fields, conditional formatting.

## Files
- `HealthOps_Excel_Analysis.xlsx`: the full workbook
- `dashboard.png`, `pivots.png`: screenshots

Author: Mazhar Kamaal | [LinkedIn](https://linkedin.com/in/mazhar-kamal-2599963a9)
