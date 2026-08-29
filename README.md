# Fitfinity Staff PWA Preview v0.11

Static UI/PWA prototype for phone testing. This build is not connected to the production backend or database and must use dummy data only.

## v0.11 changes

- Client, trainer and owner session edit/save controls are now aligned at the top-right of their page headers instead of dropping underneath on mobile.
- Every header edit state now exposes a Cancel button beside Save.
- Leaving a page/section with unsaved edits prompts for confirmation. Confirming leave discards edit mode, so reopening the page returns to read-only view.
- Client Progress keeps the exercise selector immediately available and moves Export Progress Report to the top-right.
- Exercise Plan uses the same top-right edit icon. Edit mode exposes Add Exercise, Save and Cancel.
- Exercise camera is now on the far right of the same row as the exercise selector/name.
- Session Outcome is read-only by default with its own top-right edit/save/cancel controls for duration and trainer comments.
- Client-Facing Summary is read-only by default, auto-generated from the plan and duration, with its own top-right edit/save/cancel controls for wording adjustments.
- Completed sessions continue to hide/lock editing; WhatsApp resend remains available.
- Trainer My Account Approved Availability is condensed into a two-column compact day/time list.
- Client Onboarding modal receives additional mobile width constraints to eliminate horizontal scrolling.
- PWA cache bumped to v11.

## Install/update test

Upload the contents of this folder to the root of the public GitHub Pages test repo. GitHub Pages redeploys automatically after commit. Refresh the Pages URL once in Chrome, fully close the installed PWA, and reopen it.
