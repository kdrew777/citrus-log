# 🍊 Citrus Application Records App

A simple local web app for viewing, filtering, analyzing, and adding to your citrus grove spray / fertilizer logs.

## What's included

- **Dashboard** – KPIs + charts by year, type, and application method
- **Records** – searchable, filterable table of all applications
- **Add Entry** – form to log new sprays / fertilizer applications
- **Insights** – product rankings, monthly trends, heatmap of activity
- **Export** – download cleaned or filtered CSV

## Quick start

```bash
# From this folder
pip install streamlit pandas plotly

streamlit run app.py
```

The app will open in your browser (usually http://localhost:8501).

## Files

| File | Purpose |
|------|---------|
| `app.py` | The Streamlit application |
| `citrus_records_clean.csv` | Cleaned version of your data (106 records) |
| `clean_data.py` | Script used to clean the original Excel |

## Notes

- Filters in the sidebar apply across most pages.
- New entries you add are saved into `citrus_records_clean.csv`.
- The original messy Excel is left untouched.
