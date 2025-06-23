🧹 Data Cleaning – Internship Task

This project demonstrates the data cleaning process carried out during my internship using Microsoft Excel. The dataset contains sales data that required cleaning to ensure it was accurate, consistent, and ready for analysis.

 📂 Files

 'sales_data.xlsx' – Raw dataset (before cleaning)
 'salesdata_DataCleaning.xlsx' – Cleaned dataset (after applying all data cleaning steps)

 🧼 Data Cleaning Steps

  1. Standardizing Date Formats

    Affected Columns: `Order Date`, `Delivery Date`
    Action: Converted general format to short date format using:
    Home Tab → Number Pane → Short Date
    Purpos: To maintain consistent date formatting across the dataset.

---

 2. Removing Duplicates

 Method 1: Using Conditional Formatting
  Column: `Order ID`
  Applied conditional formatting to highlight duplicate values with red fill and bold text.
  Manually deleted the highlighted duplicate row(s).

 Method 2: Using Data Tab
  Selected the entire table:
  Data → Remove Duplicates → Select All Columns → OK
  Removed exact duplicate rows automatically.

---

3. Handling Missing Values

Step 1: Identifying Missing Values
  Applied conditional formatting:
  Conditional Formatting → New Rule → Format only cells that contain blanks
  Used red fill to highlight null cells in the `Unit Price` column.

Step 2: Replacing Missing Values

 Option A: Manual Replacement
- Calculated average of `Unit Price` using Excel’s status bar (bottom right).
- Replaced blank cells with the average value.

Option B: Using Descriptive Statistics
 Used Excel’s Data Analysis Toolpak:
    Data → Data Analysis → Descriptive Statistics
     Input Range: Selected `Unit Price` column
     Output: Generated summary including mean, median, min, max
 Filled missing values using the **mean** value obtained.

---

 ✅ Final Result

The final cleaned dataset:
- Has standardized date formats
- Contains no duplicate records
- Has no missing values in key numeric columns

 🛠️ Tools Used

- Microsoft Excel
- Conditional Formatting
- Data Tab Tools (Remove Duplicates, Descriptive Statistics)
- Manual formula-based handling

---
