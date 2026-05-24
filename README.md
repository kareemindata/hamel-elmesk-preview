# Hamel El-Mesk Elite — Storefront Preview

Static HTML preview of the Hamel El-Mesk Elite perfume storefront, generated
from the private development repo for client review.

This site contains only the public-facing card design and product photos
(no source code, no admin tools, no customer data).

**Live:** https://kareemindata.github.io/hamel-elmesk-preview/

## Regenerating

The HTML in this repo is built by `scripts/build_static_preview.py` in the
private dev repo. Each refresh:

1. Run the build script in the private repo.
2. Copy `docs/storefront-preview/*` over the root of this repo.
3. Commit & push — GitHub Pages updates automatically.
