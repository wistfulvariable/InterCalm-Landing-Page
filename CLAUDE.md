# InterCalm Landing Page

## Product
InterCalm is a Wi-Fi home intercom system. Tagline: "Never yell across the house again."
Brand voice: warm, practical, calm. Not techy.

## Site
- **Domain:** getintercalm.com
- **Type:** Static holding/teaser page (single HTML file + favicon)
- **Design:** Variant 10 "Warm Aurora" — canvas-drawn flowing ribbon shapes in warm tones, Outfit font, staggered letter reveals, breathing background
- **Color palette:** Warm ivory `#FAF7F2`, soft beige `#F0EBE3`, deep warm charcoal `#2C2825`, muted warm gray `#8A8279`
- **Contact:** support@getintercalm.com

## Hosting & Deployment
- **Hosting:** GitHub Pages (free) from `master` branch
- **Repo:** github.com/wistfulvariable/InterCalm-Landing-Page
- **Deploy:** `git push origin master` (GitHub Pages auto-deploys)
- **SSL:** Auto-provisioned by GitHub Pages

## DNS (Porkbun)
- 4x A records pointing to GitHub Pages IPs (185.199.108-111.153)
- CNAME `www` -> `wistfulvariable.github.io`
- MX/DKIM/SPF/DMARC records for DreamHost email (do NOT touch)

## File Structure
- `index.html` — live landing page (copy of variant-10-warm-aurora.html with favicon + SEO title)
- `favicon.svg` — concentric ripple rings icon
- `CNAME` — GitHub Pages custom domain config
- `variant-01` through `variant-10` — design exploration variants (kept for reference)
- `viewer.html` — tabbed viewer to compare all variants
