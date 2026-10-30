# DIGANTANIYOG (দিগন্তনিয়োগ)

A responsive Bengali/English government-job information portal for West Bengal, Railway, SSC and Central Government recruitment.

## Deploy to Cloudflare Pages
1. In Cloudflare, open **Workers & Pages** → **Create** → **Pages** → **Connect to Git**.
2. Select `ranitdas0055-sys/digantaniyog`.
3. Framework preset: **None**.
4. Build command: `exit 0`.
5. Build output directory: `.` (repository root, where `index.html` lives).
6. Save and deploy.

The site is a static HTML/CSS/JS site and does not need a build step.

## APK
The Photo & Signature Resizer app remains in the separate repository:
https://github.com/ranitdas0055-sys/rd-photo-signature-resizer

The website links to the app's GitHub Releases page. Publish a release APK there for direct downloads.

## Important limitations
- The Admin Quick Panel is a browser-local demo only. It is not a secure admin system and posts are not shared between visitors.
- Job links are official portal links, not claims of currently open vacancies. Always verify recruitment dates, eligibility, fees and vacancies in the official notification.
- DIGANTANIYOG is an independent information portal, not a government website.
