# Topic 12: DSUM in Excel

## Project Overview
This exercise demonstrates how to use the DSUM database function to calculate total Pinterest impressions based on a category condition.

## Dataset
The `Pin_Data` sheet contains 10 Pinterest pin records with:
- Pin Name
- Category
- Impressions
- Engagement

## Excel Function Practiced
**DSUM**

Syntax:
`=DSUM(database, field, criteria)`

Formula used:
`=DSUM(Pin_Data!A1:D11,"Impressions",A1:A2)`

## Practice Results

| Category | Total Impressions |
|---|---:|
| Kitchen | 383 |
| Beauty | 86 |
| Fashion | 83 |

## Steps Completed
1. Created a Pinterest analytics practice workbook.
2. Entered the sample dataset.
3. Created a criteria range using Category.
4. Used DSUM to calculate total impressions.
5. Changed the criteria to test different categories without rewriting the formula.

## Key Learning
DSUM adds values from a specified database field when records match the criteria range. Changing the criteria allows the same formula to calculate results for different categories.

## Tools Used
- Microsoft Excel
- Pinterest sample analytics data