# Business Survey Data Analysis - Migori 2025/26

## Project Overview

This project analyzes business survey data collected in Migori during the 2025/2026 field study. The data was gathered through a structured questionnaire, with enumerators surveying three businesses each. The survey covers business characteristics, ownership, employment size, operational history, and challenges faced by local enterprises.

## Workflow Summary

1. **Data Preparation (SQL):**
   - Clean and standardize raw survey data.
   - Correct inconsistent responses, handle missing values, and organize categorical variables.
   - Drop irrelevant columns and standardize values (e.g., gender, spaces, N/A values).
2. **Data Transformation:**
   - Use SQL aggregation to generate summary statistics (e.g., business sector, ownership, gender, years of operation, constraints).
   - Normalize and categorize data (e.g., employee size, business category).
   - Create views for exploratory data analysis (EDA) on gender, sector, ownership, and business maturity.
3. **Visualization:**
   - Connect cleaned data to Microsoft Power BI.
   - Develop dashboards to visualize economic structure, business diversity, employment, and operational challenges.

## Key Analytical Areas

- **Survey Distribution:** Analysis by area, gender, sector, and business size.
- **Business Profiling:** Owner demographics, business maturity, and expansion rates.
- **Growth and Stagnation:** Identification of micro-business dominance, gender scaling gaps, and expansion barriers.
- **Spatial-Economic Dynamics:** Comparison of Lower Marindi (CBD), Wasweta 1, and Oruba in terms of business growth, sector specialization, and challenges.
- **Barrier Analysis:** Examination of hurdles such as high costs, taxes, access to finance, premises, infrastructure, sanitation, and competition.
- **Planning Recommendations:** Data-driven interventions for infrastructure, safety, and economic policy to support business growth.

## Technologies Used

- **Jupyter Notebook** for workflow documentation and SQL execution.
- **SQL (ipython-sql, pymysql)** for data cleaning, transformation, and analysis.
- **Power BI** for interactive dashboard development.

## How to Reproduce

1. Install required Python packages:
   - `ipython-sql`
   - `pymysql`
2. Connect to the MySQL database containing the business survey data.
3. Run the notebook cells in order to clean, transform, and analyze the data.
4. Use the cleaned and aggregated data in Power BI for visualization.

## Data Source

- Raw data: `Raw Data/MIGORI STUDIO 2025_26 - Business Questionnaire.csv`
- Analysis notebook: `Business_Questionnaire/business.ipynb`

## Locating the Analysis File

The analysis for this project can be found in the following file:

- **File Name:** `business.ipynb`
- **Location:** `Business_Questionnaire/` directory

Open this Jupyter Notebook to view the full analysis and results.

## Notes

- Oruba has a very small sample size (3 records), which may skew comparisons.
- The project demonstrates the transformation of field-collected survey data into actionable insights for planners, researchers, and stakeholders.

## License

This project is licensed under the MIT License.

---
