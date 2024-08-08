# COVID-19 Exploratory Data Analysis (EDA) Project

## Project Overview

This project involves an exploratory data analysis (EDA) of COVID-19 case data across various countries and WHO regions. The primary objective is to uncover trends, patterns, and insights that can inform public health interventions and policy decisions.

## Dataset

- **Name:** `country_wise_latest.csv`
- **Source:** [Kaggle - COVID-19 Data Statistics](https://www.kaggle.com/datasets/armanmanteghi/covid-19-data-statistics-sql/data)
- **Description:** This dataset contains the latest COVID-19 statistics, including the number of confirmed cases, deaths, recoveries, and other key metrics for countries around the world.

## Key Columns

- **Country/Region:** Name of the country or region.
- **Confirmed:** Total confirmed COVID-19 cases.
- **Deaths:** Total COVID-19 related deaths.
- **Recovered:** Total number of recoveries.
- **Active:** Current active cases.
- **New_cases:** Newly reported cases.
- **New_deaths:** Newly reported deaths.
- **New_recovered:** Newly recovered cases.
- **Deaths/100_Cases:** Deaths per 100 confirmed cases.
- **Recovered/100_Cases:** Recoveries per 100 confirmed cases.
- **Deaths/100_Recovered:** Deaths per 100 recovered cases.
- **Confirmed_last_week:** Confirmed cases reported in the last week.
- **1_week_change:** Change in confirmed cases over the past week.
- **1_week_%_increase:** Percentage increase in cases over the past week.
- **WHO_Region:** WHO region classification.

## Project Structure

- **COVID_19_EDA_PROJECT.ipynb:** Jupyter Notebook containing the entire exploratory data analysis, including data loading, cleaning, visualization, and insights.

## Exploratory Data Analysis (EDA)

### 1. Introduction

- **Objective:** Analyze and visualize COVID-19 data to uncover trends, patterns, and insights across different countries and WHO regions.

### 2. Data Cleaning and Preparation

- **Loading Data:** The dataset was loaded using pandas, and initial inspections were performed to understand its structure.
- **Data Cleaning:** Handled infinite values, replaced missing values, and renamed columns for consistency.

### 3. Descriptive Statistics

- **Summary Statistics:** Provided key statistics for confirmed cases, deaths, recovered cases, and new cases.
- **Data Types:** Verified numerical and categorical columns.

### 4. Univariate Analysis

- **Distribution of Confirmed Cases:** Histogram visualization.
- **Distribution of Deaths:** Histogram visualization.

### 5. Bivariate Analysis

- **Confirmed Cases vs. Deaths:** Scatter plot showing the relationship between confirmed cases and deaths.
- **New Cases by WHO Region:** Box plot showing new cases across WHO regions.

### 6. Pairwise Relationships

- **Pairplot:** Visualized relationships between multiple numerical features.

### 7. Correlation Analysis

- **Correlation Matrix:** Heatmap displaying correlations between numerical features.

### 8. Aggregated Data Analysis

- **Total Cases and Rates:** Calculated total confirmed cases, deaths, recoveries, death rate, and recovery rate.
- **Top 10 Countries by Confirmed Cases:** Listed countries with the highest confirmed cases.

### 9. Regional Analysis

- **Confirmed Cases by WHO Region:** Bar plot visualization.
- **Deaths by WHO Region:** Bar plot visualization.
- **Recovered Cases by WHO Region:** Bar plot visualization.

### 10. Advanced Metrics

- **Death Rate by Country:** Calculated and visualized the top 10 countries with the highest death rates.
- **Recovery Rate by Country:** Calculated and visualized the top 10 countries with the highest recovery rates.

### 11. Conclusion

- **Key Insights:** High correlation between confirmed cases and deaths, significant regional differences, and varied death rates.
- **Recommendations:** Target high-risk regions, strengthen healthcare systems, promote regional collaboration, continuous monitoring, and enhance public health communication.

## Requirements

- Python 3.x
- Jupyter Notebook
- Pandas
- NumPy
- Seaborn
- Matplotlib

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/COVID_19_EDA_PROJECT.git
   ```

2. Navigate to the project directory:
   ```bash
   cd COVID_19_EDA_PROJECT
   ```

3. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```

4. Open the Jupyter Notebook:
   ```bash
   jupyter notebook COVID_19_EDA_PROJECT.ipynb
   ```

## Results

The analysis provides a detailed view of COVID-19's impact across the globe, highlighting key areas for public health focus and potential policy intervention.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgements

- [Kaggle](https://www.kaggle.com/) for providing the dataset.
- The global health community for their tireless work during the COVID-19 pandemic.

