# Motore Digitale — Agent Instructions

## Mission

This repository is used by Motore Digitale to build premium websites
for small and medium-sized businesses.

The objective is to produce websites that are:

- visually distinctive
- fast
- mobile-first
- conversion oriented
- SEO friendly
- easy to maintain
- accessible
- production ready

Never generate a generic-looking AI website.

## Sources of truth

Before implementing significant work, read:

- docs/CLIENT-BRIEF.md
- docs/DESIGN-SYSTEM.md
- docs/CONTENT.md
- docs/SEO.md
- docs/QA.md

Client-specific instructions override generic design preferences.

## Development principles

Prefer:

- Astro
- TypeScript
- semantic HTML
- lightweight CSS
- reusable components
- minimal JavaScript

Do not add frameworks or dependencies without a clear reason.

Use React only when genuinely necessary.

Use GSAP only for animations that cannot reasonably be implemented
with CSS or native browser APIs.

## Design principles

Avoid:

- generic SaaS layouts
- excessive gradients
- unnecessary glassmorphism
- excessive rounded cards
- repetitive grids
- meaningless animations
- stock-looking layouts

Prefer:

- strong visual hierarchy
- typography-led design
- large imagery
- deliberate whitespace
- custom composition
- subtle interaction
- clear CTA hierarchy

Every website should feel specifically designed for that client.

## Responsive

Build mobile-first.

Always check:

- 375px
- 768px
- 1024px
- 1440px

No horizontal overflow is allowed.

## Performance

Optimize:

- images
- fonts
- JavaScript
- layout shifts
- loading behaviour

Avoid unnecessary JavaScript.

## SEO

Every public page should have:

- title
- meta description
- canonical URL
- Open Graph metadata

When appropriate implement:

- sitemap
- robots.txt
- structured data

## Conversion

Every website must make the main business action obvious.

Examples:

- request quote
- call
- WhatsApp
- booking
- purchase
- contact form

## Quality assurance

Before considering a task complete:

1. run the project
2. check for console errors
3. verify responsive layouts
4. verify links
5. verify navigation
6. verify forms
7. verify metadata
8. check image loading
9. check accessibility basics
10. run the build

Run:

npm run build

Fix errors before completion.