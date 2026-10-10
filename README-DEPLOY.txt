NV ESPORTS — UPDATED PWA PACKAGE

Changes made:
- Removed deposit screenshot upload from the public app. Deposits continue to use amount + UTR and admin approval.
- Removed screenshot viewing from the admin panel.
- Added an Install NV Esports App action on the login screen and app header. Supported browsers can show the install prompt; otherwise users get instructions for Chrome/Safari's Add to Home Screen option.
- Kept existing Firebase configuration and other app features unchanged.

VERCEL DEPLOYMENT
1. Upload/deploy the contents of this folder at the ROOT of the Vercel project (not inside another nested folder).
2. Keep the icons folder structure exactly as provided.
3. After deploy, check https://YOUR-DOMAIN/manifest.json and https://YOUR-DOMAIN/service-worker.js
4. Open the website in Chrome on Android. Tap INSTALL NV ESPORTS APP, or use Chrome menu (⋮) > Install app / Add to Home screen.
5. Test Google login, deposits (amount + UTR), admin approval, tournament joining, and room/pass visibility.

NOTE: Website installation creates an installable PWA, not a Play Store listing or a newly signed APK/AAB.
