# FORSPIKE Website

Static brand site for FORSPIKE (Est. 2026). Single HTML page, no build step.

## Structure
```
index.html          Main page (HTML, CSS, JavaScript)
logo.png     Seal logo (hero)
logo-small.png  Header logo
favicon.png  Browser tab icon
og-image.png Social share card (1200x630)
robots.txt          Crawler rules
sitemap.xml         Sitemap for search engines
```

## Deploy on GitHub Pages
1. Push this folder to a repository (e.g. `forspike`).
2. Go to Settings > Pages.
3. Under "Build and deployment", choose Deploy from a branch, branch `main`, folder `/ (root)`.
4. Your site appears at https://forspike2026.github.io/FORSPIKE/ within a few minutes.

## Before launch
- Replace `YOUR-USERNAME` in index.html, robots.txt and sitemap.xml.
- Replace placeholder prices, copy and contact email.
- Connect the contact form (Formspree, Netlify Forms or your own backend).
- Add a privacy page if you collect personal data.
- To use a custom domain, add a file named `CNAME` containing your domain and update the URLs.
