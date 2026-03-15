# NYC Wage Compliance Audit: Fiscal Year 2025

## Project Overview
This repository contains a forensic payroll audit of New York City municipal employees for the 2025 fiscal year. By analyzing a dataset of 6.7 million records from NYC Open Data, this study identifies systemic minimum wage violations, assesses the disparate impact on lower-income demographics, and calculates the total legal liability for the city.

## Problem Statement
Despite New York State mandates setting the minimum wage at $16.50/hour, non-compliance persists within specific municipal sectors. This analysis quantifies these gaps and identifies the job titles most susceptible to wage floor violations.

---

## Analysis Methodology
* **Data Transformation:** Filtered 6.7M records to a verified sample of 153,226 based on active employment status and non-zero work hours.
* **Statistical Rigor:** Analysis conducted at a 95% confidence level with a margin of error of ±0.24%.
* **Tech Stack:**
    * **SQL (BigQuery):** Primary data extraction, cleaning, and transformation.
    * **Google Sheets:** Statistical enrichment, data aggregation, and pivot table analysis.

---

## Key Discoveries

| Metric | Result |
| :--- | :--- |
| **Systemic Impact** | 529 individuals identified below the $16.50 threshold. |
| **Disparate Impact** | Bottom 10th percentile is 9.66x more likely to experience violations. |
| **Financial Liability** | $6.17 Million (Includes 100% liquidated damages per NYS law). |
| **Primary Risk Sectors** | Caretakers (Frequency) and Eligibility Specialists (Severity). |

---

## Repository Contents

| File Name | Description |
| :--- | :--- |
| `NYC_Payroll_Transformed_Data.csv` | Processed dataset with calculated fields for hourly rates. |
| `Payroll_Aggregation_Summary.xlsx` | Workbook containing pivot tables and final liability calculations. |
| `analysis_queries.sql.txt` | Recovered SQL logic for data cleaning and transformation. |

---

## Contact and Professional Background
* **Benjamin Hough**
* **Education:** Bucks County Community College | Phi Theta Kappa Honor Society
* **Email:** [benh2734@gmail.com](mailto:benh2734@gmail.com)
* **LinkedIn:** [View Professional Profile](https://www.linkedin.com/in/benjamin-hough-34b6473a5)
