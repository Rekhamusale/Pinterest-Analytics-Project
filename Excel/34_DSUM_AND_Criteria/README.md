# Topic 14: DSUM with AND Criteria in Excel

## Project Overview
This exercise demonstrates how to use the DSUM database function with AND criteria to calculate Pinterest impressions when multiple conditions must be satisfied.

## Dataset
The `Pin_Data` sheet contains 10 Pinterest pin records with:
- Pin Name
- Category
- Impressions
- Engagement

## Excel Function Practiced
**DSUM with AND criteria**

Formula used:
`=DSUM(Pin_Data!A1:D11,"Impressions",A1:B2)`

## Practice Results

| Conditions | Total Impressions |
|---|---:|
| Category = Kitchen AND Engagement > 2 | 290 |
| Category = Beauty AND Engagement > 1 | 86 |

## Steps Completed
1. Created a Pinterest analytics practice workbook.
2. Entered the sample dataset.
3. Created a criteria range using Category and Engagement.
4. Used DSUM to calculate impressions for records matching both conditions.
5. Changed the criteria to test Beauty pins with engagement greater than 1.

## Key Learning
In a DSUM criteria range, conditions placed in the same row are evaluated using AND logic. A record must satisfy every condition in that row to be included in the calculation.

## Tools Used
- Microsoft Excel
- Pinterest sample analytics data