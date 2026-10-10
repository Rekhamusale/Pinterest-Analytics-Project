# Topic 3: HLOOKUP in Excel

## Project Overview
This project demonstrates how to use the HLOOKUP function in Microsoft Excel to retrieve Pinterest pin information arranged horizontally.

## Objective
- Understand how HLOOKUP works.
- Search for a Pinterest pin name in the first row.
- Retrieve Category, Impressions, and Engagement.
- Use exact-match lookup.
- Handle missing values using IFERROR.

## Workbook Details
**File Name:** `Pinterest_HLOOKUP_Practice.xlsx`

**Worksheets:**
1. `Horizontal_Data` – Contains Pinterest pin data arranged horizontally.
2. `Lookup_Practice` – Used to search for pins and display matching results.

## Excel Functions Practiced

### 1. HLOOKUP
HLOOKUP searches for a value in the first row of a selected range and returns a value from a specified row.

Example:
```excel
=HLOOKUP(B3,Horizontal_Data!A1:F4,2,FALSE)
```

### 2. IFERROR
IFERROR displays a friendly message if the lookup formula returns an error.

Example:
```excel
=IFERROR(HLOOKUP(B3,Horizontal_Data!A1:F4,2,FALSE),"Pin Not Found")
```

## Practice Results

| Pin Name | Category | Impressions | Engagement |
|---|---|---:|---:|
| Handbag Fashion | Fashion | 45 | 2 |
| Wooden Knife Holder | Kitchen | 214 | 4 |

## Key Learnings
- HLOOKUP searches horizontally across the first row.
- The third argument specifies the row number within the selected range.
- `FALSE` requests an exact match.
- IFERROR helps handle missing or invalid lookup results.
- HLOOKUP is useful when data is arranged horizontally.

## Skills Practiced
Microsoft Excel, HLOOKUP, IFERROR, exact-match lookup, data retrieval, and error handling.

## Project Status
**Completed:** HLOOKUP practice and final challenge.

This project is part of my Pinterest Analytics portfolio, where I practise Excel skills using sample pin performance data.