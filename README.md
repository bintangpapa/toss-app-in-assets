# toss-app-in-assets

Public static assets for the toss-app-in mini-apps (앱인토스 / Granite RN), served via jsDelivr CDN.

The app code repo is private; this repo holds only runtime image assets (game art) so they can be
hosted on a free, permanent CDN instead of temporary fal.media URLs.

Served as: `https://cdn.jsdelivr.net/gh/bintangpapa/toss-app-in-assets@<tag>/idle-tycoon/<file>.png`

Pin a version tag (e.g. `@v1`) for permanent cache. Regenerate/update via the app repo's
`scripts/migrate-cdn-jsdelivr.py`.
