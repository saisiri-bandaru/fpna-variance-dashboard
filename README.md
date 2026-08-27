# FP&A variance dashboard

Monthly financial flash for a fictional CPG company (**Northline Consumer Products**, FY2026). Built as a portfolio piece for [saisiri-bandaru](https://github.com/saisiri-bandaru).

**File to open:** `Northline_FPNA_Variance_Dashboard_FY2026.xlsx`

All numbers are made up. Do not put real employer data in this public repo.

## What this shows

- Actual vs Budget vs Forecast on revenue, COGS, gross profit, OpEx, and EBITDA
- YTD and latest-month dollar and percent variances
- A simple **COGS rate vs volume** split (standard-cost lens)
- Department view of OpEx
- One-page dashboard for a standup or ELT pre-read

## How an FP&A close uses it

1. Set **Close month** on `01_Assumptions` (yellow cell).
2. Type actuals for that month on `02_P&L_Monthly`. Leave future months blank.
3. Update forecast only when the reforecast changes.
4. Read `05_Dashboard`, then write the story from `03_Variance`.

Blue font + yellow fill = inputs. Black font = formulas.

## Sample read (file is closed through July)

YTD revenue runs a little ahead of the annual plan on mid-year volume. The watch-item is **gross margin**: COGS % is above the 60% standard rate, so most of the COGS miss is **rate**, not volume. That is the operations conversation (mix, freight, yield, or a stale standard). OpEx is close to plan; EBITDA follows the margin gap.

## Tabs

| Tab | Role |
| --- | --- |
| `00_Cover` | Purpose and refresh steps |
| `01_Assumptions` | Close month and standard COGS % |
| `02_P&L_Monthly` | Monthly P&L three-way view |
| `03_Variance` | YTD / month flash + COGS rate bridge |
| `04_Dept_OpEx` | Cost-center structure |
| `05_Dashboard` | One-pager + revenue chart |
| `06_Data_Dictionary` | Field definitions |

## Stack

Excel (formulas only — no VBA). Built so another analyst can inherit the file from the data dictionary.

## Not included on purpose

- Live ERP extracts
- Confidential PNC or other employer data
- A full driver-based forecast engine (this is the *close flash*, not Hyperion)

## Profile

Sai Siri Bandaru — Financial Analyst | FP&A | forecasting, variance analysis, Excel & Power BI
