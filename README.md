# Analysis of FAO Data: African Nations Food Balance (2014–2018)

## Project Overview

This project provides a detailed analysis of the **Food and Agriculture Organization (FAO)** food balance sheet data for 47 African nations spanning the years 2014 to 2018. The primary objective is to quantify and visualize patterns in food production, consumption, trade (imports/exports), and domestic supply to identify key drivers of food security and economic trade specialization across the continent.

## Dataset

* **Source:** Food and Agriculture Organization (FAO)
* **File:** `FoodBalanceSheets_Africa.csv`
* **Scope:** 47 African countries, 2014–2018
* **Key Variables:**
    * `Area`: Country Name (e.g., Nigeria, Egypt)
    * `Item`: Food Item (e.g., Cereals, Roots and Tubers)
    * `Element`: Measure Type (e.g., Production, Import Quantity, Food supply quantity)
    * `Y2014` through `Y2018`: Quantity measures for each year.

## Analysis Methodology

The analysis was performed using Python (Pandas, Matplotlib, Seaborn) and focused on summing quantities across the five-year period (2014-2018) to identify overall trends.

### Key Analytical Steps:

1.  **Data Preparation:** Loaded the dataset, handled missing values by imputing zeros, and ensured column standardization.
2.  **Trade Analysis:** Identified the top 10 food **Items** and **Areas (Countries)** by total **Import Quantity** and **Export Quantity**.
3.  **Supply Analysis:** Identified the top and bottom countries in terms of total **Production**.

## Key Findings (Summary)

* **Import Dependency:** **Cereals - Excluding Beer** is the largest imported item, highlighting a structural deficit in staple food production.
* **Dietary Staples:** **Cereals, Roots, and Tubers** form the foundational base of the average per capita food supply.
* **Trade Leaders:** **Nigeria, Egypt, and South Africa** dominate both the import and production metrics, underscoring their influence on continental food balance.
* **Export Profile:** African exports are concentrated in raw or semi-processed agricultural commodities, suggesting limited value capture from downstream processing.

## Getting Started

1.  **Install Dependencies:**
    ```bash
    pip install pandas numpy matplotlib seaborn
    ```
2.  **Run the Analysis:** Execute the cells in the `Analysis of FAO data 2014-2018.ipynb` notebook.
