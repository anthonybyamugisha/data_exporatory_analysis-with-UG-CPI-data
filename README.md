# Uganda Economic Data Analysis Portfolio

A comprehensive data analysis project showcasing Python proficiency and analytical skills using real-world economic data from Uganda. This project demonstrates expertise in data manipulation, statistical analysis, and visualization techniques.

## Project Overview

This portfolio project analyzes Uganda's Consumer Price Index (CPI) data from 2020-2023, demonstrating advanced data science techniques including data wrangling, time series analysis, and statistical modeling. The project showcases skills in Python, pandas, matplotlib, and statistical analysis.

## Key Analysis Components

### 1. Economic Data Wrangling (E1-E5)
- **Data Loading & Exploration**: Successfully loaded and explored Uganda's CPI dataset from Excel format
- **Data Transformation**: Converted wide-format economic data to long-format for time series analysis using pandas melt operations
- **Date Processing**: Handled complex date transformations converting abbreviated month-year formats (e.g., 'dec-20') to proper datetime objects
- **Segmentation Analysis**: Filtered and segmented CPI indicators into specific categories:
  - All Items CPI (CPI_16 and CPI_09)
  - Core CPI (CPI_CORE_16 and CPI_CORE_09)
  - Food CPI (CPI_FOOD_16 and CPI_FOOD_09)
  - Energy, Fuel & Utilities CPI (CPI_EFU_16 and CPI_EFU_09)
- **Missing Data Treatment**: Implemented median imputation strategies grouped by indicator codes to handle missing values

### 2. Statistical Analysis & Modeling
- **Time Series Analysis**: Processed monthly economic indicators spanning multiple years
- **Statistical Imputation**: Applied group-wise median imputation for robust missing data handling
- **Comparative Analysis**: Segmented economic indicators for comparative performance analysis

### 3. Technical Skills Demonstrated
- Advanced pandas operations (melt, groupby, transform)
- Time series data processing
- Data cleaning and preprocessing
- Statistical analysis techniques
- Economic data interpretation

## Technical Implementation

Built using Python with:
- **pandas**: For data manipulation and analysis
- **numpy**: For numerical computations
- **matplotlib**: For data visualization
- **scipy**: For scientific computing

## Data Sources

- Uganda Consumer Price Index trends from 2020-2023 (Excel format)
- Real-world economic indicators including various CPI categories
- Monthly economic data spanning multiple years

## Portfolio Value

This project demonstrates:
- **Real-world data handling**: Working with authentic economic datasets
- **Advanced data manipulation**: Complex transformations and cleaning techniques
- **Statistical rigor**: Proper handling of missing data and group-wise operations
- **Domain knowledge**: Understanding of economic indicators and time series
- **Technical proficiency**: Advanced Python and pandas skills

## Use Cases

Ideal for showcasing:
- Data science proficiency
- Economic data analysis capabilities
- Python programming skills
- Statistical analysis expertise
- Real-world problem solving

## Repository Structure

- `DSA_2026_Entry.ipynb` - Complete analysis notebook
- `data/` - Raw data files
- `README.md` - This portfolio documentation

## Reproducibility

To reproduce the analysis:
1. Install required packages: `pip install pandas numpy matplotlib scipy`
2. Run the notebook: `jupyter notebook DSA_2026_Entry.ipynb`

## About the Analysis

This analysis was created as part of the Data Science Africa 2026 Summer School entry challenge, demonstrating practical application of data science skills to real-world economic data from Uganda.