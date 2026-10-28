# Anivora public avatar art

Public Anivora avatar portraits only. This repository contains no app source and no app binary.

Catalog: https://raw.githubusercontent.com/brandon-300/Anivora-Assets/main/avatars/manifest.json

Add a compressed 128–256px WebP/JPEG portrait under `avatars/`, then add its `id`, `name`, `group` and HTTPS `url` to `avatars/manifest.json`. IDs must stay stable forever: never reuse or rename an existing ID. Increase `version` for each catalog revision and update `updatedAt` (ISO-8601 UTC). Keep old image URLs available for cached catalogs. Publish to `main`; clients refresh within 12 hours or immediately with Retry. No new APK is required.

Use the raw.githubusercontent.com/brandon-300/Anivora-Assets/main/avatars/ URL prefix. The application accepts only that configured host/path and raster image extensions. Other CDN hosts require an app allowlist update before use. Portraits are rendered with native image caching; a failed image shows a bundled default.

The support/legal website lives on Cloudflare Pages. Android binaries and their update feed live in Anivora-Releases. Render hosts neither these image bytes nor APK downloads. Publication here does not grant rights to third-party characters or artwork.
