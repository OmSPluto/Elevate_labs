# Netflix Data Cleaning

This script cleans the raw Netflix dataset for analysis.

1. Load data from `Netflix_data.xlsx`.
2. Clean column names (lowercase, underscores, no special characters).
3. Fill missing values in `country` and `rating`.
4. Drop rows missing `title` or `type`.
5. Remove duplicate records.
6. Standardize text fields.
7. Parse and extract year/month from `date_added`.
8. Clean and split `duration` into numeric and type.
9. Remove outliers from `duration_num`.
10. Save cleaned data to `cleaned_netflix_data.xlsx`.
