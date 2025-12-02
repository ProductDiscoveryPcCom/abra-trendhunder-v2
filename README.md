# Abra - Advanced Brand Research & Analysis

Version: 11.4.4

## Quick Start

```bash
# Install dependencies
pip install -r requirements.txt

# Run locally
streamlit run app.py
```

## Streamlit Cloud Deployment

1. Push this repo to GitHub
2. Connect to Streamlit Cloud
3. Add secret: `SERPAPI_API_KEY = "your_key_here"`
4. Deploy

## Features

- Multi-channel analysis (Web, Images, News, YouTube, Shopping)
- 7 countries supported (ES, PT, FR, IT, DE, GB, US)
- 20 product categories
- Real-time insights and trends
- Export to CSV, Excel, PDF

## Configuration

Create `.streamlit/secrets.toml`:
```toml
SERPAPI_API_KEY = "your_api_key_here"
```
