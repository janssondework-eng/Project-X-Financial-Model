# Assumptions And Scenarios

The model is driven by a scenario selector with three cases:

- Conservative
- Base
- Optimistic

## Base Scenario Inputs

| Driver | Base Assumption |
|---|---:|
| Initial active users | 2,500 users |
| Monthly user growth | 5.5% |
| Monthly churn | 3.5% |
| Conversion to successful deal | 15.0% |
| Average rent | 25,000 RUB |
| Average commission | 4.0% |
| Premium price | 399 RUB / month |
| Premium conversion | 5.0% |
| Partnership revenue per user | 14.0 RUB / user / month |
| Advertising revenue per user | 6.0 RUB / user / month |
| Listings per user | 0.4 listings |
| Promoted listing price | 199 RUB |
| Promoted listing conversion | 20.0% |
| Paid listing start month | month 25 |
| Paid listing fee | 299 RUB |
| Paid listing conversion | 8.0% |
| CAC | 300 RUB / user |
| Average customer lifetime | 12 months |

## Cost Inputs

| Driver | Base Assumption |
|---|---:|
| Development / month | 120,000 RUB |
| Marketing / month | 120,000 RUB |
| Hosting / month | 25,000 RUB |
| Legal and admin / month | 20,000 RUB |
| Support / month | 35,000 RUB |
| Other expenses / month | 25,000 RUB |
| Variable cost per deal | 150 RUB |

## Scenario Multipliers

| Metric | Conservative | Base | Optimistic |
|---|---:|---:|---:|
| User growth multiplier | 0.7x | 1.0x | 1.4x |
| Conversion multiplier | 0.8x | 1.0x | 1.2x |
| Premium conversion multiplier | 0.8x | 1.0x | 1.3x |
| CAC multiplier | 1.3x | 1.0x | 0.9x |
| Cost multiplier | 1.1x | 1.0x | 1.1x |

## Interpretation

The model is intentionally assumption-driven. The most important drivers are:

- active user growth
- successful deal conversion
- average rent and commission rate
- premium conversion
- CAC
- fixed monthly operating costs

Because this is a synthetic portfolio model, assumptions should be treated as planning inputs rather than verified market estimates.
