# Bank Data Analytics and Automation Internship Portfolio

## Project Overview

This repository presents selected data analytics and automation work developed during a Data Analytics internship at a microfinance bank from July 2025 to September 2025. The work focuses on regulatory data validation, data cleaning, loan recovery analysis, and workflow automation using Python, SQL, Excel, and supporting documentation.

To protect banking privacy, the repository does not include confidential customer or institutional data. The code and documentation are intended to demonstrate the technical logic and analytical workflow without exposing sensitive records.

## Tools and Skills

- **Python:** Pandas, NumPy, Tkinter, regular expressions, data validation, and file automation
- **SQL:** Aggregation, grouping, segmentation, recovery analysis, branch analysis, and customer activity analysis
- **Excel Automation:** XlsxWriter-based highlighting, summaries, and charts
- **Data Quality:** Field validation, error detection, data cleaning, and compliance-oriented checks
- **Reporting:** Analytical documentation and presentation of automation workflows

## Main Projects

### 1. Regulatory Data Validation and Cleaning Tool

The Python application provides a desktop interface for selecting a CSV file and automatically validating banking data fields.

Key capabilities include:

- Customer name validation
- CNIC and identification number checks
- Mobile and landline phone validation
- Date validation
- KYC debit and credit amount checks
- Account and customer ID format checks
- Customer risk category validation
- Address and relationship field checks
- Automatic highlighting of invalid values in Excel
- Field-level error summaries
- Error distribution charts
- Error analysis by account-opening year

During the internship, this workflow was designed to support high-volume regulatory data checking and reduce manual review effort.

### 2. Loan Recovery Analysis with SQL

The SQL scripts analyze loan recovery activity from several operational perspectives, including:

- Total actions, unique loans, and unique customers
- Contact mode distribution
- Recovery chance distribution
- Branch-level customer engagement
- Area-level loan activity
- Account severity analysis
- Recovery chance by contact mode
- Branch performance segmented by recovery chance
- Action amount analysis

The scripts are kept as separate files to show the individual analytical queries used during the project.

### 3. Compliance Automation Documentation

The PowerPoint presentation documents the compliance data validation automation workflow, while the Word report contains the loan recovery analysis and supporting interpretation.

## Repository Files

| File | Purpose |
|---|---|
| [Latest cleaning tool by Hamis Arqum.py](Latest%20cleaning%20tool%20by%20Hamis%20Arqum.py) | Python desktop tool for CSV validation, cleaning, Excel highlighting, summaries, and charts |
| [Script.sql](Script.sql) | Overall action, loan, and customer counts |
| [Script-1.sql](Script-1.sql) | Multi-part SQL analysis covering contact modes, recovery, branches, areas, severity, and action amounts |
| [Script-2.sql](Script-2.sql) | SQL table structure inspection |
| [Script-3.sql](Script-3.sql) | Recovery chance analysis by contact mode |
| [Script-4.sql](Script-4.sql) | Branch activity segmented by recovery chance |
| `Script-5.sql` to `Script-9.sql` | Additional loan recovery analytical queries |
| [Automating-Compliance-Data-Validation.pptx](Automating-Compliance-Data-Validation.pptx) | Presentation documenting the compliance automation workflow |
| [Loan recovery Analysis.docx](Loan%20recovery%20Analysis.docx) | Loan recovery analysis report and interpretation |
| [requirements.txt](requirements.txt) | Python package requirements |

## Running the Python Tool

Install the required packages:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
python "Latest cleaning tool by Hamis Arqum.py"
```

Select a CSV file through the desktop interface. The tool creates an Excel output file with highlighted validation issues, a summary sheet, and analytical charts.

## Portfolio Impact

This project demonstrates practical experience with:

- Automating repetitive data-quality checks
- Working with large banking datasets
- Converting manual validation rules into reusable Python logic
- Using SQL to investigate recovery and operational performance
- Producing business-facing Excel outputs and analytical documentation

## Confidentiality

No raw confidential banking data is included in this repository. The shared scripts and documents are intended to demonstrate the technical approach while protecting customer and institutional information.

## Contact

**Muhammad Hamis Arqum**

[LinkedIn Profile](https://www.linkedin.com/in/hamis-arqum/)
