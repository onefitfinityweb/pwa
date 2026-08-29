# Fitfinity Staff PWA Preview v0.8

Mobile-first UI prototype for testing the Fitfinity owner/trainer staff workflow before backend integration.

## v0.8 changes

- Removed the global/top-left Back button.
- Removed Sign Out and Back to Previous from the hamburger drawer.
- Added a persistent Home button in the top bar that returns owner/trainer to their dashboard.
- The top-right account name/avatar is now the account entry point.
  - Owner: account details, Change Password, Sign Out.
  - Trainer: account details, masked peak/off-peak rates with eye reveal, approved availability, Request Availability Change, Change Password, Sign Out.
- Trainer account page no longer shows activity/remuneration/assigned-client dashboard content.
- Trainer availability-change request now uses the same multi-day availability block builder used during onboarding. It starts from current approved availability, can be edited, and is submitted to the owner as a proposed full weekly schedule.
- Completed sessions no longer show Owner Session Management controls.
- Fixed Exercise Library Edit not opening (incorrect media checkbox element reference).
- Exercise Library summary statistics are compact and match the scale of other page statistics.
- Owner and trainer remuneration breakdown statistics are compact.
- Remuneration session breakdowns now use responsive cards instead of wide tables, including expanded owner trainer groups, removing horizontal scrolling.
- Service-worker cache bumped to v8.

## Prototype limitations

This is still a UI/PWA prototype. Login, password changes, database persistence, file storage, video processing, WhatsApp delivery, Glofox and backend RBAC are not live yet. Use dummy data only.
