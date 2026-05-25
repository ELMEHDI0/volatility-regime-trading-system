

Volatility Regime Trading System (SPY / TLT / GLD / BIL)

What it does:

Systematic trading strategy that adjusts portfolio exposure based on volatility regimes (VIX) and long-term trend filters.

Core logic:
VIX spike → risk-on opportunity
Low volatility → risk reduction
Rising volatility → defensive allocation
Trend filter (SMA200) avoids bear markets
Portfolio
SPY: equity exposure
TLT: bonds hedge
GLD: crisis hedge
BIL: cash stability
ML component

RandomForest model used only for position sizing confidence, not trade direction.

Tech stack:

Python, QuantConnect LEAN, NumPy, Scikit-learn

Goal:

Adaptive risk allocation across market regimes instead of price prediction.

Disclaimer:

Research project. Not financial advice. !!
