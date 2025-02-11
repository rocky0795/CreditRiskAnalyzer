# Credit Risk Analyser

## Overview

The **Credit Risk Analyser** is a data-driven project aimed at analyzing financial and demographic attributes of loan applicants to assess credit risk. The project involves in-depth data processing, exploratory data analysis (EDA), and machine learning techniques to predict loan default risks.

## Features

- **Data Preprocessing**
  - Handled missing values by dropping high-missing-value columns and imputing others using mean/median.
  - Categorized missing values in key variables such as `OCCUPATION_TYPE`.
  
- **Exploratory Data Analysis (EDA)**
  - Conducted univariate and bivariate analysis to identify key risk indicators.
  - Examined categorical variables like `NAME_CONTRACT_TYPE`, `NAME_TYPE_SUITE`, and `NAME_EDUCATION_TYPE` to assess their impact on repayment behavior.
  - Investigated numerical variables like loan amount distribution and income levels.

- **Outlier Handling**
  - Identified and managed outliers using **Interquartile Range (IQR)** and **Capping Techniques**.

- **Correlation Analysis**
  - Evaluated relationships between financial and demographic features to determine their predictive power in assessing repayment risks.

## Technologies Used

- **Python**
- **Pandas, NumPy** (Data Processing)
- **Matplotlib, Seaborn** (Visualization)
- **Scikit-learn** (Machine Learning)
- **PostgreSQL** (Database Integration)

## Installation

Ensure that you have the required dependencies installed:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn psycopg2
```

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Credit-Risk-Analyser.git
   cd Credit-Risk-Analyser
   ```
2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Project.ipynb
   ```
3. Run the notebook cells sequentially to process data, analyze risks, and make credit predictions.

## Key Insights

- **Higher default risks** were found in applicants with **lower income brackets**.
- **Contract types impact creditworthiness**, with **cash loans posing higher risks**.
- **Education and marital status significantly influence repayment ability**, with individuals having secondary education showing higher default rates.
- **Outliers in financial data affect model accuracy**, requiring effective handling techniques.

## Conclusion

The **Credit Risk Analyser** provides valuable insights for financial institutions to assess and mitigate lending risks. By leveraging demographic and financial data, lenders can enhance loan approval strategies and reduce non-performing assets.

## Contributing

Contributions are welcome! Fork the repository and submit a pull request with improvements.
