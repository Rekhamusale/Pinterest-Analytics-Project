# Topic 15: Random Data

## Objective

Learn how to generate random numbers, random test data, random groups, and random dates in Excel using built-in functions.

## Dataset

Pinterest Board Performance Data

## Skills Practiced

- `RAND()`
- `RANDBETWEEN()`
- `DATE()`
- Generating random impressions
- Generating random engagement values
- Generating random pin clicks
- Creating random test groups
- Using `COUNTIF()` with random groups
- Using `SUMIF()` with random groups
- Generating random dates
- Creating random dates within a specific date range
- Paste Special → Values to freeze random results

## Practice Completed

### 1. Random Numbers

Practiced generating random decimal values using:

`=RAND()`

Practiced generating random whole numbers using:

`=RANDBETWEEN(1,250)`

### 2. Pinterest-Style Random Data

Generated random values for:

- Impressions
- Engagement
- Pin Clicks

### 3. Random Test Groups

Assigned Pinterest records randomly to three test groups using:

`=RANDBETWEEN(1,3)`

Analyzed each group using `COUNTIF()` and `SUMIF()`.

The final group totals were:

| Test GroupNumber of PinsTotal Impressions |        |         |
| ----------------------------------------- | ------ | ------- |
| 1                                         | 9      | 227     |
| 2                                         | 4      | 33      |
| 3                                         | 10     | 383     |
| **Total**                                 | **23** | **643** |

### 4. Random Dataset

Created a separate dataset containing:

- Pin numbers
- Random Impressions
- Random Engagement
- Random Pin Clicks
- Random Dates

### 5. Random Dates

Generated random dates using:

`=RANDBETWEEN(DATE(2026,1,1),DATE(2026,12,31))`

Also practiced generating dates within a specific range, such as April 1, 2026 to June 30, 2026.

## Important Learning

Functions such as `RAND()` and `RANDBETWEEN()` are volatile. Their values can change when Excel recalculates the workbook.

To keep a generated random dataset unchanged:

**Copy → Paste Special → Values**

## Business Use

Random data can be useful for:

- Testing Excel formulas
- Creating sample datasets
- Testing dashboards and reports
- Creating test groups
- Practicing data analysis
- Simulating business scenarios

## Key Learning

Random-data functions help analysts create realistic test data quickly. Understanding how random values change and how to freeze them is important when working with Excel analysis and reporting.

## Workbook

`Pinterest_Random_Data_Practice.xlsx`