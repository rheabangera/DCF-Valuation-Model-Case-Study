# DCF Valuation Model

## Project Overview
This project contains a comprehensive 5-year Discounted Cash Flow (DCF) model developed as part of a Business Valuation academic assignment. The model estimates the intrinsic value of the target company as of the transaction date, December 31, 2026.

## Technical Methodology
The valuation follows a rigorous multi-step financial process:

* **Beta Analysis & Hamada Equation:** To determine the appropriate risk profile, I analyzed three industry competitors. I used the Hamada Equation to unlever their betas (average unlevered beta of 1.09) and re-levered the result based on the target company's specific capital structure.
* **WACC Calculation:** The Weighted Average Cost of Capital (8.678%) was derived using a 2.5% Risk-Free Rate and an 8.5% Market Return.
* **Free Cash Flow (FCF) Projections:** Forecasted Unlevered FCF from 2026 through 2030, adjusting EBIT for a 30% tax rate, Depreciation & Amortization, Capex, and changes in Working Capital.
* **Terminal Value:** Calculated using the Gordon Growth Method with a 2% perpetual growth rate.

## Valuation Results
| Metric | Value |
| :--- | :--- |
| **Enterprise Value** | €43,441  |
| **Equity Value** | €43,748  |
| **Implied Share Price** | **€37.55**  |
| **Current Market Price** | €39.00  |

**Conclusion:** Based on the model, the stock is currently **overvalued** relative to its intrinsic value.

## Files in this Repository
* `DCF_Val_Model.xlsx`: The full interactive financial model.
* `DCF_Val_Model.pdf`: A static export of the model's primary outputs and assumptions.
