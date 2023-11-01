# Shopping cart analysis with PostgreSQL

Data analysis of an e-commerce consists in accumulating data from an online store, extracting trends and key informations, and communicating results. Such kind of study is of prior importance to help decision-makers to improve and develop the store.

This notebook aims to present the analysis of a synthetic dataset on e-commerce shopping. 

**Dataset**

<u>URL:</u> https://www.kaggle.com/datasets/ruchi798/shopping-cart-database

This dataset is provided by Ruchi Bhatia (Carnegie Mellon University) on Kaggle. It consists of four CSV files:
 - *customers.csv*: personal informations on customers such as its name, gender, age, address, etc.
 - *orders.csv*: data on the orders such as the customer, the payment, the order and delivery dates
 - *products.csv*: informations on products such as its name, size, colour, price, etc.
 - *sales.csv*: informations on sales such as the concerned order and product, the price, the quantity, etc. 

**Roadmap**

1. Importing data from CSV files
2. Detailing input data
3. Answering questions:
    - How have sales changed over the past few quarters?
    - What are the customer demographics and preferences?
    - Which products were sold the most in the last month?

**Tools**
- PostgreSQL: Analysis
- Python: 
    - ipython-sql: SQL in Jupyter notebook
    - Pandas, Seaborn: Data visualization
