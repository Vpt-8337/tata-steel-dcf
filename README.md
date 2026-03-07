# tata-steel-dcf
Tata Steel DCF Valuation Model
A Discounted Cash Flow valuation of Tata Steel Limited (NSE: TATASTEEL) built from scratch in Python and Excel, using FY2021–FY2025 consolidated financials sourced from Screener.in.
Method: 5-year FCF projection, Gordon Growth terminal value, WACC computed via CAPM with market value weights.
Key Assumptions: 4.5% revenue growth, 12.5% normalised EBITDA margin, 11.5% WACC, 5% terminal growth rate reflecting India's long-run nominal GDP.
Output: Intrinsic value of ₹80 per share against a market price of ₹201 — a 60% implied downside. The market price is only justified at EBITDA margins above 18%, requiring a full commodity supercycle recovery.
Limitations: Linear margins applied to a cyclical business, flat WACC across projection period, no scenario analysis on cost of debt, depreciation not adjusted for accumulated growth CapEx.
Tools: Python (Google Colab), Excel, openpyxl
