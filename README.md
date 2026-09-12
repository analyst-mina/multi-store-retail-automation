# Multi-Store Retail Automation Pipeline

An automated Python data pipeline designed to extract sales and inventory data from multiple retail sources, handle portal authentication, parse email reports via IMAP, consolidate the data using Pandas, and output a clean daily profit report.

## Key Features
- **Fault-Tolerant Error Handling:** Independent `try/except` blocks per store ensure that a failure or timeout on one site never halts the rest of the batch.
- **Automated Calculations:** Uses Pandas to compute Cost Price, Commissions, and Net Profit margins automatically.
- **Multi-Source Architecture:** Built to handle web scraping (BeautifulSoup/Playwright), email ingestion, and Excel generation in a single workflow.

## Tech Stack
- Python
- Pandas
- Playwright / BeautifulSoup
- IMAPlib
-
