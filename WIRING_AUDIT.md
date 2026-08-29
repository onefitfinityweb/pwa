# Fitfinity PWA v0.7 — UI Wiring / Mobile Overflow Audit

- Client availability builder: multi-day chips + From/To + Add Block; added blocks feed trainer matching.
- Single Day requires one final matched slot; Double Day requires two different final matched days.
- Saved trainer + fixed schedule remains editable before client creation.
- Trainer dashboard stats removed and placed on Clients / Sessions / Remuneration pages.
- Owner Month calendar: complete 7-column month visible; daily session-count summary opens existing day popup.
- Trainer Month calendar: complete 7-column month visible; compact client-name events still open session details.
- Mobile portal root and table containers explicitly prevent horizontal overflow. Secondary columns in dense history/remuneration tables are hidden on phone rather than requiring sideways scroll.
- Existing staff portal popup/button wiring retained from v0.6.

Still intentionally simulated until backend/device integrations are built: secure login/RBAC, persistence, actual camera/upload/transcoding, WhatsApp delivery, Glofox API.
