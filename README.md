# Economic Indicator Analysis 2020

## 1. Project Overview

This repository contains the submission for Part A of the Data Analytics in Action module. The project focuses on analyzing economic indicators from the year 2020, providing insights related to life expectancy, GDP per capita, and other factors. The analysis is aimed at assisting a think tank organization advising the UN on public policy.

### Key Focus:
- Life expectancy at birth across countries
- Relationships between life expectancy and other economic indicators
- Regression analysis for predictive modeling

## 2. Files in this Repository

- `A_report.pdf`: The final statistical analysis and results report.
- `A_code.ipynb`: The Python notebook containing all the code for data analysis, hypothesis testing, and regression modeling.

## 3. Instructions for Running the Code

To run the Python notebook (`A_code.ipynb`), make sure you have Python installed along with the necessary libraries:
- `pandas`
- `matplotlib`
- `seaborn`
- `numpy`
- `scipy`
- `statsmodels`

### Steps:
1. Install the necessary packages using:
   ```bash
   pip install pandas matplotlib seaborn numpy scipy statsmodels
   ```
2. Open the `A_hgwc71.ipynb` notebook in Jupyter and run the cells sequentially to generate the outputs. Alternatively, the Python file can be run directly if preferred.

### Expected Outputs:
- Descriptive statistics and visualizations for life expectancy across countries and continents.
- Hypothesis testing results on the global average life expectancy.
- Simple linear regression model between GDP per capita and life expectancy.
- Multiple regression model considering several economic indicators.

## 4. Analysis Overview

### 4.1 Life Expectancy Analysis
- The global average life expectancy was calculated at **72.67 years**.
- Life expectancy varied significantly across continents, with **Europe** having the highest average and **Africa** the lowest.
- The distribution of life expectancy showed a negative skew, indicating higher life expectancy in some regions.

### 4.2 Hypothesis Testing
- A t-test was performed to verify if the average life expectancy is 70 years.
- The test rejected the null hypothesis, confirming that the global average life expectancy significantly differs from 70 years (p-value < 0.01).

### 4.3 Simple Regression
- A strong positive correlation (0.62) was found between GDP per capita and life expectancy.
- The regression model suggests that **38.4%** of the variability in life expectancy can be explained by GDP per capita, though other factors likely play a role.

### 4.4 Multiple Regression
- Additional variables like healthcare spending and population were included in a multiple regression model.
- The adjusted R-squared value increased to **0.43**, with healthcare spending per capita being a significant predictor of life expectancy alongside GDP per capita.

## 5. Conclusion

This analysis provides insights into how various economic factors influence life expectancy across countries, emphasizing the role of healthcare spending and GDP per capita. The models provide a foundation for further investigation into global health and economic disparities.

## 6. License

This project is for academic purposes only as part of the COMP41915 Data Analytics in Action module.
