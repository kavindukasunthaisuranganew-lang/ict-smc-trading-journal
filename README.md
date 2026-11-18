# TradeLog — ICT + SMC Trading Journal

A responsive, browser-based trading journal for Forex and Crypto practice.

## Features
- Dashboard: total trades, win rate, net P/L, average R, performance snapshot
- Trade history: add, edit, delete, search and filter trades
- Automatic R-multiple calculation from entry, stop, exit and direction
- ICT/SMC pre-trade checklist
- Weekly trading review
- Export trades as CSV and download/import a full JSON backup
- Responsive layout for desktop and mobile

## Data & privacy
This is a static website. Trades are stored in the browser's localStorage on the device/browser being used. They are not uploaded to a server and do not automatically sync between devices. Export backups regularly. Do not store passwords, broker credentials, API keys or sensitive account information.

## Run locally
Open `index.html` in a modern browser.

## Deploy to GitHub Pages
1. Create a **public** repository on GitHub, for example `ict-smc-trading-journal`.
2. Upload `index.html` and `README.md` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch **main** and folder **/(root)**, then Save.
6. Wait for the deployment. Your site URL will appear in the Pages section.

GitHub Pages serves static HTML/CSS/JavaScript files. This app does not require a build step or paid hosting.

## Important
Educational journaling tool only. It does not connect to a broker, execute trades, give trading signals, or provide financial advice. Verify position sizing and contract specifications with your broker/exchange.
