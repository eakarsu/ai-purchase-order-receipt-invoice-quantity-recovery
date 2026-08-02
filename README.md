# Purchase Order, Receipt & Invoice Quantity Recovery

Recover invoice overpayments caused by quantity, receipt, return, unit-of-measure, and tolerance mismatches.

**Primary buyer:** Enterprise procurement and accounts-payable teams. **Evidence:** purchase orders, releases, receipts, service entries, returns, invoices, units of measure, tolerances, payments, and credits.

Full local application built with React, Vite, Express, PostgreSQL, and OpenRouter. Includes 15 domain-specific capabilities, 105 custom AI workbench fields, three scenario-fill controls per feature, operational registers, workflow transitions, analytics, professional AI decision briefs, audit history, and at least 15 PostgreSQL records per capability.

## Domain capabilities

- Purchase order ingestion
- Release schedule control
- Goods receipt matching
- Service entry validation
- Return-to-vendor linkage
- Invoice line ingestion
- Unit-of-measure conversion
- Quantity tolerance control
- Duplicate receipt detection
- Short shipment analysis
- Three-way match calculation
- Payment overage detection
- Supplier claim workflow
- Credit reconciliation
- Buyer supplier analytics

Run `./start.sh`, then open <http://127.0.0.1:4701>. API: `5701`.

Administrator: `runtime-admin@example.com` / `LocalDemo!2026`. Operator and reviewer credential buttons are available on the login page.
