# World Bank Debt Analysis

This repository contains an analysis of world debt data from the World Bank, focusing on the number of distinct countries, the country with the highest debt, and the country with the lowest principal repayments.

## Tasks

1. **Number of Distinct Countries**:
   - Find the number of distinct countries present in the database.
   - Output should be a single row and column, aliased as total_distinct_countries.
   - Save the query as num_distinct_countries.

2. **Country with Highest Debt**:
   - Find the country with the highest amount of debt.
   - Output should contain two columns: country_name and total_debt, with one row.
   - Save the query as highest_debt_country.

3. **Country with Lowest Principal Repayments**:
   - Find the country with the lowest amount of principal repayments, indicated by the "DT.AMT.DLXF.CD" indicator code.
   - Output should contain three columns: country_name, indicator_name, and lowest_repayment, with one row.
   - Save the query as lowest_principal_repayment.

## Data and Tools

The analysis is performed on a dataset of world debt data provided by the World Bank. The queries are written in SQL and can be executed in a PostgreSQL database.

## Conclusion

This repository provides an analysis of world debt data, focusing on the number of distinct countries, the country with the highest debt, and the country with the lowest principal repayments. The queries can be used to gain insights into the global debt landscape and identify countries with significant debt burdens or low repayment rates. These insights can be valuable for policymakers, economists, and researchers interested in understanding and addressing global debt issues.
