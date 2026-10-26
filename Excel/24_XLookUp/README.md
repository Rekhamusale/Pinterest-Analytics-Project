# Topic 4: XLOOKUP in Excel

## Project Overview
This project demonstrates how to use the XLOOKUP function in Microsoft Excel to retrieve Pinterest pin information from a dataset.

## Objective
- Understand how XLOOKUP works.
- Search for a Pinterest pin by name.
- Retrieve Category, Impressions, and Engagement.
- Display a custom message when a pin is not found.
- Build a reusable lookup sheet for Pinterest analytics data.

## Workbook Details
**File Name:** `Pinterest_XLOOKUP_Practice.xlsx`

**Worksheets:**
1. `Pin_Data` – Contains Pinterest pin names, categories, impressions, and engagement.
2. `Lookup_Practice` – Allows users to enter a pin name and retrieve matching details.

## Excel Function Practiced

### XLOOKUP
XLOOKUP searches for a value in a specified range and returns the corresponding value from another range.

Example:
```excel
=XLOOKUP(B3,Pin_Data!A2:A11,Pin_Data!B2:B11,"Pin Not Found")
```

### Formula Explanation
- `B3` – The pin name to search for.
- `Pin_Data!A2:A11` – The lookup range containing pin names.
- `Pin_Data!B2:B11` – The return range containing categories.
- `"Pin Not Found"` – The message displayed when no matching pin exists.

## Practice Results

| Pin Name | Category | Impressions | Engagement |
|---|---|---:|---:|
| Handbag Fashion | Fashion | 45 | 2 |
| Wooden Knife Holder | Kitchen | 214 | 4 |

## Key Learnings
- XLOOKUP searches for a value in a specified lookup range.
- The return range determines which matching information is displayed.
- XLOOKUP can return values from columns to the left or right of the lookup range.
- A custom message can be specified for missing values.
- One lookup formula can be reused for different search values.

## Skills Practiced
Microsoft Excel, XLOOKUP, lookup and return ranges, data retrieval, exact-match lookups, and basic error handling.

## Project Status
**Completed:** XLOOKUP practice and final challenge.

This project is part of my Pinterest Analytics portfolio, where I practise Excel functions using sample Pinterest pin performance data.