# Hebrew Translator (Streamlit)

## What it does
Upload one or more Hebrew PDFs (with selectable text). The app translates each page and exports a single Word document.

## Deploy (Streamlit Community Cloud)
1) Create a GitHub repo and upload these files: `app.py`, `requirements.txt`, `README.md`.
2) Go to Streamlit Community Cloud → **Create app** → select your repo → main file `app.py` → Deploy.
3) In Streamlit: **App settings → Secrets** add:

```toml
OPENAI_API_KEY = "YOUR_KEY_HERE"
```

## Notes
- If your PDF pages are scanned images (no selectable text), this MVP will warn you. OCR can be added as a next step.
