# Easy FreeDge

Easy FreeDge is a mobile-first smart shopping and household inventory assistant. It helps households keep track of what they have, what is running low, and what they may need to buy next.

The product is designed to reduce household busywork through lightweight inventory tracking, shared shopping lists, purchase-history insights, and fast product capture. Planned input methods include manual entry, barcode scanning, product and receipt photography, and AI-assisted recognition.

> Spend less time managing the application than the application saves you managing your household.

## This repository

This repository contains the public-facing marketing website, not the mobile application or backend. It is intentionally small while the product is being developed.

The website currently presents the product idea, its main benefits, and progress notes. Future additions may include a beta waitlist, product previews, FAQ, privacy information, and app-store links.

## Tech stack

- [Astro](https://astro.build/) for a lightweight static site
- TypeScript configuration supplied by Astro
- Responsive CSS with minimal client-side JavaScript

## Local development

Requires Node.js 22.12 or newer.

```sh
npm install
npm run dev
```

The development site is available at `http://localhost:4321`.

## Commands

| Command | Description |
| --- | --- |
| `npm run dev` | Start the local development server |
| `npm run build` | Build the production site into `dist/` |
| `npm run preview` | Preview the production build locally |
| `npm run astro -- --help` | Show Astro CLI help |

## Project structure

```text
public/                Static assets
src/pages/index.astro  Landing page
astro.config.mjs       Astro configuration
```

## Status

Under active development. No public release date is currently committed.
