# Agent instructions

## Development

This is a small Astro marketing site. Keep the implementation lightweight and mobile-first. Prefer Astro, standard browser APIs, and CSS before adding a framework or dependency.

When starting the development server, use background mode:

```sh
astro dev --background
```

Manage it with `astro dev status`, `astro dev logs`, and `astro dev stop`.

## Product context

Easy FreeDge is a smart shopping and household inventory assistant. It helps people know what they have at home, what is running low, and what to buy next. The product may use barcode scanning, product and receipt photography, and AI-assisted recognition to make product entry quick.

The website should communicate practical outcomes—less household busywork, fewer forgotten purchases, and less waste—rather than leading with technical terms such as AI, OCR, or predictive inventory management.

## Content and implementation principles

- Keep the site mostly static and avoid unnecessary dependencies.
- Use semantic, accessible HTML with keyboard navigation, visible focus states, good contrast, and meaningful alternative text.
- Keep copy concrete and honest; do not invent testimonials, user numbers, ratings, or release dates.
- Preserve a clear path toward a beta/waitlist CTA without creating empty pages or speculative features.
- Add SEO metadata and privacy considerations as public features are introduced.

Consult the [Astro documentation](https://docs.astro.build/) when working on Astro-specific behavior.
