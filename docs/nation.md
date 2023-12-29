**Table 2: COPY_SAMPLE.TPCH_SF1.NATION** (Stores nation information)

This table contains information about nations.

- N_NATIONKEY NUMBER(38,0) - Unique identifier for nations
- N_NAME VARCHAR(25) - Name of the nation
- N_REGIONKEY NUMBER(38,0) [Foreign Key - REGION(R_REGIONKEY)] - Region of the nation
- N_COMMENT VARCHAR(152) - Additional information about the nation