# Fitfinity Staff PWA Preview v0.13

Static UI/PWA prototype for phone testing. This build is not connected to the production backend or database and must use dummy data only.

## v0.13 changes

- Session editing now uses the same text-based `Edit` / `Save` / `Cancel` controls as Client Profile.
- Removed remaining session pencil/save glyph states.
- Exercise Plan view mode shows only `Edit`.
- `Add Exercise`, `Save`, and `Cancel` are hidden until `Edit` is selected.
- Added a CSS visibility override so mobile responsive flex rules cannot force hidden Exercise Plan actions back on-screen.
- Existing v0.12 production UI cleanup, camera positioning, progress export, and edit-state behavior are retained.
- PWA cache bumped to v13.

## Install/update test

Upload the contents of this folder to the root of the public GitHub Pages test repo. GitHub Pages redeploys automatically after commit. Refresh the Pages URL once in Chrome, fully close the installed PWA, and reopen it.
