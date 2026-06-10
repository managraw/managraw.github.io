# Manu Agrawal personal website

Static personal website for `manuagrawal.com`, designed for GitHub + Cloudflare Pages deployment.

## Files

- `index.html` - homepage
- `about.html` - professional narrative and thesis
- `work.html` - selected public work and impact themes
- `media.html` - press and expert commentary
- `publications.html` - publications and technical writing hub
- `service.html` - peer review, think tank, and roundtables
- `recognition.html` - memberships, awards, and affiliations
- `contact.html` - contact page
- `style.css` - global styling
- `sitemap.xml` and `robots.txt` - search discovery helpers
- `_headers` - basic Cloudflare Pages security headers
- `CNAME` - custom domain marker for GitHub Pages compatibility

## Before publishing

1. Replace the LinkedIn placeholder in `contact.html` with your exact LinkedIn URL.
2. Add exact paper titles and citations to `publications.html` only after acceptance or public availability.
3. Add award names to `recognition.html` only where the award name, year, issuer, and selection context can be publicly shared.
4. Confirm that all employer-related claims are public and non-confidential.

## Deployment with Cloudflare Pages

1. Create a GitHub repository, for example `manuagrawal-site`.
2. Upload all files in this folder to the repository root.
3. In Cloudflare Pages, connect the GitHub repository.
4. Use these settings:
   - Framework preset: `None`
   - Build command: leave blank
   - Build output directory: `/`
5. Add the custom domain `manuagrawal.com` in Cloudflare Pages.
6. After deployment, submit `https://manuagrawal.com/sitemap.xml` in Google Search Console.

## Important note on search indexing

Google Search Console can request crawling and indexing, but no static site can guarantee first-page ranking or immediate indexing. The site includes clean internal structure, direct outbound links to public media coverage, and Schema.org markup to help search engines understand the identity and content.
