# VV Creative Solutions — Corporate Website

A premium, single-page corporate/agency website for **VV Creative Solutions**, built with plain HTML, CSS and JavaScript (no build step, no dependencies beyond Google Fonts).

**Tagline:** Transforming Ideas into Digital Excellence

## Structure

```
index.html    → all page content and sections (Home, About, Services, Portfolio, Process, Testimonials, Pricing, FAQ, Contact, Footer)
styles.css    → design tokens, layout, glassmorphism, animations, responsive rules
script.js     → nav toggle, scroll reveal, stat counters, FAQ accordion, form handling, back-to-top
```

## Features

- Dark navy / royal blue theme with glassmorphism cards and gradient accents
- Animated aurora hero background + signature rotating "service orbit" visual
- Scroll-reveal animations, animated stat counters, smooth in-page navigation
- Fully responsive (mobile-first breakpoints at 1080px / 880px / 480px)
- Accessible: skip link, visible focus states, semantic landmarks, `prefers-reduced-motion` support
- SEO: meta description/keywords, Open Graph/Twitter tags, JSON-LD structured data
- Self-contained inline SVG icons and favicon — no icon-font or image requests, so it loads fast
- WhatsApp floating button, embedded Google Map, working client-side contact form validation

## Customize before launch

1. **Contact details** — replace the placeholder email, phone and WhatsApp number in `index.html` (search for `hello@vvcreativesolutions.com`, `+15551234567`).
2. **Map location** — update the `src` of the `<iframe>` in the Contact section with your real address.
3. **Social links** — swap the `#` placeholders in the footer `.socials` block for real profile URLs.
4. **Form submission** — the form currently shows a success message client-side only. Connect it to a real backend or a form service (e.g. Formspree, Netlify Forms) by changing the `<form>` `action`/`method` or the submit handler in `script.js`.
5. **Portfolio projects & testimonials** — replace the sample project names and quotes with real client work.
6. **Pricing** — the figures are starting-point placeholders; update to your actual packages.

## Deploy to GitHub Pages

1. Create a new GitHub repository and push these three files (`index.html`, `styles.css`, `script.js`) to the root of the `main` branch.
2. In the repository, go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to `Deploy from a branch`, branch `main`, folder `/ (root)`.
4. Save — GitHub will publish the site at `https://<your-username>.github.io/<repo-name>/` within a minute or two.
5. Optional: add a `CNAME` file with your custom domain if you're using one.

No build tools or npm install required — it's ready to deploy as-is.
