# Fitfinity Staff PWA Preview v0.10

Static UI/PWA prototype for phone testing. This build is not connected to the production backend or database and must use dummy data only.

## v0.10 changes

- Client Overview no longer lists every current-package session.
- Client Progress now uses one exercise dropdown so the selected chart appears immediately.
- Added Export Progress Report. On supported browsers this opens a print-ready report so it can be saved as PDF.
- Session Details top four cards are substantially more compact on mobile.
- Exercise-plan camera control now sits at the right of the exercise heading instead of below the exercise fields.
- Client contact editing moved to the edit icon beside the Client Profile heading. Only phone and email are edited there. The icon changes to Save and asks for confirmation.
- Health / Limitation Notes has its own independent edit/save icon and confirmation.
- Owner Trainer Profile editing moved to the edit icon beside the trainer heading. Read-only profile fields switch to inline inputs and the icon becomes Save.
- Trainer rate changes require an Effective From date, preserving the intended historical remuneration model.
- Owner Session Details editing moved to the edit icon beside Session Details. Date, time and trainer become editable inline; Save asks for confirmation. Completed sessions remain locked.
- The old Owner Session Management panel is removed.
- PWA cache bumped to v10.

## Install/update test

Upload the contents of this folder to the root of the public GitHub Pages test repo. GitHub Pages redeploys automatically after commit. Refresh the Pages URL once in Chrome, fully close the installed PWA, and reopen it.
