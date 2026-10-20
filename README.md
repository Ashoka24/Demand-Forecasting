# Demand Forecasting

A Python project comparing Random Forest regression with a seasonal-naive baseline on a chronological holdout, then generating a six-month forecast.

The included monthly sales data are synthetic and are for portfolio demonstration only.

## Run

```bash
python -m pip install -r requirements.txt
python scripts/run_analysis.py
python -m unittest discover -s tests -v
streamlit run app.py
```

See [model card](docs/model-card.md) for the method, intended use and limitations. Forecast quality should be tested with rolling-origin backtesting before real-world use.