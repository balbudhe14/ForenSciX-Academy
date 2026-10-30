# ForenSciX Academy — starter prototype

## What this is
A mobile-friendly PWA-style front-end prototype with:
- Course catalogue and course detail pages
- Local demo student profile
- Demo enrollment and lesson completion tracking
- Sample MCQ quiz with scoring and explanations
- Demo admin area to add/delete sample courses
- Basic PWA manifest and service worker

## Run locally
Open `index.html` in a modern browser. For service-worker/PWA testing, serve the folder over HTTPS or localhost.

## Important limitations
This is a front-end prototype, not a production learning management system.
- Data is stored in the current browser's localStorage; friends will NOT share accounts, courses, or progress.
- The demo profile and admin area are not secure authentication.
- There is no real payment processing, private video hosting, backend database, or certificate verification.
- Do not upload confidential student data or sell courses through this prototype.
- Before public commercial use, connect a real backend (e.g. Supabase), implement server-side authorization and payment verification, configure private video delivery, add privacy/terms/refund policies, and test security.

## Free deployment route
1. Create a GitHub account.
2. Create a public repository named `forenscix-academy`.
3. Upload `index.html`, `manifest.json`, and `sw.js`.
4. In repository Settings → Pages, choose Deploy from branch, select `main` and `/root`.
5. GitHub Pages will provide a public HTTPS URL. You can share that URL with friends to preview the prototype.
6. For a true multi-user app, connect a backend before treating it as a real student platform.

A custom domain and official Apple App Store / Google Play publishing are not included.
