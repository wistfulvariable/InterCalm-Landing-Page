---
name: InterCalm hosting and infrastructure
description: GitHub Pages hosting, Porkbun DNS, DreamHost email -- critical DNS records to preserve
type: project
---

GitHub Pages serves the site from master branch. Deploy = git push.

**Why:** Simplest free static hosting for a single-page site. No build step needed.

**How to apply:** Any code change just needs a push to master. Never modify DNS email records (MX, DKIM, SPF, DMARC) at Porkbun -- those route to DreamHost for email.
