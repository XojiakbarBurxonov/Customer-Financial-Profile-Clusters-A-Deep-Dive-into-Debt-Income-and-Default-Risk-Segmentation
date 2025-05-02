# Customer-Financial-Profile-Clusters-A-Deep-Dive-into-Debt-Income-and-Default-Risk-Segmentation
This repository showcases an analysis of customer financial profiles through clustering. It leverages key variables—such as age, years employed, income, credit card debt, other debt, default status, and debt-to-income ratio—to segment customers into three distinct clusters:
### 1. Understanding the Columns:
  - `Customer Id`: Unique identifier for customers.
  - `Age`: Age of the customer.
  - `Edu`: Level of education (possibly categorical but represented numerically).
  - `Years Employed`: Number of years the customer has been employed.
  - `Income`: Customer's annual income.
  - `Card Debt`: Outstanding credit card debt.
  - `Other Debt`: Other types of debts the customer has.
  - `Defaulted`: Whether the customer has defaulted on debt (0 = No, 1 = Yes).
  - `DebtIncomeRatio`: Ratio of total debt to income.

### 2. Summary of the Clusters (Rows):
#### Cluster 0
    Age: ~34.64 years
    Years Employed: ~8.22 years
    Income: ~$37.93K
    Card Debt: ~$0.82K
    Other Debt: ~$1.76K
    Default Rate: Very low (0.007 or ~0.7%)
    Debt-to-Income Ratio: Low (~7.26%)
- Interpretation: A relatively young group with moderate income, low card debt, and very low default risk.
#### Cluster 1
    Age: ~43.48 years
    Years Employed: ~17.78 years
    Income: ~$107.82K
    Card Debt: ~$4.56K
    Other Debt: ~$8.49K
    Default Rate: Moderate (~21.2%)
    Debt-to-Income Ratio: Moderate (~14.1%)
➡ Interpretation: Older customers with high income but carrying significantly more debt. They have a higher default rate, possibly due to larger financial obligations.
#### Cluster 2
    Age: ~30.92 years
    Years Employed: ~3.88 years
    Income: ~$31.66K
    Card Debt: ~$1.66K
    Other Debt: ~$3.09K
    Default Rate: Very High (~84.6%)
    Debt-to-Income Ratio: Very High (~15.03%)
➡ Interpretation: The youngest group, with the lowest income and highest default rate. They have a high debt-to-income ratio, making them more financially vulnerable.

### 3. Key Insights:

`Cluster 0` is financially stable, with low debt and almost no default risk.
`Cluster 1` has higher income but also higher debt and a moderate risk of default.
`Cluster 2` is the riskiest group, with low income, high debt, and an extremely high default rate (~85%).


The repository includes data preprocessing, clustering implementation, and visualization scripts to help identify and understand these distinct customer segments. This analysis can inform targeted financial strategies and risk management decision
