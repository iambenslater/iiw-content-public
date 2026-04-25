# It's In Writing — public content mirror

Read-only public host for the daily carousel JPGs published to @itsinwriting on Instagram.
Pushed by the cron at 9am AEST from the content engine in `iambenslater/itsinwriting`.

Files are 1080x1350 baseline JPEGs (one per carousel slide), grouped by drop date.

URL pattern (jsDelivr CDN):
`https://cdn.jsdelivr.net/gh/iambenslater/iiw-content-public@main/{date}/png/carousel-{id}-{slug}-slide-{n}.jpg`

The original PNGs and the source code (renderer, generator, brand brief) live in the
private `iambenslater/itsinwriting` repo. This repo only carries the rendered output
because Meta's IG Graph API requires images to be reachable from a CDN host it trusts —
hosting them ourselves on `itsinwriting.com.au` was rejected.
