Week 1 of Carbon Emissions Internship

📁 Project Overview
In this module, I worked with a raw CSV file containing carbon emissions data. The goal was to clean and preprocess this data to make it suitable for downstream analysis. Key tasks included:
- Handling missing values
- Standardizing column formats
- Removing duplicates
- Renaming columns for clarity
- Converting data types where needed
🛠️ Tools & Libraries
- Python 3.x
- Jupyter Notebook
- pandas
- numpy
- matplotlib (optional for quick visual checks)
🧹 Data Cleaning Steps
- Exploration: Loaded the dataset and examined basic statistics and structure.
- Missing Values: Identified null entries and used techniques like imputation or row removal.
- Data Types: Ensured consistency across all columns by converting to appropriate types.
- Duplicates: Removed redundant rows.
- Renaming and Reindexing: Improved column names and index formatting for clarity.
📊 Output
The final cleaned dataset is ready for further statistical analysis, visualization, or machine learning modeling in upcoming weeks.
📌 Directory Structure
Carbon_Emissions_Week-1/
│
├── Carbon_Emissions_Cleaning.ipynb
├── raw_data.csv
├── cleaned_data.csv
└── README.md


🚀 Getting Started
To run the notebook locally:
- Clone the repository.
- Install the required libraries:
pip install pandas numpy matplotlib
- Open the notebook using Jupyter:

Week 2 of the Carbon Emissions Internship

__1. Introduction:__ The notebook explores a carbon emissions dataset to understand trends, correlations, and country-specific differences in CO₂ emissions.

__2. Data Loading and Overview:__

- Libraries used: numpy, pandas, seaborn, matplotlib, statsmodels.
- Data is loaded from `data_cleaned.csv`.
- The notebook prints the shape of the dataset, data types of the columns, the first 5 rows, and descriptive statistics.

__3. Data Visualization:__

- __Global Average CO₂ Emissions per Capita Over Time:__ A line plot shows the trend of global average CO₂ emissions per capita over the years.
- __Total CO₂ Emissions Against Population:__ A line plot illustrates the relationship between total CO₂ emissions and population.
- __Correlation Matrix of All Features:__ A heatmap displays the correlation between all features in the dataset.
- __Pairplot of Selected Features for Chosen Countries:__ A pairplot visualizes the relationships between selected features for a subset of countries.
- __4D Plot:__ A relplot shows the relationship between urban population growth, CO₂ per capita, energy use per capita, and population in urban agglomerations.

__4. Variance Inflation Factor (VIF):__

- VIF is used to check for multicollinearity among the following features: `cereal_yield`, `fdi_perc_gdp`, `gni_per_cap`, `en_per_cap`, `co2_per_cap`, `pop_urb_aggl_perc`, `prot_area_perc`, `gdp`, `pop_growth_perc`, and `urb_pop_growth_perc`.
- The notebook prints the VIF values for each feature.

__5. Country-Specific Analysis:__

- The notebook identifies the unique countries in the dataset.
- It selects the following countries for comparison: `IND`, `USA`, `PAK`, `RUS`, and `NZL`.
- A line plot shows the CO₂ emissions per capita over time for these selected countries.

__6. Outlier Handling:__

- The notebook removes outliers from the country `ARE` before creating the 4D plot.

__7. Conclusion:__ The notebook provides a comprehensive exploration of the carbon emissions dataset, revealing trends, correlations, and country-specific patterns. The visualizations and VIF analysis offer valuable insights into the factors influencing CO₂ emissions.

jupyter notebook data_preparation_week_1.ipynb




