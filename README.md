# d2k tech

Dataset Link: [Credit Card Customers](https://www.kaggle.com/datasets/sakshigoyal7/credit-card-customers)

Github link :

```link
https://github.com/shivam1750/d2k_tech.git
```

Requirement installation :

```code
pip install -r requirements.txt
```

#### Dataset Description

- Source: The dataset consists of 10,127 customer records.
- Columns: 23 features capturing demographic, relationship, and transaction data.
- Target Variable:
  - Attrition_Flag: Indicates whether the customer has churned (Attrited Customer) or retained (Existing Customer).

#### Key Features:

```
Customer_Age: Age of the customer.
Gender: Gender of the customer.
Dependent_count: Number of dependents the customer has.
```

`Financial` Attributes:

`Income_Category`: Customer's income range.

`Credit_Limit`: Maximum credit limit available.
Behavioral Metrics:

`Months_on_book`: Number of months the customer has been with the institution.

`Total_Trans_Amt`: Total transaction amount over a defined period.

`Avg_Utilization_Ratio`: Average utilization of the credit limit.

`Months_Inactive_12_mon`: Months the customer was inactive in the last 12 months.

#### Derived Features:

`Avg_Trans_value`: Average transaction value (calculated as Total_Trans_Amt / Total_Trans_Ct).
`Total_Chng_Q4_Q1`: Average change in transaction amount and count between quarters
