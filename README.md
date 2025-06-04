## Repository Structure and File Overview

This repository contains all the resources and files related to the DS594 BCAN project completed by Jaejoong Kim, organized into the following directories:

### 1. `analysis` Folder
This folder includes Python notebooks and data files for analysis:
- **Code_merged_cleaned_data.ipynb**: A Jupyter notebook for analyzing and cleaning the merged data.
- **DS594_BCAN_Property_Analysis_Testing.ipynb**: A testing notebook for project-specific analysis.
- **sample.ipynb**: A sample Jupyter notebook for project reference.

### 2. `sql` Folder
This folder holds SQL scripts and resources for data queries:
- **BCAN Property Analysis SQL Statements.pdf**: Documentation of SQL queries used in the project.
- **Building Age Group_BCAN.sql**: SQL script for analyzing data by building age groups.
- **Dynamic Filter_BCAN.sql**: SQL script for implementing dynamic filters.
- **Merged_cleaned_query.sql**: Query script for merged and cleaned data.
- **Neighborhoods_BCAN.sql**: SQL script for neighborhood-level analysis.
- **Property Type Group_BCAN.sql**: SQL script for grouping property types.
- **data_scrub.sql**: Script for data cleaning and scrubbing.
- **sample.sql**: A sample SQL script for reference.

### 3. `utils` Folder
This folder includes utility files required for project execution:
- **BU-20240120.dbp**: DBeaver project configuration file.
- **cds-ds-594-d7b0a649a5bf.json**: Configuration file for BigQuery connection.
- **requirements.txt**: List of Python libraries needed for the project.

### 4. `visualizations` Folder
This folder contains visualizations and dashboard files:
- **BCAN Property Analysis Workbook.twb**: Tableau workbook for property analysis.
- **Final Visualizations_GHG Emissions Analysis by Categories.twb**: Finalized Tableau workbook for GHG emissions analysis.
- **PropertyScorecard.twb**: Tableau workbook for property scorecards.
- **Revised Trend Dashboard_Jaejoong Kim.png**: PNG image of a revised trend dashboard.
- **sample.pbix**: A sample Power BI file.
- **sample.twb**: A sample Tableau workbook.
- **total_GHG_emissions_by_building_age.png**: Visualization of total GHG emissions by building age.
- **total_GHG_emissions_by_neighborhood.png**: Visualization of total GHG emissions by neighborhood.
- **total_GHG_emissions_by_property_type.png**: Visualization of total GHG emissions by property type.
- **gitignore**: Specifies files and directories ignored by Git.

---

### Navigating the Repository
1. Clone the repository using the command:
   ```bash
   git clone <url_for_git_repository>
   ```
2. Navigate through the directories (`analysis`, `sql`, `utils`, `visualizations`) to access relevant files.
3. Open Jupyter notebooks in the `analysis` folder for data analysis.
4. Use SQL scripts in the `sql` folder for querying the database.
5. Refer to the Tableau workbooks and Power BI files for data visualization in the `visualizations` folder.

For any issues or inquiries, please open an issue in this repository.

---
