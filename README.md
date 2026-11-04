# Studio Tubi website

A one-page company website for Studio Tubi, served at **https://studiotubi.com**. It's the public website Apple asks for when enrolling Studio Tubi in the Apple Developer Program as an organization.

It's plain HTML and one CSS file: no build step, no framework, no JavaScript, no cookies or analytics.

- `index.html`: the page
- `assets/style.css`: styles (editorial look: warm paper, classic serif, thin rules; follows the visitor's light/dark setting)
- `404.html`: not-found page

## Preview locally

```bash
python3 -m http.server 8080
```

Then open http://localhost:8080.

## Deploying

The site is published with GitHub Pages from the `main` branch (repository root). Every push to `main` updates https://studiotubi.com within a minute or two. The `CNAME` file tells GitHub Pages which domain to serve.
