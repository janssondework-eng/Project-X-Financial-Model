# Model Audit Notes

This file documents a lightweight structural review of the workbook for portfolio-readiness. It is not a full financial model audit.

## Workbook Structure

The workbook contains 11 sheets:

| Sheet | Non-empty Cells | Formula Cells |
|---|---:|---:|
| Cover | 39 | 0 |
| Assumptions | 113 | 0 |
| Monthly Model | 816 | 720 |
| Annual Summary | 30 | 18 |
| Unit Economics | 34 | 21 |
| P&L | 30 | 18 |
| Cash Flow | 30 | 14 |
| Valuation | 14 | 4 |
| Sensitivity | 23 | 9 |
| Dashboard | 46 | 19 |
| README Notes | 19 | 0 |

## Automated Checks Performed

- Workbook opened successfully.
- Sheet list was readable.
- Formula-bearing sheets were identified.
- No visible `#REF!`, `#DIV/0!`, `#VALUE!`, `#NAME?` or `#N/A` markers were found in stored formulas.

## Important Caveat

This check does not replace a full Excel recalculation and visual QA pass. Before using the model for a real decision, the workbook should be opened in Excel, recalculated, and reviewed cell by cell for:

- formula consistency across forecast periods
- correct scenario links
- hardcoded values inside calculation areas
- sign conventions
- model checks
- chart ranges
- source documentation

## Current Portfolio Strengths

- Clear workbook structure.
- Separate assumptions sheet.
- Scenario selector.
- Monthly operating model.
- Annual summary.
- Unit economics.
- P&L, cash flow and valuation sections.
- Sensitivity analysis.
- Dashboard page.

## Current Limitations

- Assumptions are synthetic and not source-backed.
- The model does not yet include a dedicated `Checks` sheet.
- Visual screenshots show mixed Russian/English labels.
- Dashboard chart series labels should be renamed from default series names.
- No Sources/Audit sheet is present for market assumptions.
