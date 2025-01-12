# Crowdfunding Analysis

## Summary
This project involves the analysis and updating of a crowdfunding database using Python. The goal is to perform data operations such as adding new entries, updating existing ones, and executing exploratory data analysis to gain insights from the data.

## Objectives
- Import data from Excel files.
- Perform various update operations on the database.
- Conduct exploratory data analysis to identify patterns and trends.
- Utilize Python libraries like Pandas and NumPy for data operations and analysis.

## Data Description
The dataset includes:
- **Crowdfunding Data**: Information about various crowdfunding campaigns, including categories and subcategories.
- **Contacts Data**: Information about contacts related to the campaigns.

## Scripts Included
1. **Categories and Subcategories Script**: 
   - Reads data from `crowdfunding.xlsx`.
   - Creates DataFrames for categories and subcategories.
   - Exports DataFrames to `category.csv` and `subcategory.csv`.

2. **Campaigns and Contacts Script**: 
   - Reads data from `crowdfunding.xlsx` and `contacts.xlsx`.
   - Creates and transforms DataFrames for campaigns and contacts.
   - Exports DataFrames to `campaign.csv` and `contacts.csv`.

## Requirements
- Python 3.10
- pandas module
- numpy module
- openpyxl module
- json module

## Instructions

### Categories and Subcategories Script
1. Ensure the necessary libraries are installed.
2. Place the `crowdfunding.xlsx` file in the `Resources` folder.
3. Run the script to create `category.csv` and `subcategory.csv`.

### Campaigns and Contacts Script
1. Ensure the necessary libraries are installed.
2. Place the `crowdfunding.xlsx` and `contacts.xlsx` files in the `Resources` folder.
3. Run the script to create `campaign.csv` and `contacts.csv`.

## Contributions
Contributions are welcome. If you have suggestions or improvements, please open an issue or submit a pull request.
