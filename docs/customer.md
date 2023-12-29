**Table 1: COPY_SAMPLE.TPCH_SF1.CUSTOMER** (Stores customer information)

This table contains the information of customers who have purchased products.

- C_CUSTKEY NUMBER(38,0) - Unique identifier for customers
- C_NAME VARCHAR(25) - Name of the customer
- C_ADDRESS VARCHAR(40) - Physical address of the customer
- C_NATIONKEY NUMBER(38,0) [Foreign Key - NATION(N_NATIONKEY)] - Nation of the customer
- C_PHONE VARCHAR(15) - Phone number of the customer
- C_ACCTBAL NUMBER(12,2) - Account balance of the customer
- C_MKTSEGMENT VARCHAR(10) - Market segment of the customer
- C_COMMENT VARCHAR(117) - Additional information about the customer