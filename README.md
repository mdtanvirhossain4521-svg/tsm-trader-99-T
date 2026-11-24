# TSM TRADER 99-T

Mobile-friendly Streamlit market-analysis prototype.

## Run locally

```bash
python -m pip install -r requirements.txt
streamlit run app.py --server.address 0.0.0.0 --server.port 8501
```

## Streamlit Cloud

In the app's **Settings > Secrets**, add:

```toml
ADMIN_PASSWORD = "replace-with-admin-password"
USER_PASSWORD = "replace-with-user-password"
```

## Data limitation

This app uses public Yahoo Finance data. It does not access Quotex, use an OTC feed, guarantee accuracy, place trades, or provide financial advice.
