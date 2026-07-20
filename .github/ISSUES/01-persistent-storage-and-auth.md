Title: Add persistent storage and basic authentication

Description:
Currently activity data is stored in-memory which is lost on restart and not suitable for production. Add a persistent database (SQLite/Postgres) and implement user authentication.

Acceptance criteria:
- Move activities and participants to a database with models for Activity and Participant/Membership.
- Add user accounts and login/logout (FastAPI dependency or OAuth if preferred).
- Update API endpoints to use the database.
- Include migrations and seed/dev data script.

Notes:
Start with SQLite for simplicity, provide Postgres instructions for production.
