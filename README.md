# Robert Hrastnik - Multilingual Welding Profile Website

Static SEO-first website for GitHub Pages with German, Croatian and English pages.

## Structure
- /de/ German homepage (primary market)
- /hr/ Croatian homepage
- /en/ English homepage
- /assets/css/main.css visual system + SVG animations
- /assets/js/app.js viewport reveal behavior
- /robots.txt and /sitemap*.xml multilingual SEO files
- /.github/workflows/deploy.yml automatic GitHub Pages deployment

## Before launch
1. Replace itforsociety in all canonical, hreflang, robots and sitemap URLs.
2. Update phone number in DE/HR/EN pages.
3. Set Formspree endpoint in all forms: https://formspree.io/f/your-form-id
4. Keep profile photo file as /profilePicture.jpg (already in project root).
5. Optional optimization later: export WebP/JPG variants for faster loading.

## Local test
Open index.html directly or run a local server:

```powershell
cd c:\webstranice\RobertHrastnik
python -m http.server 8080
```

Then open http://localhost:8080 and test /de/, /hr/, /en/.

## Deploy
Push to main branch. GitHub Actions workflow will publish to GitHub Pages.
