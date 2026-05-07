# Southern Water Corp — Financial Performance Analysis

Built a end-to-end financial analysis model for Southern Water Corp, a desalination company operating three plants across Australia. The goal was to cut through 12 months of raw transactional data and surface actionable insights on revenue performance, cost drivers, and unit-level profitability.

## What I worked with

A master dataset covering July 2013 to June 2014 across three desalination units — Kootha, Surjek, and Jutik — with revenue and expense transactions mapped to accounting code centres, customer segments, and monthly periods.

## What I built

**Revenue Analysis** — aggregated monthly revenues by unit and customer segment (Private, Public, Residential) using dynamic SUMIFS formulas. Calculated segment contribution percentages to understand revenue mix.

**Expense Analysis** — broke down operating costs across Chemical, Facility, Operational Maintenance, and Labour categories. Identified cost concentration by unit and traced chemical spend against water production volumes.

**Profitability (EBIT)** — computed EBIT and EBIT margins per unit across the full 12-month period. Surfaced which units were genuinely profitable vs revenue-heavy but margin-thin.

## Key Takeaways

- Surjek generated the highest revenue (~$202M) but had the thinnest EBIT margin (~11%) due to disproportionately high operating costs
- Jutik was the most cost-efficient unit with the strongest EBIT margin (~45%)
- Labour and Chemical Costs were the biggest expense drivers across all units
- January consistently peaked in revenue across all three units — clear seasonal demand pattern

## Tools
Excel — SUMIFS, dynamic formula logic, no Pivot Tables, data visualisation (line, column, stacked charts)
