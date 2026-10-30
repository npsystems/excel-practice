# Excel Data Analytics Project

## Project Overview

This project is a personal Excel learning exercise built around a financial transactions dataset. It was designed to practice data cleaning, Excel formulas, PivotTables, data visualization, and basic analytical reporting while developing an end-to-end workflow in preparation for more structured learning and future portfolio projects.

## Objectives

1. Develop a structured learning guide for completing an end-to-end Excel analytics project.
2. Practice data cleaning techniques and Excel formulas to investigate potential data-quality issues.
3. Analyze transaction data using formulas and PivotTables, then visualize the findings in a dashboard.
4. Communicate the findings, potential business implications, and recommended next steps in a concise report.

## Tools Used

- **ChatGPT:** Used to develop the learning packet, optimize Excel functions, and refine the report.
- **Microsoft Excel:** Used for data cleaning, formulas, conditional formatting, PivotTables, and charts.

## Methodology

The dataset used was the *Dirty Financial Transactions Dataset* from Kaggle. The table was cleaned by duplicating the raw data into a separate sheet and applying corrective formatting. Dates and number columns were reformatted to exclude errors, conditional formatting scales were applied to the quantity and price columns, blank or missing values were highlighted with a blackout, and the product column was reformatted to fix spelling errors. Sorting was used to improve the readability and organization of the dataset.

The dataset was examined through the practical application of a variety of Excel functions. Each function was paired with a question pertaining to the database. Afterwards, an analytical question was developed for the report, and a separate Excel sheet was created to break down the question into PivotTable analysis and paired questions. The dashboard presented visualizations from the PivotTables, along with a summary of the analysis and findings.

## Key Findings

The transaction dataset contains numerous records with potential data-quality issues, including suspicious quantities, negative prices, and missing transaction statuses that were flagged for investigation.

The analysis identified the following records:

| Potential Data-Quality Issue | Number of Records |
|---|---:|
| Suspicious quantities | 52,984 |
| Negative prices | 29,780 |
| Missing transaction statuses | 15,672 |

## Recommendations

The identified discrepancies may affect the accuracy and reliability of sales reporting. Further investigation is recommended to determine the causes of these inconsistencies and whether corrective action is necessary.

Specifically, suspicious records may need verification to determine whether there was an input or calculation error. Additionally, negative transactions may need to be verified to check for adjustments, credits, returns, or other errors.

Missing transaction statuses may make the intended outcomes harder to determine. The process for categorizing a transaction may need to be verified to detect any looping errors. Addressing these issues could improve data quality and support more reliable business decisions.

## Limitations

The analysis identifies records that meet the project's criteria for potential data-quality issues. These flags do not necessarily indicate confirmed errors. Additional investigation using business rules or supporting transaction records would be required to determine the cause and validity of each discrepancy.

## Project Files

The repository is organized into the following directories and files:

```text
excel-data-analytics-project/
├── README.md
├── data/
│   ├── raw/
│   │   └── dataset.csv
│   └── cleaned/
│       └── cleaned_dataset.xlsx
├── excel/
│   ├── excel-learning-guide.pdf
│   ├── analysis_workbook.xlsx
│   └── dashboard.xlsx
├── reports/
│   └── business_report.pdf
└── excel-data-analytics-project.zip
