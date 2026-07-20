Title: Implement membership roles and permissions (owner/officer/member)

Description:
Add role-based membership management so clubs/activities can have owners, officers, and members with different permissions.

Acceptance criteria:
- `Membership` model linking users to activities with roles (owner, officer, member).
- Endpoints for invite, accept/decline membership, and role changes.
- Permission checks on endpoints (only owners/officers can manage activity details).
- Tests covering role enforcement.
