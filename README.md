# FP&A variance dashboard

Monthly flash for a fictional CPG company (**Northline Consumer Products**, FY2026).

**Deliverable:** [`Northline_FPNA_Variance_Dashboard_FY2026.xlsx`](Northline_FPNA_Variance_Dashboard_FY2026.xlsx)

![Dashboard preview](dashboard-preview.svg)

## Business question

Revenue is slightly ahead of plan. Why is EBITDA still short — and is the COGS miss **rate** or **volume**?

## How to review this file (8 minutes)

1. Open `05_Dashboard`. Sample close is YTD through July.
2. Read the COGS rate vs volume split on `03_Variance`.
3. On `01_Assumptions`, change **Close month** or **Standard COGS %** (yellow / blue).
4. Confirm `05_Dashboard` and the COGS bridge move. Black font is formulas.

## Screen-share test

Cut July units / revenue ~10% on `02_P&L_Monthly` and keep the standard COGS rate fixed. The COGS bridge should shift toward **volume**. Rate should stay the residual. If both move together, the split is not isolated.

| Driver (yellow / blue) | Tab | What should move |
| --- | --- | --- |
| Close month | `01_Assumptions` | Which month is “latest” on the dashboard |
| Standard COGS % | `01_Assumptions` | Size of the rate vs volume split |
| Latest-month actuals | `02_P&L_Monthly` | Dollar and percent variances, EBITDA |
| Forecast rows | `02_P&L_Monthly` | Remaining-year outlook vs annual plan |

## Sample read (closed through July)

YTD revenue runs a little ahead of plan. The watch-item is **gross margin**: COGS % is above the 60% standard, so most of the COGS miss is **rate**, not volume. That is an operations conversation (mix, freight, yield, or a stale standard). OpEx is close to plan; EBITDA follows the margin gap.

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

Excel formulas only. No VBA, no live ERP, no employer data. This is the close flash, not a driver-based forecast engine.

[Profile](https://github.com/saisiri-bandaru) · [Portfolio](https://saisiri-bandaru.github.io) · [LinkedIn](https://www.linkedin.com/in/bandarusaisiri) · [bandarusaisiri1207@gmail.com](mailto:bandarusaisiri1207@gmail.com)
