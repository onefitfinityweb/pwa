# Fitfinity v0.6 UI Wiring Audit

## Staff portal wiring completed
- Client onboarding: flexible availability -> trainer match -> final fixed schedule -> save/edit assignment -> create client.
- Client edit / health notes.
- Trainer onboarding and trainer edit popup, including Active / Inactive / Password reset state.
- Trainer directory search/status/public-profile filters.
- Trainer approved availability editing and saving.
- Trainer availability change request -> owner review -> approve/reject.
- Session date/time edit and ad-hoc trainer reassignment.
- Session details and exercise plan edit/view states.
- Exercise Library Add and Edit popups.
- Content Management editor and publish-selection popup.
- Copy Previous Plan confirmation popup.
- Trainer profile edit request popup.
- Remuneration breakdown popups.
- Calendar event/day-session popups.
- Signature/acknowledgement popup.
- Exercise camera/caption popup with start/stop recording UI state.
- WhatsApp share popup remains re-sendable after completion.

## Static audit result
Every button inside the staff portal has an explicit click handler. No staff-portal button is currently left inert or wired directly to a toast-only placeholder.

## Intentionally not real yet
These require backend/device/external integration rather than more UI wiring:
- Secure authentication and RBAC.
- PostgreSQL persistence.
- Real camera capture, upload, FFmpeg caption burn-in and 30-day retention deletion.
- WhatsApp actual send/delivered/read status.
- Glofox API authentication/sync.
- Email/invite delivery for trainer accounts.
