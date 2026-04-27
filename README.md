# Klozr

Marketing site for **Klozr** — the Autonomous Sales Execution Layer.

- Single-file static site (`index.html`) — vanilla HTML / CSS / JS, no build step.
- Deployed via **Cloudflare Pages** at **[aiklozr.com](https://aiklozr.com)**.

## Local dev
Just open `index.html` in a browser, or serve the folder:

```bash
python -m http.server 8080
# or
npx serve .
```

## Deploy
Pushes to `main` deploy automatically via Cloudflare Pages (GitHub integration).

## Stack
- HTML / CSS / JS only
- Cloudflare Pages (hosting + DNS + TLS)
- GitHub (source of truth)
