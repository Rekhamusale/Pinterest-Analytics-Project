# Topic 2: VLOOKUP in Excel

## Project Overview
This project demonstrates how to use the VLOOKUP function in Excel to search for Pinterest pin data and return matching information.

## Objective
- Learn how VLOOKUP works.
- Find a pin by its name.
- Retrieve Category, Impressions, and Engagement.
- Use exact-match lookup.
- Handle missing values using IFERROR.

## Workbook Details
**File Name:** `Pinterest_VLOOKUP_Practice.xlsx`

**Worksheets:**
1. `Pin_Data` – Contains Pinterest pin details.
2. `Lookup_Practice` – Used to search for a pin and display its results.

## Excel Functions Practiced

### 1. VLOOKUP
Searches for a value in the first column of a selected range and returns information from another column in the same row.

Example:
```excel
=VLOOKUP(B3,Pin_Data!A:D,2,FALSE)
```

### 2. IFERROR
Displays a friendly message when the lookup cannot find a matching pin.

Example:
```excel
=IFERROR(VLOOKUP(B3,Pin_Data!A:D,2,FALSE),"Pin Not Found")
```

## Practice Results

| Pin Name | Category | Impressions | Engagement |
|---|---|---:|---:|
| Wooden Knife Holder | Kitchen | 214 | 4 |
| Beauty Self-Care | Beauty | 57 | 2 |
| Kitchen Storage | Kitchen | 76 | 3 |
| Handbag Fashion | Fashion | 45 | 2 |

**Missing-value test:** Searching for `Premium Lunch Box` displays `Pin Not Found`.

## Key Learnings
- VLOOKUP searches vertically.
- The lookup value must be in the first column of the selected range.
- The column index determines which value is returned.
- `FALSE` requests an exact match.
- IFERROR helps handle missing values.

## Skills Practiced
Microsoft Excel, VLOOKUP, IFERROR, exact-match lookup, data retrieval, and basic error handling.

## Project Status
**Completed:** VLOOKUP practice and final challenge.

This project is part of my Pinterest Analytics portfolio, where I practise Excel skills using sample pin performance data.
