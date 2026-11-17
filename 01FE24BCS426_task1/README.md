# Onion modal price forecast: Hubli (Amaragol)

- `forecast_onion.ipynb`: full pipeline (inspection → cleaning → features + leakage check → LightGBM → walk-forward vs random split → 14-day forecast), already executed
- `forecast_onion.html`: the same notebook, viewable in a browser
- `WRITEUP.md` / `WRITEUP.pdf`: one-page write-up
- `figures/`: raw-data plot, forecast-vs-actuals plot, results table, 14-day forecast CSV
- `data/`: the 6 raw CEDA exports (price and arrivals, 2023/2024/2025)

Run: `pip install -r requirements.txt`, then run all cells in the notebook.
