# Werkbank prototype

Clickable prototype for the Capstone B8AF124 group project (Werkbank: one AI platform for small Munich Handwerk businesses). Single HTML file, no build step, sample data only, no real AI or bank calls.

Four views: Reception (simulated AI call, German transcript with English gloss, fills a job card), Job inbox (stage board), Hub (customer timeline + receipt reading), Insights (KPIs, chart, plain-language advice). A Basis/Komplett switch locks the phase 2 views.

Open `public/index.html` in a browser, or deploy to Cloudflare Workers with `npx wrangler deploy` (static assets only, see `wrangler.jsonc`).
