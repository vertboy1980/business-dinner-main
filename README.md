# Business Time

Mockup one-pager for an invite-only Auckland business-dinner series. Static site, no build step.

## Local preview

Just open `index.html` in a browser, or run any static server from this directory:

```sh
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy

Hosted on GitHub Pages, served direct from `main`.

**Setup:** repo settings → **Pages** → **Source: Deploy from a branch** → **Branch: main / (root)**.

## Structure

```
index.html           # the page
assets/style.css     # all styles
```

Stock photos are loaded from Unsplash CDN — swap the URLs in `index.html` and `assets/style.css` for real photos when ready.
