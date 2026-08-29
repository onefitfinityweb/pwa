# Fitfinity Staff PWA Preview v0.6

Mobile UX prototype for owner/trainer testing. Dummy data only — authentication, database persistence, real media upload and external integrations are not production-ready yet.

## v0.6 changes
- Reworked Client Onboarding into a two-stage scheduling flow:
  1. Record as many possible client availability day/time options as needed.
  2. Match trainers against those options.
  3. Single Day requires a trainer with at least 1 compatible day; Double Day requires at least 2 different compatible days.
  4. Owner selects the trainer, exact fixed day(s) and exact one-hour session start time(s).
  5. Owner saves/locks the trainer + recurring schedule; the saved assignment can still be reopened and edited before client creation.
- Couple remains a client-type selection only and reveals the second person's fields.
- Package choices are 12-session PT and 24-week PT.
- Double Day automatically includes free gym membership.
- Creating a client now adds the new client to the in-memory client directory so the flow can be tested end-to-end.
- Exercise Library Edit now opens a complete popup with name, category, status, description and media replacement/removal controls.
- Adding/editing an exercise updates the in-memory exercise library and session-planner dropdown source.
- Completed a staff-portal wiring pass: health-note editing, trainer create/edit/filtering, owner availability save, trainer availability request/owner review, content edit/publish popups, Copy Previous Plan popup, trainer profile edit request, plan draft status and exercise recording UI state.
- Staff portal buttons were audited for missing click handlers/direct toast-only placeholders; none remain in the portal UI.
- Unified trainer calendar "Not planned" navigation into Session Details instead of the legacy standalone planner screen.
- Service-worker cache bumped so installed Android PWAs can receive the new build.

## Important prototype limits
- Changes are stored only in browser memory and reset after a full reload/restart until the backend is connected.
- Camera recording UI is interactive but does not yet record/upload a real video.
- WhatsApp opens the prototype sharing flow; delivery tracking is not implemented.
- Glofox remains an external handoff placeholder.
- Prototype login is not secure. Do not use real client information yet.

Deploy the files in this folder to the GitHub Pages repository root.
