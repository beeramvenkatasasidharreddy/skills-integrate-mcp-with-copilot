Title: Implement ticketing, cart, and payments integration

Description:
Support paid events with carts, tickets, QR confirmations, and a payment gateway integration.

Acceptance criteria:
- `Cart` and `Ticket` models with ownership/transfer and attendance flags.
- Purchase flow integrating with a payment provider (stub/test gateway or CyberSource in future).
- Email confirmation with QR attachment after successful purchase.
- Admin view to manage tickets and view transaction records.

Notes:
Start with a test-mode payment simulator; do not store full card data.
