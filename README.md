# AFS Project Estimator-Tracker

HTML-based project tracking dashboard for Audubon Companies with Google Sheets API integration.

## Features
- Real-time budget tracking (Projects 1-3)
- EVM metrics (EAC, CPI, SPI, variance analysis)
- Weekly FCST/ACWP hours and burndown
- Google Sheets API sync

## Setup
1. Save as `index.html`
2. Create Google Cloud Project with OAuth 2.0 credentials
3. Replace `CLIENT_ID` and `SHEET_ID` in code
4. Run: `python3 -m http.server 8000`
5. Open http://localhost:8000
