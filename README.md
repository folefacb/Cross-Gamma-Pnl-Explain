# Cross-Gamma-Pnl-Explain

cross-gamma-risk-engine/
├── app/
│   ├── gamma_overview.py
│   ├── cross_gamma.py          # main page
│   ├── trade_detail.py
│   ├── basket_detail.py
│   └── scenarios.py
├── risk/
│   ├── delta.py
│   ├── gamma.py
│   ├── hessian.py              # core engine
│   ├── pnl_attribution.py
│   └── scenarios.py
├── pricing/
│   ├── base.py
│   ├── worst_of.py
│   └── basket.py
├── baskets/
│   ├── models.py
│   ├── mappings.py
│   └── transforms.py
├── data/
│   ├── sample_market_data.csv
│   ├── sample_trades.csv
│   └── sample_baskets.json
├── tests/
│   ├── test_hessian.py
│   ├── test_greeks.py
│   └── test_pnl.py
├── README.md
├── pyproject.toml
└── requirements.txt
