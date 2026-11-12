# Personal Financial Management Tracker

An offline browser-based application for organizing personal
finances, monitoring expenses, and tracking financial commitments.

## Features

- Financial dashboard with charts and summary indicators.
- Loan and installment tracking.
- Payment schedules and payment status management.
- Actual transaction tracking.
- Planned and daily expense management.
- Reports and financial analysis.
- Multiple local profiles.
- Configurable lookups and settings.
- Audit history.
- Light and dark themes.

## Import and Export

- Import daily expenses from supported CSV and Excel files.
- Extract transaction details from supported pasted bank messages.
- Preview imported records and review validation results.
- Review duplicate warnings before importing daily expenses.
- Import and export payment schedules.
- Export supported records as CSV.
- Export payment schedules in Excel-compatible format.
- Download and restore full JSON backups.

Bank message recognition depends on the message format.
Review extracted values before confirming an import.

## Getting Started

1. Select Code → Download ZIP.
2. Extract the downloaded ZIP file.
3. Open index.html in a modern browser.
4. Review any sample records before entering your own data.
5. Configure your profile and settings.
6. Add your loans, schedules, transactions, and expenses.

No application server or external API is required.

## Data Storage

Financial records are stored locally in your browser using
IndexedDB, with local storage as a fallback.

Data is specific to your browser, browser profile, and
application location. It does not automatically synchronize
between devices.

Use the same browser and keep the application in a stable
location. Export a backup before moving or replacing the file.

Local profiles organize datasets within the application.
They are not separate authenticated user accounts.

## Backup and Restore

1. Open Import / Export.
2. Download a full JSON backup.
3. Keep the backup in a secure location.
4. Use the restore option when recovering or transferring data.

Restoring a full backup replaces the current dataset.
Export the current data before restoring another backup.

Clearing browser data can remove saved financial records.
GitHub stores the application source code, not your
browser-stored financial records.

## Privacy

Financial data is processed locally.
The application does not connect to your bank or automatically
retrieve transactions.

Keep financial backups and transaction files private.

## Technology

- HTML
- CSS
- JavaScript
- IndexedDB
- Browser local storage fallback

## Updates

Export a full backup before updating the application.

Replace index.html with the latest version and use a
descriptive commit message. GitHub preserves the source
code's version history.
