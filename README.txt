CLIPNOVA AI V2 — FRONTEND STARTER

FILES
- index.html: responsive V2 interface and retained V1 local clip editor
- manifest.webmanifest: installable PWA metadata
- sw.js: offline app-shell caching
- icon.svg: updated app icon

WHAT WORKS
- Local video upload and preview
- Manual start/end trimming and WebM recording where browser APIs support it
- YouTube link preview (not downloading or extracting)
- PWA install prompt and basic offline app shell
- V2 interface with pricing and roadmap previews

NOT YET IMPLEMENTED
This is a static frontend package. It does NOT yet provide real registration/login, server-side 400-credit grants, AI highlight detection, automatic captions, MP4/1080p encoding, secure admin roles/unlimited credits, payment processing, subscription activation, or the first-100 discount counter. These require a secure backend and payment verification. Do not put secrets, passwords, OTPs, or private payment credentials in frontend code.

PRICING PLAN DISPLAYED
Nepal NPR 100/month; India INR 100/month; other countries USD 1/month. First 100 verified Premium subscribers: 50% off first period, once implemented server-side.
Payment methods planned: Nepal eSewa QR and bank transfer; India and other countries bank transfer.

GITHUB PAGES
1. Extract this ZIP.
2. Upload the four app files to the ROOT of your existing clipnova-ai repository, replacing old versions after keeping a backup.
3. Keep GitHub Pages configured for main / (root).
4. Open your Pages URL in Chrome and refresh. If an older version remains, clear site data or unregister the old service worker once.
5. On Android Chrome, use menu > Install app / Add to Home screen.

TEST
Use a short MP4, choose start/end, tap Create clip, and keep the page open. Export is WebM and browser/device support varies. Only clip videos you own or have permission to use.
