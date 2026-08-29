# Fitfinity Staff PWA Preview v0.14

Mobile UI prototype for owner/trainer workflow testing. Use dummy data only; authentication and persistence are still simulated.

## v0.14 changes
- Session header statuses are compact and stay in one row.
- Bottom session actions are reduced to `Acknowledge Session` and `WhatsApp Client`.
- Week calendar date range now occupies the centre navigation button; the separate range label and `Today` wording are removed.
- Owner trainer profile shows the first 5 assigned clients with a searchable/filterable `View All` popup.
- `10-Session Follow-Up` is renamed `Upcoming Renewals`, shows the first 5, and has a searchable/filterable `View All` popup.
- Trainer monthly calendar now matches the owner month format: one session-count card per day, tap to expand that day's sessions.
- Added left-to-right swipe-back gesture from the left side of mobile portal screens.
- Service-worker cache bumped to v14.

No backend, real RBAC, database persistence, Glofox sync, real camera upload, or WhatsApp delivery tracking is enabled in this preview.
