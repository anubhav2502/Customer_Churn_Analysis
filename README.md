# Customer Churn Analysis

## Project Overview
This project analyzes factors contributing to customer churn, with a specific focus on payment methods, contract types, and customer tenure. The goal is to identify which factors have the greatest influence on churn, providing insights that can be leveraged to improve customer retention strategies.

## Objective
The primary objective of this analysis is to investigate customer churn patterns to:
- Understand the impact of contract types and payment methods on churn rates.
- Explore how tenure influences customer retention.
- Identify key areas for targeted customer retention strategies.

## Key Insights & Findings
### 1. Contract Type and Churn
- **Month-to-Month Contracts**: Churn rate is **42%**, indicating a higher risk of customer loss compared to long-term contracts.
- **One-Year Contracts**: Churn rate drops to **11%**, highlighting a positive retention effect.
- **Two-Year Contracts**: The churn rate is only **3%**, showing the strongest retention rate for long-term contracts.
- **Recommendation**: Encourage customers to commit to longer contracts through incentives.

### 2. Payment Methods and Churn
- **Electronic Checks**: Customers using this method exhibit a high churn rate of **45%**.
- **Credit Cards, Bank Transfers, Mailed Checks**: These methods show lower churn rates, averaging between **15-18%**.
- **Recommendation**: Encourage customers to switch to more secure and reliable payment methods to reduce churn.

### 3. Churn by Tenure
- **First-Year Customers**: Churn rate is **50%**, indicating the importance of early engagement.
- **1-3 Years Tenure**: The churn rate decreases to **35%**.
- **More than 3 Years**: Churn rate further declines to **15%**, suggesting customer loyalty increases with tenure.
- **Recommendation**: Focus on improving customer experience during the initial year to enhance retention.

### 4. Churn by Internet Service Type
- **Fiber Optic Customers**: Churn rate is **30%**, possibly due to service quality issues or increased competition.
- **DSL Customers**: Churn rate is lower at **20%**.
- **Recommendation**: Address satisfaction with service speed and reliability to retain fiber optic users.

### 5. Senior Citizens and Churn
- **Senior Citizens (65+)**: Churn rate is **41%**, significantly higher than the **26%** churn rate for non-senior citizens.
- **Recommendation**: Develop targeted retention programs for senior customers.

## Visualizations & Data Insights
- **Bar Charts & Line Graphs**: These visualizations provide a clear representation of churn rates across various factors like contract type, payment methods, and customer tenure.
- **Churn Distribution**:
  - **Payment Methods**: 45% churn for electronic check users, 15% for credit card users.
  - **Contract Types**: 42% churn for month-to-month contracts, 11% for yearly contracts, and 3% for two-year contracts.
  - **Tenure**: 50% churn in the first year, dropping to 15% after three years.

## Recommendations
- **Promote Long-Term Contracts**: Offer incentives to encourage customers to choose one- or two-year contracts.
- **Address Payment Method Issues**: Implement initiatives to transition customers from electronic checks to more reliable payment methods.
- **Enhance Early Engagement**: Focus on improving customer experience during the first year to mitigate the high churn rate.
- **Senior Citizen Retention Programs**: Develop personalized offers or assistance programs to retain senior customers.

## Technologies Used
- Python (for data analysis and visualization)
- Pandas, NumPy (for data manipulation)
- Matplotlib, Seaborn (for creating visualizations)
- Jupyter Notebook

## Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/anubhav2502/customer-churn-analysis.git
   ```
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the analysis notebook in Jupyter:
   ```bash
   jupyter notebook churn_analysis.ipynb
   ```
   
