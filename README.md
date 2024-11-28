# Animal Species Population Extinction Analysis Project

This project analyzes animal species population data to study the relationship between species at high risk (e.g., endangered/extinct/vulnerable) and those at low risk (e.g., least concerned). Various statistical methods and visualizations have been applied to understand distributions, sampling, and potential relationships between these random variables.

## Table of Contents
- [Dataset Description](#dataset-description)
- [Analysis Performed](#analysis-performed)
- [Code Requirements](#code-requirements)
- [Project Features](#project-features)
- [Results Summary](#results-summary)
- [Contributors](#contributors)

---

## Dataset Description
The project uses **`species.xlsx`**, which contains data on:
1. **Endangered/Extinct/Vulnerable species** - Species at high risk of extinction.
2. **Least Concerned species** - Species at low risk of extinction.

Ensure the dataset is placed in the same directory as the project script for seamless execution.

---

## Analysis Performed
The following analyses were conducted:
1. **Descriptive Statistics**: 
   - Computed mean, standard deviation, count, and minimum values for both random variables.
2. **Distribution Analysis**: 
   - Frequency graphs and joint distribution plots for the random variables.
3. **Sampling Distributions**: 
   - Generated sampling distributions for means and variances using 200 samples of size 10.
4. **Point and Interval Estimates**:
   - Estimated population mean and variance for both random variables.
5. **Regression Analysis**:
   - Explored the relationship between the two random variables.

---

## Code Requirements
To run this project, install the following Python packages:
- `numpy`
- `matplotlib`
- `seaborn`
- `pandas`
- `openpyxl` (for loading `.xlsx` files)

You can install the required libraries using:
```bash
pip install numpy matplotlib seaborn pandas openpyxl
```

---

## Project Features
1. **Descriptive Statistics**:
   - Generates a summary table for both random variables.
2. **Visualization**:
   - Frequency histograms and joint plots using `seaborn`.
3. **Sampling Distributions**:
   - Custom functions to compute sample means and variances.
4. **Point Estimates**:
   - Provides comparison between estimated and true means and variances.
5. **Regression Analysis**:
   - Visualizes the regression line and evaluates the relationship between random variables.

---

## Results Summary
1. **Descriptive Statistics**:
   - The endangered/extinct/vulnerable species show a lower mean but higher variance compared to least concerned species.
2. **Sampling Distributions**:
   - Sampling estimates closely approximate the true population parameters, except for the mean of endangered species.
3. **Regression Analysis**:
   - Limited correlation between the two random variables, indicating that least concerned species are not strongly related to endangered species.

---

## Contributors
- **Mayank Ghritlahre**  
  *Roll Number*: 210010040  

