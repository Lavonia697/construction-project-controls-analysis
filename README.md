# Construction Project Controls & Performance Analysis

![Construction Project Dashboard](https://github.com/Lavonia697/construction-project-controls-analysis/blob/main/dashboard/dashboard.png)

## Project Overview

This project uses Microsoft Excel to analyse construction project tracking records, with a focus on budget performance, schedule performance, project status validation, and data quality.

The project demonstrates an end-to-end data analysis workflow, from cleaning inconsistent records and creating calculated columns to building PivotTables, KPI cards, charts, and a dashboard.

## Business Problem

Construction project tracking data can contain inconsistent labels, missing cost information, duplicate-looking records, schedule variances, and disagreements between recorded project statuses and reported progress.

The objective of this analysis is to organise the data, identify areas that require investigation, and present the latest recorded project position in a clear dashboard.

## Tools Used

- Microsoft Excel
- Excel formulas and calculated columns
- PivotTables and PivotCharts
- Data validation and quality checks
- Interactive dashboard design

## Analysis Workflow

1. Reviewed and cleaned the source data.
2. Standardised inconsistent text values.
3. Created missing-data and status-validation flags.
4. Calculated cost and schedule variances.
5. Identified the latest dated tracking records for each project.
6. Summarised results using PivotTables.
7. Built KPI cards and four dashboard charts.
8. Documented business insights and recommendations.

## Key Findings

The dashboard covers 20 projects using their latest selected tracking records:

- **55% recorded as over budget:** 11 projects.
- **70% recorded as behind schedule:** 14 projects.
- **70% flagged for status review or mismatch:** 14 projects.
- **2 projects flagged as having missing cost data.**

## Business Recommendations

- Investigate budget variances and review cost estimates and approved changes.
- Examine schedule delays, resource availability, and subcontractor dependencies.
- Reconcile recorded project statuses with progress percentages.
- Complete missing cost information before making financial assessments.

## Limitations

The results reflect the latest dated tracking records selected for analysis, not necessarily final project outcomes. Some cost information is missing, and status flags identify records for review rather than proving that the underlying project information is incorrect.

A pair of records for one project had the same latest update date and appeared identical apart from the Record_ID. I investigated the potential duplicate and excluded one record from the analysis copy to avoid double-counting, while preserving the original raw dataset for traceability.

## Project Files
- Completed Excel Analysis
- Dashboard Screenshot
- Data Cleaning Process
- Analysis Methodology
- Business Insights

## Project Deliverables

- Cleaned construction tracking data
- Calculated cost, schedule, and status fields
- PivotTables summarising project performance
- Dashboard with KPI cards and four charts
- Business insights and recommendations
- Data cleaning and analysis methodology documentation
