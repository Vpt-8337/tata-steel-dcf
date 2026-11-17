# tata-steel-dcf
# Tata Steel Limited – Discounted Cash Flow (DCF) Valuation

A five-year Discounted Cash Flow (DCF) valuation model of **Tata Steel Limited (NSE: TATASTEEL)**, estimating intrinsic equity value using projected free cash flows, weighted average cost of capital (WACC), and terminal value analysis.

## 1. Project Overview

This project develops an independent valuation of Tata Steel using a five-year DCF model covering FY2026–FY2030, with FY2025 as the base year.

The objective is to estimate the company's intrinsic value per share based on projected operating performance, capital expenditure requirements, and the cost of capital, and compare it against its market price.

The model uses consolidated historical financial data and incorporates assumptions regarding revenue growth, EBITDA margins, taxation, capital expenditure, and long-term growth.

## 2. Valuation Summary

| Metric | Result |
|---|---:|
| Company | Tata Steel Limited |
| Ticker | NSE: TATASTEEL |
| Base Year | FY2025 |
| Projection Period | FY2026–FY2030 |
| WACC | 10.84% |
| Terminal Growth Rate | 5.00% |
| Enterprise Value | ₹1,83,456 crore |
| Equity Value | ₹1,00,035 crore |
| Intrinsic Value per Share | ₹80.22 |
| Market Price | ₹200.79 |
| Implied Upside / (Downside) | **-60.0%** |

**Key finding:** The model estimates an intrinsic value of ₹80.22 per share, approximately 60% below the reference market price of ₹200.79, suggesting that Tata Steel was trading at a substantial premium to the model's estimated intrinsic value under the base-case assumptions.

## 3. Historical Financial Analysis

The model incorporates five years of consolidated historical financial data (FY2021–FY2025).

Key financial indicators include:

- Revenue
- EBITDA
- Depreciation
- EBIT
- Capital expenditure
- EBITDA margins
- EBIT margins
- Capital expenditure as a percentage of revenue

Historical performance informs the assumptions used in projecting future operating performance, particularly normalised EBITDA margins, depreciation and capital expenditure requirements.

**Data source:** Screener.in – Consolidated financial statements.

## 4. Key Modelling Assumptions

### Operating assumptions

| Assumption | Value |
|---|---:|
| Annual Revenue Growth | 4.5% |
| EBITDA Margin | 12.5% |
| Depreciation / Revenue | 4.5% |
| Tax Rate | 31% |
| Change in Working Capital | Neutral (0%) |

Revenue growth reflects an assumption of continued Indian infrastructure demand and post-FY2025 recovery. EBITDA margins are normalised above the FY2024 trough.

### Capital expenditure assumptions

The model separates maintenance capital expenditure from growth capital expenditure.

- Maintenance CapEx is approximated using depreciation.
- Growth CapEx is modelled as a declining percentage of revenue, reflecting an assumed moderation in expansion expenditure.

| Financial Year | Growth CapEx / Revenue |
|---|---:|
| FY2026 | 2.5% |
| FY2027 | 2.0% |
| FY2028 | 1.5% |
| FY2029 | 1.0% |
| FY2030 | 0.5% |

### Weighted Average Cost of Capital (WACC)

The discount rate is calculated using the weighted average cost of equity and after-tax cost of debt.

| Component | Assumption |
|---|---:|
| Risk-Free Rate | 7.0% |
| Beta | 1.4 |
| Equity Risk Premium | 5.0% |
| Cost of Equity | 14.0% |
| Pre-tax Cost of Debt | 7.0% |
| Equity Weight | 65.5% |
| Debt Weight | 34.5% |
| **WACC** | **10.84%** |

The cost of equity is estimated using the Capital Asset Pricing Model (CAPM).

### Terminal Value and Balance Sheet

| Component | Value (₹ crore) |
|---|---:|
| Terminal Growth Rate | 5.0% |
| Total Borrowings | 94,801 |
| Cash and Equivalents | 12,222 |
| Net Debt | 83,421 |
| Shares Outstanding | 1,247 crore |

The terminal growth rate represents the assumed long-term nominal growth of the business.

## 5. DCF Valuation Methodology

The model follows a conventional unlevered Discounted Cash Flow framework.

**Step 1 – Revenue Projection**

Future revenue is projected using the assumed annual growth rate of 4.5%.

**Step 2 – Operating Profitability**

