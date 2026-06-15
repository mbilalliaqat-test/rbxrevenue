# Roblox DevEx Calculator — Deploy Package

This is a static, single-page calculator site.

## Files

- `index.html` — main calculator landing page
- `robots.txt` — search engine crawl file
- `sitemap.xml` — basic sitemap
- `netlify.toml` — Netlify config
- `favicon.svg` — simple favicon
- `seo-launch-checklist.md` — launch tasks
- `keyword-plan.csv` — keyword cluster
- `content-brief.md` — content expansion plan

## How to deploy on Netlify

1. Log in to Netlify.
2. Create a new site.
3. Drag and drop this whole folder or upload the ZIP file.
4. After deployment, replace `https://your-domain.com` inside:
   - `robots.txt`
   - `sitemap.xml`
   - canonical/metadata if you later add a real domain.
5. Submit the live URL to Google Search Console.

## Important calculator assumptions

The calculator uses default assumptions for estimation only:

- Normal DevEx rate: `$0.0038` per Earned Robux
- US 18+ eligible DevEx rate: `$0.0054` per Earned Robux
- Creator share for own in-experience sales: `70%`
- DevEx threshold reference: `30,000 Earned Robux`

Always verify current Roblox DevEx and monetization policy before publishing or making financial claims.


## Launch Kit Additions

- `/about/` — basic trust page
- `/privacy/` — starter privacy page
- `/terms/` — starter terms and disclaimer page
- `/404.html` — error page
- `/downloads/roblox-monetization-planner.xlsx` — lead magnet spreadsheet
- `/assets/analytics-hooks.js` — safe event hooks for future analytics

## Important

Before publishing, replace `your-domain.com` everywhere with the real domain.
Also update the privacy page if you install analytics, email capture, ads, or affiliate scripts.
