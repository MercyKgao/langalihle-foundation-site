User-agent: *
Allow: /

# Block non-public or irrelevant paths
Disallow: /api/
Disallow: /.git/
Disallow: /node_modules/
Disallow: /private/
Disallow: /admin/
Disallow: /tmp/
Disallow: /drafts/
Disallow: /search

# Optional crawl control
Crawl-delay: 5

# Sitemap (update domain later)
Sitemap: https://YOUR-DOMAIN-HERE/sitemap.xml
# Langalihle Foundation NPO Website

This is a lightweight, accessible static website for **Langalihle Foundation NPO**, built with:
- HTML5
- Tailwind CSS (via CDN)
- No build tools required

The site is PWA-ready, SEO-friendly, and easy to deploy.

---

## Project Structure


---

## Open Locally (Recommended)

### Option A: VS Code Live Server (Easiest)
1. Open Extensions in VS Code
2. Install **Live Server**
3. Right-click `index.html` → **Open with Live Server**

### Option B: Python server
```bash
python -m http.server 5500
