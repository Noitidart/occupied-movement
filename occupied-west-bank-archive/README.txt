WIRED West Bank Interactive — offline archive
Archived: 2026-10-01
Source article: https://www.wired.com/story/experience-what-its-like-to-travel-in-the-occupied-west-bank/
"Experience What It's Like to Travel in the Occupied West Bank" — WIRED, published 2026-10-01. Illustration: Lina Jaradat.

Contents:
- index.html          Offline rebuild of the interactive simulation. Works from any static
                      server (e.g. `python3 -m http.server` in this folder). Original boot
                      markup extracted from the article's interactiveOverride; asset URLs
                      rewritten from the Cloudflare R2 bucket to ./assets/.
- assets/             76 files pulled from pub-ce74e6c9659b4aa18a44457c124e8a9b.r2.dev
                      /interactive/assets/ — Vite JS+CSS build, 68 scene webp images
                      (11 artworks x responsive variants), 6 fonts. The entire simulation
                      (all scenes, choices, text) is baked into index-CJlroFO-.js; it makes
                      no network requests at runtime.
- article-snapshot/   Full original wired.com HTML (includes __PRELOADED_STATE__ with all
                      article metadata) and the hero illustration at w_2560.

Ads/analytics/site chrome intentionally excluded.
