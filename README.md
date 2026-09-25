# NETWORK_GHOST — Cybersecurity Portfolio

A fast, responsive, dependency-free cybersecurity portfolio built with semantic HTML, CSS and vanilla JavaScript.

## Features

- Responsive mobile/tablet/desktop layout
- No frameworks or third-party JavaScript
- No analytics or tracking
- Accessible keyboard navigation and reduced-motion support
- Strict CSP baseline in the document
- Production security-header checklist
- Mobile navigation with minimal JavaScript
- Static-site friendly for GitHub Pages, Netlify, Cloudflare Pages, Vercel, etc.

## Before deployment

1. Replace `your-email@example.com` in `index.html`.
2. Replace the LinkedIn and GitHub placeholder URLs.
3. Add your actual project repository links if desired.
4. Configure the HTTP security headers from `security-headers.txt` in your hosting platform.
5. Serve only over HTTPS.
6. Do not place API keys, passwords, tokens or private files in the repository.

## Run locally

Open `index.html` directly, or use any static server.

Example:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deployment

This is intentionally backend-free. If you later add a contact form, authentication, APIs or a CMS, treat that as a separate security boundary and add server-side validation, CSRF protection, rate limiting and appropriate authentication controls.
