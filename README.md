# Banking_kpis_analysis
This project simulates banking transactions data and performs end-to-end data analysis in Python using jupyter notebook

The goal is to clean the data, compute key performance indicators (KPIs), visualize them with charts, and export a PDF report with business insights.

## Features

- Synthetic banking transactions dataset (no real customer data)
- Data cleaning and preprocessing in pandas
- KPI summary table (transaction volume, inflow/outflow, customers, time span)
- Visualizations:
  - KPI 1: Monthly net transaction volume (line chart)
  - KPI 2: Transaction amount vs time (scatterplot)
  - KPI 3: Product mix by transaction volume (pie chart)
  - Optional: Donut chart and channel bar chart
- Automated PDF report containing:
  - KPI charts
  - Text pages with insights and recommendations
- Export of cleaned dataset to CSV

- ## Project Structure

- `notebooks/banking_kpi_analysis.ipynb`  
  Main notebook with data creation, cleaning, KPI calculations, charts,
  KPI summary, and PDF export.

- `data/clean_bank_transactions.csv`  
  Cleaned dataset exported from the notebook.

- `data/kpi_summary.csv` (optional)  
  Tabular KPI summary generated from the cleaned data.

- `reports/bank_kpi_report_with_insights.pdf`  
  Multi-page PDF report containing charts and written interpretations.

- `src/data_generation.py` (optional)  
  Script version of the data-generation step if you prefer modular code.

  ## Setup

 Clone the repository:

   ```bash
   git clone https://github.com/<your-username>/banking-kpi-analysis.git
   cd banking-kpi-analysis

- `requirements.txt`  
  Python dependencies required to run the project.
