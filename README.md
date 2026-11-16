##🍽️ n8n Google Maps Restaurant Scraper

An n8n workflow that runs a Google Maps scraper through Apify and saves the collected restaurant data to a newly created Google Sheet.

## 📌 Features

- **Manual workflow start:** Start the workflow from n8n whenever you need a new scrape.
- **Google Maps data collection:** Runs Apify's Google Maps Scraper with the search term `restaurant` and a limit of up to 50 places per search.
- **Automatic spreadsheet creation:** Creates a new Google Sheet named `AI 2` for the results.
- **Results export:** Appends the scraper output to the new sheet using automatic column mapping.

## 🛠️ Tech Stack

- **Automation Tool:** n8n
- **Scraping Platform:** Apify — Google Maps Scraper (`compass/crawler-google-places`)
- **Data Destination:** Google Sheets
- **Workflow Format:** JSON

## 🔧 Setup

1. Download `scraping_project_redacted.json` from this repository.
2. In n8n, import the JSON workflow.
3. Connect your Apify and Google Sheets credentials to the relevant nodes.
4. Review the scraper input and adjust the search term or result limit if needed.
5. Click **Execute workflow** to run it.

## 🔐 Credentials

Credentials are not included in the exported workflow. Add your own Apify and Google Sheets connections in n8n before running it.


