# HARUMI LLC Corporate Website

Static production-ready website for HARUMI LLC / 合同会社晴海.

## Structure

- `index.html` - Japanese default redirect page
- `en/index.html` - English homepage
- `ja/index.html` - Japanese homepage
- `zh/index.html` - Chinese homepage
- `assets/css/styles.css` - responsive corporate styling
- `assets/js/main.js` - navigation and reveal interactions
- `assets/img/logo.svg` - SVG logo
- `assets/img/favicon.svg` - SVG favicon
- `robots.txt` and `sitemap.xml` - search engine support
- `CNAME` - GitHub Pages custom domain for `harumi-trade.com`
- `404.html` - static fallback page

## Deployment

This site uses only HTML, CSS and JavaScript. It is ready for GitHub Pages or Cloudflare Pages with the project root as the publish directory.

For Cloudflare Pages, set the build command to empty and the output directory to `/`.
