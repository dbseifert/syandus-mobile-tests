# syandus-mobile-tests

Prototype HTML pages for the syandus.com redesign, hosted on GitHub Pages for mobile and desktop testing.

## Viewing pages in a browser

Live site: **https://dbseifert.github.io/syandus-mobile-tests/**

The root URL shows an index of all available pages. Tap or click any page to open it.

Individual pages:

- Home: https://dbseifert.github.io/syandus-mobile-tests/home.html
- Platform: https://dbseifert.github.io/syandus-mobile-tests/platform.html
- Learning & Development: https://dbseifert.github.io/syandus-mobile-tests/ld.html
- Sales Training: https://dbseifert.github.io/syandus-mobile-tests/sales.html

## How deploys work

1. Edit or upload a file in this repo through the GitHub web interface
2. Commit to `main` (use "Commit directly to the main branch" option)
3. GitHub Pages rebuilds automatically — typically within 60 seconds
4. Refresh the live URL to see changes (hard refresh on mobile: pull down to reload)

## Notes

- These are working prototypes with external image references (HubSpot CDN URLs). They are not production-ready.
- Production handoff to Claude Code happens in a separate repo after image library migration.
- Canonical CSS is inlined in each HTML file — the standalone `syandus-canonical-v1_3.css` file is maintained separately for reference, not pulled at runtime.
