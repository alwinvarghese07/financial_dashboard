# StayTransit — Financial Administration Redesign

Redesigned financial admin console for StayTransit, featuring unified styling, stat ribbons, multi-criteria filtering, and data tables with responsive controls.

## Screens Included

- **Daily Revenue (`index.html` / `daily_revenue.html`)**: Checkout revenues across Merchant & Partner channels, Package Tax, Global Tax, and Net Revenue calculations.
- **Consolidated Revenue & Payouts (`consolidated_revenue.html`)**: Unified revenue tracking and complete payout lifecycle management (Pending, Scheduled, Completed, Overdue) with interactive settlement actions and modal dialogs.
- **Wallet Transactions (`wallet_transaction.html`)**: Partner credit/debit audit logs, security deposits, and deduction clearing lifecycles.
- **Redirects & Legacy Routing**: `completed_payout.html` and `consolidated_tracking.html` redirect to the consolidated ledger.
- **Styling (`styles.css`)**: Centralized design system styles, tokens, layout grid, badges, and components.

## Running Locally

Run a local static HTTP server:

```bash
# Using Python
python -m http.server 3000

# Or using Node.js / npx
npx serve -l 3000 .
```

Open [http://localhost:3000](http://localhost:3000) to view the console.
