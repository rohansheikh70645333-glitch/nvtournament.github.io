NV ESPORTS — FINAL PWA PACKAGE

Changes in this package:
- Removed payment screenshot upload from the user deposit form.
- Deposit requests now require amount + UTR only and still go to the admin for approval.
- Removed the screenshot viewer/button from the admin payment list.
- Kept UPI QR, UTR, admin approve/reject, withdrawal, tournament and other existing app logic.
- Added an Install NV Esports App button and PWA manifest/service worker; bumped service-worker cache to v3.
- Added required PWA icons.

DEPLOY TO THE EXISTING VERCEL PROJECT (keep the same domain):
1. Extract this ZIP.
2. Upload/replace the files at the ROOT of the SAME connected GitHub repository: index.html, admin.html, manifest.json, service-worker.js, README-DEPLOY.txt, and the icons folder containing icon-192.png and icon-512.png.
3. Commit changes to the main branch. Wait for Vercel deployment to show Ready.
4. Open https://nv-e-sports.vercel.app in Chrome and refresh. If the old installed app still shows old content, close it and reopen; if needed remove the old home-screen shortcut and add it again.

PWA INSTALL:
- Open the HTTPS website in Chrome. Tap INSTALL NV ESPORTS APP. If Chrome does not offer the prompt, use Chrome menu (⋮) > Install app / Add to Home screen.

Important: This is a website/PWA package, not a compiled APK. Test Google login, deposits, admin approval, tournament joining and other features after deployment.
