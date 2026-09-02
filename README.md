# FP&A variance dashboard

Monthly financial flash for a fictional CPG company (**Northline Consumer Products**, FY2026).

**Open this file:** [`Northline_FPNA_Variance_Dashboard_FY2026.xlsx`](Northline_FPNA_Variance_Dashboard_FY2026.xlsx)

![Dashboard preview](dashboard-preview.svg)

Preview of `05_Dashboard`. Sample close is YTD through July. All figures are fictional.

## Business question

Revenue is slightly ahead of plan. Why is EBITDA still short — and is the COGS miss **rate** or **volume**?

That is the conversation this file is built to start with operations in the first ten minutes of the flash meeting.

## What to change in a screen-share

| Driver (yellow / blue) | Tab | What should move |
| --- | --- | --- |
| Close month | `01_Assumptions` | Which month is “latest” on the dashboard |
| Standard COGS % | `01_Assumptions` | Size of the rate vs volume split |
| Latest-month actuals | `02_P&L_Monthly` | Dollar and percent variances, EBITDA |
| Forecast rows | `02_P&L_Monthly` | Remaining-year outlook vs annual plan |

**Volume shock to try:** cut July units / revenue ~10% on the actuals tab and keep the standard COGS rate fixed. The COGS bridge should show the miss shifting toward **volume**; rate should stay the residual. If both move together, the split is not isolated.

Blue font + yellow fill = inputs. Black font = formulas.

## Sample read (file closed through July)

YTD revenue runs a little ahead of the annual plan on mid-year volume. The watch-item is **gross margin**: COGS % is above the 60% standard rate, so most of the COGS miss is **rate**, not volume. That is an operations conversation (mix, freight, yield, or a stale standard). OpEx is close to plan; EBITDA follows the margin gap.

## How a close uses it

1. Set **Close month** on `01_Assumptions`.
2. Type actuals for that month on `02_P&L_Monthly`. Leave future months blank.
3. Touch forecast only when the reforecast changes.
4. Read `05_Dashboard`, then write the story from `03_Variance`.

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

Excel formulas only — no VBA. Built so another analyst can inherit the file from the data dictionary.

## Not in this file on purpose

- Live ERP extracts
- Confidential employer data
- A full driver-based forecast engine (this is the *close flash*)

[Profile](https://github.com/saisiri-bandaru) · [Portfolio](https://saisiri-bandaru.github.io) · [LinkedIn](https://www.linkedin.com/in/bandarusaisiri) · [bandarusaisiri1207@gmail.com](mailto:bandarusaisiri1207@gmail.com)
