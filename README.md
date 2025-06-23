# International Debt Analysis

## Project Overview
This repository contains a data analysis project focused on exploring international debt statistics provided by The World Bank. The dataset includes debt information (in USD) for various countries across multiple debt indicators from 1970 to 2015. The primary goal of this project is to uncover insights into global debt patterns, such as total debt owed, the countries with the highest debt, and average debt across different indicators. The analysis is performed using **SQL** for data querying and **Power BI** for data visualization and dashboard creation.

### Objectives
- Determine the total amount of debt owed by countries in the dataset.
- Identify the country with the maximum debt and its corresponding amount.
- Calculate the average debt across various debt indicators.
- Analyze debt distribution by country and indicator to identify trends and patterns.
- Visualize key findings through interactive dashboards in Power BI.

## Dataset
The dataset is sourced from The World Bank and contains national and regional debt statistics for 124 countries from 1970 to 2015. Key columns include:
- `country_name`: Name of the country.
- `indicator_code`: Code representing the type of debt (e.g., PPG, private creditors).
- `indicator_name`: Description of the debt indicator.
- `debt`: Amount of debt in USD.

The dataset is stored in a relational database (`international_debt`) for SQL analysis and imported into Power BI for visualization.

## Tools Used
- **SQL**: For querying and analyzing the dataset to extract meaningful insights.
  - Environment: Jupyter Notebook with `ipython-sql` library or SQL Server Management Studio.
- **Power BI**: For creating interactive visualizations and dashboards to present findings.


## Setup Instructions
### Prerequisites
- **SQL Environment**: MySQL, PostgreSQL, or Microsoft SQL Server installed.
- **Power BI Desktop**: Installed on a Windows machine.
- **Git**: To clone the repository.

### Steps
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Madhuraa-k/International-Debt-Analysis.git
   cd International-Debt-Analysis
   ```

2. **Set Up the Database**:
   - Import the `DB.sql` file into your SQL database:
     ```bash
     mysql -u your_username -p your_database_name < sql/DB.sql
     ```
   - Alternatively, use SQL Server Management Studio to restore the database.

3. **Run SQL Queries**:
   - Open `sql/queries.sql` in your SQL client or Jupyter Notebook.
   - Execute the queries to reproduce the analysis.

4. **Explore Power BI Dashboard**:
   - Open `power_bi/dashboard.pbix` in Power BI Desktop.
   - Ensure the data source is connected (update the data source settings if needed).
   - Interact with the dashboard to explore visualizations.

## Visualizations
Screenshot of the Power BI dashboard are available in the `power_bi/dashboard_screenshot.png` . 
