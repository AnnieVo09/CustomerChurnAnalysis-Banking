# Bank Customer Churn Dataset

## Data Dictionary

### Columns Description:
- **RowNumber**: A sequential record identifier, has no effect on the output.
- **CustomerId**: Unique identifier for a customer, randomly assigned and has no effect on customer churn.
- **Surname**: Customer surname, no impact on customer decision to leave the bank.
- **CreditScore**: Credit score of the customer, higher credit scores correlate with lower churn likelihood.
  - **Excellent**: 800–850
  - **Very Good**: 740–799
  - **Good**: 670–739
  - **Fair**: 580–669
  - **Poor**: 300–579
- **Geography**: Customer’s location, which can influence their decision to leave the bank.
- **Gender**: Gender of the customer, explored to determine if there’s any relationship with churn.
- **Age**: Age of the customer, older customers are generally less likely to leave the bank than younger ones.
- **Tenure**: The number of years the customer has been with the bank. Long-tenure customers are more loyal.
- **Balance**: Customer's account balance, higher balances are an indicator that customers are less likely to leave.
- **NumOfProducts**: Number of products purchased by the customer from the bank.
- **HasCrCard**: Indicates if a customer has a credit card.
  - **1**: Has a credit card
  - **0**: Does not have a credit card
- **IsActiveMember**: Indicates if the customer is an active member of the bank.
  - **1**: Active Member
  - **0**: Inactive Member
- **Estimated Salary**: Customer's estimated salary, those with higher salaries are less likely to leave.
- **Exited**: Indicates whether the customer has left the bank.
  - **0**: Retained customer
  - **1**: Customer has exited
- **Bank DOJ**: The date when the customer joined the bank.

## Data Sources:

The following data assets are utilized for customer data gathering and analysis:
- `ActiveCustomer`
- `Bank_Churn`
- `CreditCard`
- `CustomerInfo`
- `ExitCustomer`
- `Gender`
- `Geography`

## Churn Analysis:

This analysis focuses on understanding the reasons behind customer churn, helping banks identify factors that influence a customer’s decision to leave. Insights from churn analysis can guide the development of loyalty programs and retention strategies, aiding in customer retention and reducing churn rates.

---

This README provides an overview of the dataset structure, key variables, and analysis goals for customer churn.
