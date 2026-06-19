# Forward Holdings

A mobile-first portfolio app for uploading or pasting stock holdings, categorizing them into future-industry themes, tracking earnings, and exploring emerging industry watchlists.

## Features

- Upload broker exports, text files, PDFs, and screenshots.
- Paste holdings text when screenshots cannot be OCR-read locally.
- Categorize holdings across AI, semiconductors, quantum, nuclear, energy, infrastructure, space, medicine, gaming, cybersecurity, water, and robotics themes.
- Show short company descriptions for recognized tickers.
- Track upcoming earnings and recent earnings report availability.
- Connect optional Finnhub or Financial Modeling Prep API keys for live earnings data.
- Explore future-industry research candidates across large, mid, and smaller companies.

## Run

Open `index.html` in a browser, or enable GitHub Pages for the repository and serve from the `main` branch root.

## Notes

- Screenshot OCR loads Tesseract.js from a CDN when the browser is online.
- Without an earnings API key, the app uses demo earnings data.
- Watchlist ideas are research candidates, not financial advice.
