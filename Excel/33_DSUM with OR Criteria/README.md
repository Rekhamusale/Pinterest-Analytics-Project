# Topic 13: DSUM with OR Criteria in Excel

## Project Overview
This exercise demonstrates how to use the DSUM database function with OR criteria to calculate Pinterest impressions for multiple categories.

## Dataset
The `Pin_Data` sheet contains 10 Pinterest pin records with:
- Pin Name
- Category
- Impressions
- Engagement

## Excel Function Practiced
**DSUM with OR criteria**

Formula used:
`=DSUM(Pin_Data!A1:D11,"Impressions",A1:A3)`

## Practice Results

| Categories | Total Impressions |
|---|---:|
| Beauty OR Fashion | 169 |
| Kitchen OR Home | 478 |

## Steps Completed
1. Created a Pinterest analytics practice workbook.
2. Entered the sample dataset.
3. Created a criteria range with multiple categories on separate rows.
4. Used DSUM to calculate total impressions for either matching category.
5. Changed the criteria to test Kitchen OR Home.

## Key Learning
In a DSUM criteria range, conditions on separate rows are evaluated using OR logic. A record qualifies if it matches at least one row of criteria.

## Tools Used
- Microsoft Excel
- Pinterest sample analytics data