# Bank Loan Report Dashboard

## Overview
This repository contains a comprehensive **Bank Loan Report** built using Power BI, analyzing a dataset of loan applications to monitor lending activities, portfolio health, and performance trends. The dashboard provides actionable insights into key metrics like total applications, funded amounts, repayment rates, and borrower profiles, enabling data-driven decisions for risk assessment and strategy optimization.

Key focus areas include:
- **Good vs. Bad Loans**: Classification based on status (Fully Paid/Current vs. Charged Off).
- **Trend Analysis**: Monthly trends, regional distributions, and breakdowns by loan term, purpose, employment length, and home ownership.

## Features
- **Dashboard 1: Summary** - KPIs for applications, funded/received amounts, average interest rates, DTI, and loan status grid.
- **Dashboard 2: Overview** - Visualizations including line charts (monthly trends), filled maps (state-wise), donut charts (loan terms), bar charts (employee length/purpose), and treemaps (home ownership).
- **Dashboard 3: Details** - Consolidated view of borrower and loan details.
- Interactive filters for grade, state, purpose, and more.
- SQL queries for data extraction and aggregation.

## Dataset
- **Source**: `financial_loan.csv` (sample of ~3,000+ records with columns like `loan_amount`, `dti`, `loan_status`, `purpose`, etc.).
- Data covers loan applications from 2021, including demographics, financials, and outcomes.

## Technologies
- **Visualization**: Power BI
- **Data Processing**: SQL (queries in `Query_Docs_Bank_Loan_Data.docx` or this link: https://docs.google.com/document/d/1-UYgk6RfVVsC81fgi6kqRIODEWTrLuMJ4RM2M79sH8Q/edit?usp=sharing)

## Setup Instructions
1. Clone the repo: `git clone https://github.com/yourusername/bank-loan-report.git`
2. Open `financial_loan.csv` in Power BI Desktop.
3. Import SQL queries from `Query_Docs_Bank_Loan_Data.docx` to recreate measures.
4. Apply relationships (e.g., on `id`, `issue_date`).
5. Load the `.pbix` file (if provided) or rebuild dashboards per `Problem Statement.docx`.
6. Explore filters and slicers for dynamic views.

## Screenshots
See the /images folder for dashboard previews (e.g., summary KPIs, monthly trends, state maps).

## Contributing
Contributions welcome! Fork, raise issues, or submit PRs for enhancements like additional metrics or ML-based predictions.
