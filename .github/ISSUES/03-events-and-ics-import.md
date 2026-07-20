Title: Add events, showings, and ICS calendar import

Description:
Support events with multiple showings and ability to import club calendars via ICS URLs.

Acceptance criteria:
- `Event` and `EventShowing` models (name, description, url, start/end, location).
- API to create/update/delete events and showings.
- Background job or endpoint to import .ics from a URL and sync events.
- Frontend pages to list events and showings.
