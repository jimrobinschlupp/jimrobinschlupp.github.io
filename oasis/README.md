# Oasis Adventures — page assets

Drop real imagery for the Oasis Adventures case-study page (#oasis) here, then
swap the placeholder `.oa-ph` tiles in `src/pages/OasisPage.tsx` for `<img>`
tags pointing at these files.

Suggested files (any names are fine — just match them in OasisPage.tsx):

- `logo-*.svg` / `.png` — the logo lockups (light / dark / on-colour)
- `website.png` — a screenshot of oasis-adventures.com for the browser frame
- `social/*.jpg` — square social-media posts
- `tours/*.jpg` — tour photography for the gallery
- `hero/*.jpg` — the three photos in the hero collage

Public assets are not fingerprinted by Vite — if you replace a file in place,
add a `?v=2` suffix to its URL in the code to bust the browser cache.
