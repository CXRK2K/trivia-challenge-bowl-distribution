# LOCKOUT! Public Static Files

This `docs/` folder is served by GitHub Pages. Everything here is public.

| Path | What it is | When to touch it |
|---|---|---|
| `index.html` | Public web app entry point | Replaced by public web builds from `lockout-core`. |
| `404.html` | SPA fallback for GitHub Pages refresh/deep links | Preserve during every sync. |
| `assets/` | Built JS/CSS/font assets | Replaced by public web builds. |
| `data/` | Public bootstrap JSON | Replace only with public-safe export output. |
| `mobile-client/` | Phone buzzer client for same-Wi-Fi rooms | Preserve during every sync unless intentionally updating the mobile client. |
| `lockout-icon.svg` | Public LOCKOUT! icon | Replace only with public-safe brand assets. |

Forbidden here: owner tools, private databases, unpublished content, private env files, credentials, internal release material, and audit logs.

