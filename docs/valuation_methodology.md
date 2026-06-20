# Valuation Methodology

The valuation section combines discounted cash flow outputs with a revenue multiple view.

## NPV

NPV is based on projected free cash flows and the selected discount rate.

In the base case screenshot:

- discount rate: 18.0%
- NPV: 7.14M RUB

## IRR

IRR is calculated from the projected cash flow stream. The base case screenshot shows a high IRR, which should be interpreted carefully because early-stage synthetic models are very sensitive to initial cash flow timing and scale assumptions.

## Revenue Multiple Valuation

The model also applies a revenue multiple to estimate implied valuation.

In the base case screenshot:

- revenue multiple: 3.0x
- implied valuation: 34.86M RUB

## EBITDA Context

The valuation page also reports total 3-year EBITDA:

- total 3-year EBITDA: 11.93M RUB

## Sensitivity Analysis

The sensitivity table tests Year 1 revenue against:

- deal conversion
- average commission rate

This is useful because the transaction commission stream depends heavily on both conversion and commission assumptions.

## Recommended Valuation Improvements

- Add a visible equity bridge if the model introduces debt, cash, or external funding.
- Add a terminal value bridge if the DCF is extended beyond the explicit forecast.
- Add a sensitivity table for discount rate and terminal value / exit multiple.
- Add sanity checks for implied valuation vs revenue, EBITDA and user base.
- Document source logic for valuation multiples when moving from synthetic to market-backed assumptions.
