# README

## Purpose

This code processes and analyzes data from multiple Excel files related to water infrastructure management. It aims to:

1. **Consolidate data:** Extract data from Excel files for different years (2018-2021) and categories (water lines, connections, etc.).
2. **Clean and prepare data:** Remove unnecessary columns, handle missing values, and format data for analysis.
3. **Calculate costs:** Determine the costs associated with different types of water infrastructure work.
4. **Generate insights:** Create visualizations and summaries to understand trends and patterns in the data.
5. **Export data:** Save the processed data in a JSON format for further use.


## Actions Taken

1. **Data Extraction:** Data is loaded from Excel files using the `pandas` library.
2. **Data Cleaning:** Empty columns and rows with missing values are removed. Headers are corrected and data is reorganized.
3. **Cost Calculation:** Costs are calculated based on the type of work and associated cost factors.
4. **Data Transformation:** Data is transformed into dictionaries and lists to prepare for visualization and export.
5. **Data Export:** Data is exported as a JSON file named `data.json`.


## Libraries Used

* `pandas`: For data manipulation and analysis.
* `numpy`: For numerical computations.
* `fuzzywuzzy`: For string matching and comparison.
* `recordlinkage`: For record linkage and deduplication.
* `matplotlib`: For basic plotting and visualization.
* `plotly`: For interactive visualizations.
* `json`: For data serialization.n.
