Borrower Ledger PWA v4.1.1 - Click Fix

Fixed a JavaScript syntax error in CSV export initialization that prevented all click handlers from loading.

Deployment:
1. Back up current data if accessible.
2. Replace all hosted files with this package.
3. Clear the old site cache or uninstall the old PWA.
4. Open the hosted URL and refresh twice, then reinstall.

The browser storage keys are unchanged, so existing borrower and transaction data on the same origin/browser is retained.