EBITDA is estimated using the normalised EBITDA margin of 12.5%. Depreciation is then deducted to calculate Earnings Before Interest and Tax (EBIT).

**Step 3 – Net Operating Profit After Tax (NOPAT)**

EBIT is adjusted for the assumed effective tax rate of 31%.

**Step 4 – Free Cash Flow Calculation**

Free Cash Flow is estimated by adjusting NOPAT for capital expenditure requirements.

The model approximates maintenance CapEx using depreciation and separately deducts projected growth CapEx.

**Step 5 – Discounting Cash Flows**

Projected annual free cash flows are discounted to present value using the calculated WACC of 10.84%.

**Step 6 – Terminal Value**

Terminal value is estimated using the Gordon Growth approach, applying a perpetual growth assumption of 5%.

**Step 7 – Equity Valuation**

Present values of projected free cash flows and terminal value are combined to estimate Enterprise Value. Net debt is deducted to derive Equity Value, which is subsequently divided by shares outstanding to calculate intrinsic value per share.

## 6. Sensitivity Analysis

A sensitivity analysis examines how changes in revenue growth and EBITDA margins affect estimated intrinsic value.

The model evaluates:

- Revenue growth assumptions ranging from 3% to 6%.
- EBITDA margins ranging from 10% to 18%.

Selected sensitivity outputs:

| EBITDA Margin | 3% Growth | 4.5% Growth | 6% Growth |
|---|---:|---:|---:|
| 10% | ₹21 | ₹27 | ₹34 |
| 12% | ₹61 | ₹70 | ₹79 |
| 14% | ₹101 | ₹112 | ₹124 |
| 16% | ₹141 | ₹155 | ₹170 |
| 18% | ₹180 | ₹197 | ₹215 |

The analysis demonstrates the significant sensitivity of Tata Steel's estimated valuation to operating margins and long-term revenue growth.

Higher EBITDA margins and revenue growth assumptions materially increase intrinsic value, highlighting the importance of operating performance in determining the company's valuation.

## 7. Model Output and Interpretation

Under the base-case assumptions, the DCF model produces an intrinsic valuation of ₹80.22 per share.

Compared with the reference market price of ₹200.79, this implies approximately 60% downside.

The valuation suggests that the market price incorporates substantially more optimistic expectations regarding future operating performance than those reflected in the model's base case.

This does not necessarily imply that the market price is incorrect. Rather, it highlights the sensitivity of the valuation to assumptions concerning profitability, growth, capital expenditure and the cost of capital.

## 8. Limitations

The valuation is subject to several limitations:

- Revenue growth and EBITDA margins are based on assumptions rather than guaranteed future performance.
- Depreciation is used as a proxy for maintenance capital expenditure.
- Working capital changes are assumed to be neutral.
- The terminal value is sensitive to the perpetual growth rate and WACC.
- The model uses a simplified set of operating and macroeconomic assumptions and may not capture all industry-specific developments.
- The sensitivity analysis illustrates valuation outcomes under alternative operating assumptions but does not assign probabilities to those scenarios.

The estimated intrinsic value should therefore be interpreted as a scenario-based valuation rather than a definitive target price.

## 9. Repository Structure

The accompanying Excel workbook is organised into five worksheets:

| Worksheet | Description |
|---|---|
| Cover | Company information and headline valuation |
| Assumptions | Operating assumptions, WACC and balance-sheet inputs |
| Historical Data | Consolidated financial history (FY2021–FY2025) |
| DCF Model | FY2026–FY2030 projections and intrinsic valuation |
| Sensitivity Analysis | Intrinsic value under alternative growth and margin assumptions |

## 10. Tools and Data Sources

**Tools**
- Microsoft Excel – Financial modelling and valuation.
- Discounted Cash Flow methodology.
- Capital Asset Pricing Model (CAPM).
- Sensitivity analysis.

**Data sources**
- Screener.in – Consolidated historical financials and FY2025 borrowings.
- Google Finance – FY2025 cash and equivalents.
- Bloomberg – Beta reference.
- Assumption-based inputs – Risk-free rate, equity risk premium, cost of debt, growth and operating projections.

---

## Disclaimer

This project represents independent academic financial research and is intended for educational and analytical purposes only. The valuation is based on historical information and subjective assumptions. It does not constitute investment advice or a recommendation to buy or sell Tata Steel securities.

**Author:** Veer Thakkar  
**Project:** Independent Equity Valuation  
**Valuation Period:** FY2026–FY2030
