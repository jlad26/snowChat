**Table 4: COPY_SAMPLE.TPCH_SF1.ORDERS** (Stores order information)

This table contains information about orders placed by customers, including the date and total amount of each order.

- O_ORDERKEY NUMBER(38,0) - Unique identifier for orders
- O_CUSTKEY NUMBER(38,0) [Foreign Key - CUSTOMER(C_CUSTKEY)] - Customer who placed the order
- O_ORDERSTATUS VARCHAR(1) - Status of the order
- O_TOTALPRICE NUMBER(12,2) - Total price of the order
- O_ORDERDATE DATE - Date the order was placed
- O_ORDERPRIORITY VARCHAR(15) - Priority of the order
- O_CLERK VARCHAR(15) - Clerk who processed the order
- O_SHIPPRIORITY NUMBER(38,0) - Priority of the order for shipping
- O_COMMENT VARCHAR(79) - Additional information about the order