````markdown
# Noayck — Static Dashboard and Site

This commit adds a full static front-end for Noayck (wearenoyack.com) built with HTML, CSS and JavaScript only. It includes:

- index.html — marketing/home page
- dashboard.html — admin dashboard with charts, stats and quick-actions
- members.html — member directory
- courses.html — course catalog
- resources.html — resources and guides
- settings.html — basic settings mock
- 404.html — fallback page
- assets/css/style.css — shared styles
- assets/js/app.js — shared client-side data and utilities
- assets/js/dashboard.js — dashboard-specific logic and charts

How to use
1. Serve these files from any static host (GitHub Pages, Netlify, Vercel).
2. Open `index.html` or `dashboard.html` in the browser.

Notes and next steps
- This is a static prototype — replace the sample data with real API calls for live data.
- Consider adding a simple auth flow, server routes, and a CMS to manage courses/members.
- I included Chart.js via CDN in dashboard.html.
````