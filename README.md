# Analyze Power BI Capacity Consumption

Lab files for the Pluralsight Desktop Lab **Analyze Power BI Capacity Consumption**.

## Contents

| File | Description |
|---|---|
| `Capacity-Consumption.xlsx` | Two weeks of hourly usage for a Microsoft Fabric F64 capacity, as an Excel workbook with two sheets |

## Workbook

| Sheet | Rows | Columns |
|---|---|---|
| `Timepoints` | 336, one per hour for 14 days | Timepoint, Date, Weekday, Available CU (s), Throttling stage |
| `Usage` | 3,714, one per hour, item, and operation | Timepoint, Workspace, Workload, Item kind, Item name, Operation, Operation type, CU (s) |

Learners import both sheets into Power BI Desktop in the first objective of the lab. Nothing else needs to be installed or configured.

## About the Data

The data is fictional. It is modeled on the terms of the Microsoft Fabric Capacity Metrics app and is produced by a script, so the same workbook comes out of every build. The workspace and item names do not refer to any real organization.
