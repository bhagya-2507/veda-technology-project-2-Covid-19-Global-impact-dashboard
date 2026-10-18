# COVID-19 Global Impact Dashboard

## Project Overview
The COVID-19 Global Impact Dashboard project explores COVID-19 data to understand reported cases, deaths, and trends across countries over time. The project focuses on data cleaning, data quality checks, exploratory data analysis, and visualization using Python.

## Objectives
- Clean and prepare the COVID-19 dataset for analysis.
- Identify missing values and check duplicate records.
- Analyze reported COVID-19 cases and deaths over time.
- Compare reported cases and deaths across countries.
- Present findings through charts and summary reports.

## Tools and Technologies
- Python
- Pandas
- Matplotlib
- Jupyter Notebook
- CSV Dataset
- GitHub

## Dataset Information
The project uses a COVID-19 dataset containing country-level information and daily reported indicators.

- **Raw dataset:** 617,667 rows and 61 columns
- **Cleaned dataset:** 538,921 rows and 61 columns
- **Countries/locations:** 227
- **Date range:** 1 January 2020 to 30 August 2026

The cleaned dataset contains missing values. The `human_development_index` field was reported as entirely missing in the inspected data.

**Data quality note:** The cleaned dataset contains fewer rows than the raw dataset. The exact reason for this difference should be verified from the cleaning process before attributing it to a specific operation.

## Project Structure

```text
COVID-19-Global-Impact-Dashboard/
├── data/
│   ├── raw/
│   │   └── covid_data.csv
│   └── processed/
│       └── covid_cleaned.csv
├── notebooks/
│   └── 01_data_cleaning.ipynb
├── reports/
│   ├── project_summary.csv
│   ├── missing_values_report.csv
│   ├── monthly_covid_trends.png
│   ├── country_total_cases.png
│   ├── country_total_deaths.png
│   └── COVID19_Executive_Summary.pdf
└── README.md
```

## Data Analysis and Visualizations

The project includes the following analysis outputs:

1. **Project Summary:** A summary of the dataset and analysis.
2. **Missing Values Report:** A report showing missing values in the dataset.
3. **Monthly COVID-19 Trends:** A chart of reported cases and deaths over time.
4. **Country-wise Total Cases:** A comparison of reported case totals across countries.
5. **Country-wise Total Deaths:** A comparison of reported death totals across countries.

## Key Data Quality Findings

- The dataset covers 227 countries/locations.
- The observed date range runs from January 2020 to August 2026.
- The cleaned dataset still contains substantial missing data.
- Some indicators may have incomplete country-level coverage.
- Country comparisons should be interpreted carefully because reporting practices and missing data can differ.

## How to Run the Project

1. Download or clone this repository.
2. Open the project folder.
3. Open the `notebooks/01_data_cleaning.ipynb` notebook in Jupyter Notebook.
4. Ensure the required Python libraries are installed.
5. Run the notebook cells in order.
6. Review the cleaned dataset and generated reports in the `data/processed/` and `reports/` folders.

## Limitations

- Missing values remain in several dataset fields.
- Reported case and death figures depend on the available source data.
- The reason for the raw-to-cleaned row-count difference should be confirmed from the cleaning code.
- The analysis represents reported data and should not be interpreted as a complete measure of the pandemic's impact.

## Conclusion

This project demonstrates a workflow for cleaning, inspecting, analyzing, and visualizing COVID-19 data. The resulting summary reports and charts support exploratory analysis of reported cases and deaths across time and countries.

The project also highlights the importance of documenting data-cleaning decisions and considering missing data when interpreting results.

---

**Project:** COVID-19 Global Impact Dashboard  
**Internship:** VEDA Technology — Data Analytics