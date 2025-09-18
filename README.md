# Rebuilt Static Site

This folder contains a cleaned, portable version of the provided site archive.

## What I did
- Extracted original ZIP into `extracted_site/` (for reference; not included here).
- Selected entry HTML: `index.html` -> written to root as `index.html`.
- Copied all assets preserving folder structure.
- Rewrote HTML asset paths to be relative where possible.
- Left external resources (http/https) untouched.

## Notes
- Index rewrites: 3 changes
- Other HTML rewrites: 0 changes
- Potential issues: 0

If something looks off (e.g., missing fonts or scripts loaded from CDN), those are likely external resources not bundled in the ZIP.
