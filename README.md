
- **1_zafer_cleaning.ipynb**  
  Initial data cleaning. Tasks include:
  - Importing raw data
  - Removing duplicates
  - Converting data types (e.g., dates, numeric columns)
  - Standardizing column names

- **2_zafer_missing_value_filling.ipynb**  
  Part 1 of missing‐value handling. Tasks include:
  - Identifying columns with missing values
  - Documenting “prima facie” observations about NaNs
  - Exploring unique values in each column to detect typos or invalid entries
  - Establishing a column‐priority order for imputation

- **3_zafer_missing_value_2.ipynb**  
  Part 2 of missing‐value handling. Tasks include:
  - Executing realistic imputations on high‐priority columns
  - Using imputed columns as references for filling remaining gaps
  - Verifying and validating imputed values

- **4_zafer_outlier.ipynb**  
  Outlier detection and column pruning. Tasks include:
  - Visualizing distributions (histograms, box plots)
  - Defining context‐aware outlier thresholds (e.g., mileage, age)
  - Removing or capping outliers
  - Evaluating whether to drop low‐utility or high‐NaN columns

- **5_zafer_dummy_hazirlik_.ipynb**  
  Final preprocessing and dummy encoding. Tasks include:
  - Converting categorical features into numeric representations (one‐hot, frequency, or target encoding)
  - Verifying final feature matrix
  - Exporting the cleaned, dummy‐encoded dataset

- **final_scout_dummy_zafer.csv**  
  The final output: a fully cleaned, imputed, and dummy‐encoded CSV ready for downstream modeling.

## How to Use

1. **Clone this repository**  
   ```bash
   git clone https://github.com/zaferyildirim-1/auto_scout_zafer.git
   cd auto_scout_zafer
