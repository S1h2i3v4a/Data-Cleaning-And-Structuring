 

## Data Cleaning Issues and Solutions

### 1. Missing Data Problem

**Issue:**
Some records contained missing (`null`/empty) values, which could affect data analysis and model performance.

**Solution:**
Missing values were replaced with `None` (or an appropriate placeholder value) to handle incomplete records consistently.

 
---

### 2. Inconsistent Data Format

**Issue:**
Data was stored in different formats (e.g., different date formats, text casing, naming conventions), causing inconsistency.

**Solution:**
All values were converted into a single standardized format to ensure consistency across the dataset.

 
---

### 3. Duplicate Data Problem

**Issue:**
The dataset contained duplicate records, which could lead to inaccurate analysis.

**Solution:**
Duplicate entries were removed by keeping only unique values. A `set` data structure was used to identify unique records.

 

---

### Summary

| Problem             | Solution                                              |
| ------------------- | ----------------------------------------------------- |
| Missing Values      | Filled missing values with `None`                     |
| Inconsistent Format | Standardized data into a consistent format            |
| Duplicate Records   | Removed duplicates using `set` or `drop_duplicates()` |

This data cleaning process improved the dataset's quality, consistency, and reliability for further analysis.
