# Joscha Hoche

Minimal personal website for [hochej.com](https://hochej.com).

## Local development

This is a static site. No install step needed.

```sh
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

## Editing

- Main content: `index.html`
- Styling: `styles.css`
- Metadata: `<head>` in `index.html`

## Cloudflare Pages

Import this repository into Cloudflare Pages.

- Framework preset: `None`
- Build command: leave empty
- Build output directory: `/`
- Production branch: `main`

Attach `hochej.com` as the custom domain in Cloudflare Pages.
