# Saraz Pasni Rental — deployed website

**Live site URLs (free hosting):**

- https://saraz-pasni-rental.netlify.app  ← primary, root path
- https://sushant-me.github.io/saraz-pasni-rental/  ← GitHub Pages mirror

This repository contains only the production build of the **Saraz Pasni Rental**
website — a React + Vite site for authentic traditional Nepali Pasni sets and
backdrop decorations in Melbourne, Australia.

- Pages: Home, Packages, Gallery, About, Contact
- Build: `npm run build` with `VITE_BASE_PATH=/saraz-pasni-rental/`
- SPA fallback: `404.html` (copy of `index.html`) for direct navigation on
  client-side routes such as `/packages`, `/gallery`, `/about`, `/contact`
- Hosting: GitHub Pages (free `*.github.io` subdomain), branch `main`, path `/`

The source project is maintained in a separate, private repository.
