#  SQL Data Cleaning - Tech Layoffs Dataset

A beginner-friendly MySQL project that cleans a real-world tech layoffs dataset.
Covers duplicate removal, data standardization, null handling, and column cleanup
using CTEs, window functions, self-joins, and ALTER TABLE.

## Steps
1. **Remove Duplicates** - ROW_NUMBER() + staging table pattern
2. **Standardize Data** - TRIM, LIKE, STR_TO_DATE, date type conversion
3. **Handle Nulls** - self-join to fill missing industries, drop useless rows
4. **Cleanup** - drop the helper `row_num` column

## Tools
- MySQL 8.0+
- Dataset: `layoffs.csv`

## How to Run
1. Import `layoffs.csv` into a MySQL database
2. Run `Data_cleaning_project_fixed.sql`
3. Query `layoffs_staging2` for the clean data
```
