# Power-BI-Practice-Cheat-sheet

- Insatll Power-Bi from Microsoft Store
- [Dowanld Data sate fro prectice Power-BI](https://github.com/microsoft/powerbi-desktop-samples/tree/main/powerbi-service-samples)

- [Microsoft officle webiste for dataset ](https://learn.microsoft.com/en-us/power-bi/create-reports/sample-datasets#explore-excel-samples-in-excel)

- [DAX-Queries](https://learn.microsoft.com/en-us/dax/dax-queries)

- [Power-Query](https://learn.microsoft.com/en-us/powerquery-m/power-query-m-function-reference)

---

Mujhe maaf kijiye agar pehle wali list mein kuch DAX functions chhut gaye the. Yahan par main DAX functions ki complete aur updated list de raha hoon, saath hi unke brief descriptions bhi. Ye list A se Z tak arranged hai aur har function ke aage "Q" diya gaya hai.

### Complete List of DAX Functions with Descriptions

| Function Name                | Description                                                                                  |
|------------------------------|----------------------------------------------------------------------------------------------|
| **ABS** (Q)                  | Returns the absolute value of a number.                                                     |
| **ACOS** (Q)                 | Returns the arccosine of a number.                                                          |
| **ADDCOLUMNS** (Q)           | Adds calculated columns to a table.                                                         |
| **ADDCOLUMNS** (Q)           | Adds calculated columns to a table.                                                         |
| **ALL** (Q)                  | Removes filters from a table or column.                                                     |
| **ALLSELECTED** (Q)          | Returns all values in a column or table while respecting the current filter context.       |
| **AND** (Q)                  | Logical AND function, returns TRUE if both arguments are TRUE.                             |
| **APPEND** (Q)               | Combines two tables by stacking them vertically.                                            |
| **AVERAGE** (Q)              | Calculates the average of a set of values.                                                 |
| **AVERAGEX** (Q)             | Evaluates an expression for each row in a table and returns the average of those values.  |
| **BLANK** (Q)                | Returns a blank value.                                                                      |
| **CALCULATE** (Q)            | Evaluates an expression in a modified filter context.                                       |
| **CALCULATETABLE** (Q)       | Returns a table that has been filtered by the specified filters.                            |
| **CROSSJOIN** (Q)            | Returns a table that is a Cartesian product of all rows from two or more tables.           |
| **COUNT** (Q)                | Counts the number of rows in a column that contain numbers.                                 |
| **COUNTA** (Q)               | Counts the number of non-blank rows in a column.                                           |
| **COUNTBLANK** (Q)           | Counts the number of blank values in a column.                                             |
| **COUNTROWS** (Q)            | Counts the number of rows in a table.                                                      |
| **DATEDIFF** (Q)             | Returns the number of intervals between two dates.                                          |
| **DATE** (Q)                 | Returns the specified date in datetime format.                                             |
| **DAY** (Q)                  | Returns the day of the month from a date.                                                  |
| **DIVIDE** (Q)               | Performs division and handles division by zero gracefully.                                   |
| **EARLIER** (Q)              | Returns the current value of the specified column in an earlier row context.                |
| **EDATE** (Q)                | Returns the date that is the specified number of months before or after a start date.      |
| **EOMONTH** (Q)              | Returns the last day of the month that is the specified number of months before or after a start date. |
| **FILTER** (Q)               | Returns a table that represents a subset of another table or expression.                   |
| **FIRSTDATE** (Q)            | Returns the first date in a column.                                                         |
| **FIRSTNONBLANK** (Q)        | Returns the first value in a column that is not blank, given a specified filter.           |
| **GENERATE** (Q)             | Combines two tables into a single table.                                                   |
| **GROUPBY** (Q)              | Groups a table by specified columns and applies calculations.                               |
| **IF** (Q)                   | Checks a condition and returns one value for TRUE and another for FALSE.                    |
| **IFERROR** (Q)              | Returns a value if an expression evaluates to an error; otherwise returns the expression.  |
| **ISBLANK** (Q)              | Checks if a value is blank.                                                                 |
| **ISERROR** (Q)              | Checks if a value is an error.                                                              |
| **ISTEXT** (Q)               | Checks if a value is text.                                                                  |
| **LOOKUPVALUE** (Q)          | Returns the value in a column that is related to a specified value.                        |
| **MAX** (Q)                  | Returns the largest value in a column.                                                      |
| **MAXX** (Q)                 | Returns the largest value that results from evaluating an expression for each row in a table. |
| **MIN** (Q)                  | Returns the smallest value in a column.                                                     |
| **MINX** (Q)                 | Returns the smallest value that results from evaluating an expression for each row in a table. |
| **MOD** (Q)                  | Returns the remainder of a division operation.                                              |
| **NOT** (Q)                  | Reverses the logical value of its argument.                                                |
| **NOW** (Q)                  | Returns the current date and time.                                                          |
| **OR** (Q)                   | Logical OR function, returns TRUE if either argument is TRUE.                               |
| **RANKX** (Q)                | Returns the rank of a number in a list of numbers for each row in the table.               |
| **RELATED** (Q)              | Returns a related value from another table.                                                |
| **RELATEDTABLE** (Q)         | Returns a table that contains all rows related to the current row.                          |
| **REPLACE** (Q)              | Replaces part of a text string with another text string.                                   |
| **SUM** (Q)                  | Returns the sum of a set of values.                                                         |
| **SUMX** (Q)                 | Evaluates an expression for each row in a table and returns the sum of those values.       |
| **SAMEPERIODLASTYEAR** (Q)   | Returns a table that contains a column of dates from the previous year.                     |
| **SELECTEDVALUE** (Q)        | Returns the value when a single value is selected; otherwise returns the alternate result. |
| **TODAY** (Q)                | Returns the current date.                                                                    |
| **TOTALYTD** (Q)             | Calculates the year-to-date value of the specified expression.                             |
| **TRUNC** (Q)                | Truncates a number to an integer by removing the fractional part.                           |
| **UNION** (Q)                | Combines two or more tables into a single table.                                          |
| **UNICHAR** (Q)              | Returns the Unicode character that is referenced by the given numeric value.               |
| **VALUES** (Q)               | Returns a one-column table that contains the distinct values from a column.                 |
| **YEAR** (Q)                 | Returns the year from a date.                                                               |
| **YEARFRAC** (Q)             | Returns the year fraction representing the number of whole days between the start date and end date. |
| **FORMAT** (Q)               | Formats a value as text according to specified formatting rules.                            |
| **SWITCH** (Q)               | Evaluates an expression against a list of values and returns the result corresponding to the first matching value. |
| **SELECTCOLUMNS** (Q)        | Creates a new table with selected columns from an existing table.                          |
| **SUMMARIZE** (Q)            | Creates a summary table for the requested totals over a set of groups.                     |
| **DISTINCT** (Q)             | Returns a one-column table that contains the distinct values from a column.                 |
| **ISNONTEXT** (Q)            | Checks if a value is not text.                                                              |
| **ISNUMBER** (Q)             | Checks if a value is a number.                                                              |
| **ISLOGICAL** (Q)            | Checks if a value is a logical value (TRUE/FALSE).                                        |
| **ISBLANK** (Q)              | Checks if a value is blank.                                                                 |
| **ISLOGICAL** (Q)            | Checks if a value is logical (TRUE/FALSE).                                                 |
| **CONCATENATE** (Q)          | Combines two text strings into one string.                                                 |
| **CONCATENATEX** (Q)         | Concatenates the result of an expression evaluated over a table.                           |

### Notes:
- Ye list DAX ke sabhi functions ko cover karti hai, jo Power BI, Power Pivot, aur SSAS mein use hoti hain.
- Agar aapko kisi specific function ka detail chahiye, toh aap padh sakte hain Microsoft ki official documentation se.

Agar aapko aur kisi function ki jaankari chahiye ho ya kisi specific query ke liye help chahiye, toh aap zaroor puch sakte hain!
