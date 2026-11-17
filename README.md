# Stacks Property Services website

Plain HTML and CSS. No build step and no framework. Upload the contents of this folder to your web host's public folder (often `public_html` or `www`).

## Files
- `index.html`: home page
- `residential.html`, `commercial.html`: service pages
- `blog.html`: blog index
- `frozen-pipes-fort-worth.html`, `foundation-watering-fort-worth.html`, `commercial-maintenance-checklist-fort-worth.html`: blog posts
- `css/styles.css`: shared styles (layout styles are also inline in each page)
- `images/stacks-logo.png`: logo and favicon
- `sitemap.xml`, `robots.txt`: for search engines and AI crawlers

## Before going live
1. Fill in the remaining [bracketed placeholders]: two rental listings, commercial plan prices and response time. Search the HTML files for "[" to find them.
2. When ready, add your phone number and street address to the LocalBusiness schema (the `application/ld+json` block in each page's head), using `"telephone"` and `"streetAddress"`.
3. Replace the remaining striped placeholder boxes (two rental listings, founder photo) with real photos (`<img src="images/your-photo.jpg" alt="...">`).
4. If the domain isn't https://stacksps.com, update the canonical URLs, sitemap.xml and robots.txt.
5. Submit sitemap.xml in Google Search Console.

## Notes
- The quote buttons link to your existing Smartsheet quote form.
- Each blog post includes BlogPosting, FAQPage and BreadcrumbList schema. When you update a post, change the "Last updated" date on the page and `dateModified` in its schema.
- Moving off WordPress? Add 301 redirects from old URLs (for example /non-tenants/ to /residential.html) so search rankings carry over.
