# 11 things

Support and privacy pages for the 11 family of apps (GitHub Pages, no build step).

- `/` the family
- `/11looks/` 11 Looks support
- `/11looks/privacy/` 11 Looks privacy policy
- `/11objects/` 11 Objects support
- `/11objects/privacy/` 11 Objects privacy policy
- `/11plates/` 11 Plates support
- `/11plates/privacy/` 11 Plates privacy policy
- `/11plates/terms/` 11 Plates terms of use

11 Plates pages are generated from the app's `src/data/legal.ts`: in eleven-plates run
`node --experimental-strip-types scripts/site-pages.mjs ../11things`.
