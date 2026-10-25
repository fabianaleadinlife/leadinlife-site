# Lead in Life — website

Static site for www.leadinlife.com. Plain HTML and CSS, no build step.

- `index.html` — home
- `coaching/`, `learning/`, `design/`, `about/`, `contact/`, `privacy/` — one folder per page
- `styles.css` — all styling; colours and fonts are defined at the top
- `netlify.toml` — hosting config and redirects from the old WordPress URLs
- `images/` — photos (add `fabiana-portrait.jpg` and `fabiana-working.jpg`, then uncomment the `<img>` tags)

To publish: connect this repository to Netlify (or Cloudflare Pages). Every push to `main` deploys automatically.

Before go-live: add photos, paste the Calendly link in `contact/index.html`, write the privacy page, confirm client names in the "Trusted by" strip.
