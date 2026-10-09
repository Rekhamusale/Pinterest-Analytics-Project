# Topic 20 – Cross-Sheet References

## Overview

This practice focuses on using cross-sheet references in Excel to connect raw data, calculations, and dashboard information.

## Workbook Structure

The workbook contains three worksheets:

1. `Raw_Data`
2. `Calculations`
3. `Dashboard`

## Raw Data

The `Raw_Data` sheet contains Pinterest performance data:

* Pinterest Link
* Impressions
* Engagement
* Pin clicks
* Outbound clicks
* Saves

## Calculations

The `Calculations` sheet uses cross-sheet formulas to calculate:

* Total Impressions
* Total Engagement
* Total Pin Clicks
* Total Outbound Clicks
* Total Saves

Example formula:

`=SUM(Raw_Data!B2:B6)`

## Dashboard

The `Dashboard` sheet retrieves the calculated values from the `Calculations` sheet using cross-sheet cell references.

Example:

`=Calculations!B2`

## Data Flow

The workbook follows this structure:

`Raw_Data → Calculations → Dashboard`

Changes made to the original data automatically update the calculations and dashboard values.

## Excel Skills Practiced

* Cross-sheet references
* Sheet-to-sheet data linking
* SUM formulas with another worksheet
* Direct cell references between worksheets
* Creating a simple reporting structure
* Testing automatic updates
* Separating raw data, calculations, and presentation

## Learning Outcome

Learned how to connect multiple Excel worksheets so that calculations and dashboard values update automatically when the source data changes.
