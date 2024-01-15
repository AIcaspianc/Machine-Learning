## Context

Banks incur significant losses due to default in loans. This has led to a tightening up of loan underwriting and has increased loan rejection rates. The need for a better credit risk scoring model is also raised by banks.

The CNK bank has collected customer data for the past few years and wants to build a model to predict if a customer coming to purchase a loan is a good customer (will not default) or a bad customer (will default).


## Data Dictionary

- month - the month of purchase
- credit_amount - amount for which loan is requested
- credit_term - for how long customer wants a loan
- age - age of the customer
- sex - gender of the customer
- education - education level of customer
- product_type - for purchasing what type of product does the customer need a loan (0, 1, 2, 3, 4)
- having_children_flg - if the customer has children or not
- region - customer region category(0, 1, 2)
- income - income of the customer
- family_status - another, married, unmarried
- phone_operator - mobile operator category(0, 1, 2, 3)
- is_client - if the customer wanting to purchase a loan is our client or not
- target - 1-bad customer, 0-good customer
