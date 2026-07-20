# Suggested Issues Generated from penn-clubs Comparison

These are suggested GitHub issues representing features from the `penn-clubs` project that are not present in this repository. Create them as issues in GitHub if you want; this file records their titles and descriptions so you can copy/paste.

1. **Add persistent storage and models**
   - Migrate from in-memory `activities` to a proper database.
   - Add models for Activity, Participant, Event, Membership, Ticket.
   - Include migrations and tests; prefer SQLite/Postgres for development.

2. **Implement membership roles and permissions**
   - Add roles (owner/officer/member), membership invites and requests.
   - Implement role-based access control on endpoints.

3. **Add events and calendar support**
   - Create Event and EventShowing models; support types and multi-showings.
   - Add ICS import to sync external club calendars.

4. **Implement ticketing and payments**
   - Add Cart and Ticket models, QR generation, transfer records.
   - Integrate with a payment gateway (e.g., CyberSource or Stripe) and store transaction records.

5. **Club applications and recruitment workflow**
   - Add application cycles, committees, questions, and submissions handling.
   - Support acceptance/rejection templates and release windows.

6. **Advanced search and filtering**
   - Add tags/categories and filter endpoints; implement ranking and caching.

7. **Subscriptions, favorites and email notifications**
   - Allow users to subscribe to clubs, favorite items, and receive email blasts.

8. **Asset uploads and thumbnail generation**
   - Implement file upload endpoints, validate files (e.g., constitution), and generate thumbnails.

9. **Admin and moderation tools**
   - Add approval workflow, admin templates, reports, and history tracking.

10. **Analytics and reporting**
    - Track club page visits and search queries; add exportable reports and ranking weights.

11. **Realtime notifications (WebSockets)**
    - Add WebSocket consumers for notifications and realtime updates.

12. **Email templates and helpers**
    - Centralize email templates, add text/html rendering and attachment support (QR codes), include retry logic.

---

To convert these into live GitHub issues, create one issue per section above and label them `feature` / `backend` as appropriate.
