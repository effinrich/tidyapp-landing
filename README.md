# Tidy Landing

Marketing landing page for [Tidy](https://tidyapp.me) — an ADHD-friendly cleaning app built by [ForgeKit](https://forgekit.cloud).

## Tech stack

- [Astro](https://astro.build) v5
- [Tailwind CSS](https://tailwindcss.com) v3
- Deployed to [tidyapp.me](https://tidyapp.me)

## Project structure

```
public/
  videos/          # Explainer videos served as static assets
  favicon.png
  logo-*.svg/png
  wordmark.svg
src/
  components/
    Nav.astro
    Hero.astro
    AppExplainer.astro     # "Meet Tidy" video section
    Features.astro
    DesignPhilosophy.astro # "Designing Against Paralysis" video section
    Pricing.astro
    Footer.astro
  layouts/
    Layout.astro
  pages/
    index.astro
    privacy.astro
    terms.astro
```

## Getting started

```bash
npm install
npm run dev
```

## Commands

| Command         | Action                                   |
| --------------- | ---------------------------------------- |
| `npm run dev`   | Start local dev server at localhost:4321 |
| `npm run build` | Build production site to `./dist/`       |
| `npm run preview` | Preview the production build locally   |

## Legal

- Privacy Policy: [tidyapp.me/privacy](https://tidyapp.me/privacy)
- Terms of Service: [tidyapp.me/terms](https://tidyapp.me/terms)
- Contact: legal@tidyapp.me
