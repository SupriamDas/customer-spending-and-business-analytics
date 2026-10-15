# Customer Spending & Business Analytics

**Python | Financial Data Analysis | Expenditure Analysis | Business Intelligence | Data Visualisation**

## Project Overview

This project uses Python to analyse customer income, expenditure and purchasing behaviour, with a focus on identifying financial patterns, evaluating spending activity and generating insights to support business decision-making.

The analysis covers 2,240 customer records and examines relationships between income levels, product expenditure, purchasing frequency and customer value. Data cleaning, statistical analysis, feature engineering and visualisation are used to transform raw data into meaningful business information.

The findings are presented through analytical visualisations and a structured report, highlighting expenditure trends, customer spending profiles and opportunities for improved commercial performance.

## Project Objectives

- Analyse income distribution and customer expenditure patterns.
- Evaluate spending across different product categories.
- Examine relationships between income, purchasing frequency and expenditure.
- Identify differences in customer value and spending behaviour.
- Investigate trends, correlations and unusual observations within the data.
- Develop financial and business performance indicators from existing variables.
- Present analytical findings to support business planning and management decisions.

## Tools & Technologies

| Technology | Application |
|---|---|
| Python | Data analysis and processing |
| Pandas | Data cleaning, manipulation and aggregation |
| NumPy | Numerical and statistical calculations |
| Matplotlib & Seaborn | Data visualisation and analytical reporting |
| Scikit-learn | Advanced statistical and analytical techniques |
| Jupyter Notebook | Analysis, documentation and reporting |

## Dataset Overview

The analysis uses the [Customer Personality Analysis dataset](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis), containing financial and behavioural information across 2,240 customer records and 29 variables.

The dataset includes:

- **Income:** Annual customer income.
- **Expenditure:** Spending across multiple product categories.
- **Purchasing activity:** Frequency and methods of purchase.
- **Customer characteristics:** Demographic and household information.
- **Customer relationships:** Registration history and engagement.

The dataset is available under the CC0 Public Domain licence.

## Analysis & Methodology

### Data Preparation & Quality Assessment

The dataset was examined and prepared to improve the reliability of the analysis.

This included:

- Identifying missing and inconsistent values.
- Applying median imputation to missing income observations.
- Investigating unusual values and outliers.
- Reviewing numerical distributions and data quality.
- Preparing 2,236 records for subsequent analysis.

### Income & Expenditure Analysis

Customer income and expenditure were examined to understand spending distributions and purchasing behaviour.

The analysis explored:

- Income distribution across customers.
- Total expenditure across product categories.
- Relationships between income and spending.
- Differences in purchasing frequency and expenditure.
- Spending patterns across customer characteristics.

### Business Performance Indicators

Additional variables were developed to support more detailed analysis.

| Indicator | Purpose |
|---|---|
| Total Spending | Measures combined expenditure across product categories |
| Total Purchases | Measures overall purchasing activity |
| Customer Tenure | Measures the length of the customer relationship |

These indicators provide a clearer view of customer activity, spending levels and customer value.

### Statistical Analysis & Data Visualisation

Descriptive statistics, correlation analysis and visualisations were used to examine relationships between variables and identify meaningful trends.

Advanced analytical techniques were also applied to investigate patterns within the dataset and group customers with similar financial and purchasing characteristics.

The results were used to develop spending profiles and assess differences in customer value.

## Key Findings & Business Insights

### Income and Spending Patterns

The analysis examines how customer income relates to expenditure and purchasing activity, providing insight into differences in spending behaviour across income levels.

### Expenditure by Product Category

Product-level spending analysis highlights differences in expenditure across categories and supports an understanding of customer purchasing preferences.

### Customer Value Analysis

Customer profiles were developed based on expenditure and purchasing behaviour, identifying three broad groups:

| Customer profile | Characteristics |
|---|---|
| High-value customers | Higher expenditure and purchasing activity |
| Regular customers | Moderate spending and purchasing frequency |
| Low-spending customers | Lower overall expenditure and purchasing activity |

These findings support analysis of customer value, purchasing patterns and potential opportunities for improved commercial performance.

### Business Reporting & Decision Support

The analytical results provide a structured basis for:

- Monitoring expenditure and purchasing trends.
- Understanding differences in customer value.
- Evaluating product-category spending patterns.
- Supporting commercial planning and resource allocation decisions.
- Communicating findings through visual reports and statistical summaries.

## Data Visualisations

Selected visualisations from the analysis are available in the [`figures/`](figures/) folder.

The charts illustrate income distributions, expenditure trends, relationships between financial variables and differences in customer purchasing behaviour.

For the complete analysis, see the Python notebook and accompanying report.

## Project Structure

```text
customer-spending-and-business-analytics/
│
├── README.md
├── EDAPROJECT.ipynb
├── Data.pdf
├── marketing_campaign.csv
│
└── figures/
    └── [Analysis visualisations]
```

| File | Description |
|---|---|
| `EDAPROJECT.ipynb` | Python notebook containing the complete data analysis |
| `Data.pdf` | Detailed analytical report and findings |
| `marketing_campaign.csv` | Original dataset |
| `figures/` | Charts and analytical visualisations |

## Running the Project

**1. Clone the repository**

```bash
git clone https://github.com/SupriamDas/customer-spending-and-business-analytics.git
```

**2. Navigate to the project folder**

```bash
cd customer-spending-and-business-analytics
```

**3. Install the required libraries**

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

**4. Launch Jupyter Notebook**

```bash
jupyter notebook
```

Open `EDAPROJECT.ipynb`, ensure the dataset path points to `marketing_campaign.csv`, and run the notebook to reproduce the analysis.

## Conclusion

This project demonstrates the use of Python for financial and business data analysis, combining data preparation, expenditure analysis, statistical investigation and visual reporting.

By examining customer income, spending behaviour and purchasing activity, the analysis provides insights into customer value, expenditure trends and commercial performance.

The project reflects a structured approach to working with numerical data, identifying meaningful relationships and communicating findings to support informed business decisions.

---

## About Me

**Supriam Das**  
Accounting & Finance Graduate | ACCA Part-Qualified (9/13)

Accounting and finance professional with interests in financial analysis, business performance, data analytics and management reporting.

- [LinkedIn](https://www.linkedin.com/in/supriam-das/)
- [GitHub](https://github.com/SupriamDas)

---

**Data Source:** [Customer Personality Analysis — Kaggle](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis)  
**Licence:** CC0 Public Domain
