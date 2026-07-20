# Add persistent storage and models

Migrate from the current in-memory `activities` structure to a persistent database.

Tasks:
- Add models for `Activity`, `Participant`, `Event`, `Membership`, and `Ticket`.
- Add database migrations and development configuration (SQLite for local, Postgres for production).
- Add unit tests for model behavior and API endpoints.

Labels: feature, backend
