# Fitfinity PWA phone preview

This folder is only for testing the **installed phone experience and current wireframe UI**.

## Important
The HTML still contains the wireframe's prototype login behaviour. It is **not production authentication**. Use dummy data only.

## Test
1. Host this folder over HTTPS.
2. Open the HTTPS URL with `?staff=1`.
3. iPhone: Safari -> Share -> Add to Home Screen.
4. Android/Chrome: menu -> Install app / Add to Home screen.
5. Launch the icon; it should open straight into the Staff Portal login in standalone mode.

The public Staff Portal navigation button has been hidden in this preview.

## What to test
- owner and trainer responsive layouts
- weekly/monthly calendars
- drawer and back behaviour
- modal scrolling
- input ergonomics
- exercise planning flow
- camera/video button placement

Do not use real customer information until the login is replaced by real `/api/auth/login` and backend authorization is active.
