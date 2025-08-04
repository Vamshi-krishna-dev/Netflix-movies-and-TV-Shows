## Netflix_movies and Tv shows

This project involve basic data cleaning steps performed on the Netflix_movies and Tv shows

**Steps peroformed**
--> Loaded data sets using pandas
--> Handling Missing Values using isnull() to detect and 'fillna()' or 'dropna()' as needed
--> remove duplicate values using '.drop_duplicates()'
--> Standardize the text values in columns like country and rating
   -  Removed extra spaces.
   - Converted text to consistent casing (e.g., 'title()' or 'upper()').
--> converetade the date formates using "pd.to_datetime()"
--> renamed colume names from lower case to upper case using ".columns.str.strip().str.upper()"
--> **Checked and fixed data types**:
   - Converted 'date_added' to datetime.
   - Extracted numeric values from 'duration'
