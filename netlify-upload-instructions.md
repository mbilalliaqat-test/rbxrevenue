# Netlify Upload Instructions

## Fastest method

1. Go to Netlify.
2. Choose “Add new site”.
3. Choose “Deploy manually”.
4. Drag the full ZIP package or the extracted folder into Netlify.
5. Wait for deployment.
6. Open the temporary Netlify URL.
7. Test:
   - homepage loads
   - calculator tabs work
   - copy result works
   - download planner works
   - blog pages load
   - about/privacy/terms pages load

## After deployment

Replace `your-domain.com` in these files before final launch:

- `sitemap.xml`
- `robots.txt`
- blog canonical tags
- about/privacy/terms canonical tags

## Brutal warning

Do not publish with `your-domain.com` still inside the files if you are serious about SEO.
That is sloppy and avoidable.
