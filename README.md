# Fitfinity Staff PWA Preview v0.7

Mobile UX test build only. Use dummy data; authentication and persistence are still prototype-only.

## v0.7 changes
- Client preferred availability now uses the same multi-day block builder as trainer onboarding: select multiple possible days, choose From/To, then Add Block. Repeat for different time windows.
- Trainer matching still happens only after the client availability blocks are entered. For Double Day, a trainer must match at least two different days before the owner chooses and saves the final two fixed slots.
- Removed the four summary cards from Trainer Dashboard. They now live on their relevant pages: Assigned Clients on All Clients; Today and Not Planned on All Sessions; Completed Hours This Month on Remuneration.
- Owner and trainer Month calendars now fit all seven days across the phone viewport with no horizontal scrolling. Owner month keeps daily session totals; trainer month keeps compact client names.
- Added portal-wide mobile overflow protections. Tables and detail views collapse secondary columns rather than scrolling sideways.
- Service worker cache bumped to fitfinity-staff-ui-v6.

## Deploy
Replace the files in the public GitHub Pages test repo with the contents of this folder and commit. GitHub Pages should redeploy automatically. Open the Pages URL in Chrome once and refresh, then fully close/reopen the installed PWA.
