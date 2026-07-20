Title: Add realtime notifications and WebSocket support

Description:
Add websockets/channels for realtime notifications (e.g., membership requests, ticket updates) and integrate a simple channel layer.

Acceptance criteria:
- WebSocket endpoints for real-time events.
- Channel layer configuration (Redis) or fallback long-polling approach.
- Example notification: membership request alert for owners.
