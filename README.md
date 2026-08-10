# Tumusiime, Kabega & Co. Advocates — website prototype

A static, single-page prototype for a commercial law firm website in Kampala, Uganda.

## Status

This is a **prototype**, not a production site. Placeholder content is marked inline in the
HTML (search for `PLACEHOLDER`, `[VERIFY:`, and `TODO`). Nothing on the page submits to a real
backend yet — see the TODO block near the top of the `<script>` in `index.html` for the full
list of outstanding backend work (enquiry/booking submission handling, PDF delivery, a CMS for
Insights articles, search indexing, analytics, and a live Google Maps embed).

## Files

- `index.html` — the entire site (structure, styles, and behaviour in one file)
- `robots.txt`, `sitemap.xml` — placeholder SEO files; update the domain before launch

## Running locally

No build step. Open `index.html` directly in a browser, or serve the folder with any static
file server, e.g.:

```
python -m http.server 8000
```
