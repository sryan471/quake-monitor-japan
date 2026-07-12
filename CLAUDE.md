# Quake Monitor Japan
Single-file app: everything lives in index.html (HTML+CSS+JS inline).
Live earthquake data from JMA via my Cloudflare Worker proxy:
https://jma-proxy.sryanjp.workers.dev — the PROXIES array and embedded
SNAPSHOT fallback in index.html are critical plumbing. Never remove or
rewrite them during styling or feature changes.
Bilingual EN/JP interface — all UI strings go through the I18N dictionary.
Dark theme, cyan/blue accents. Deployed on GitHub Pages from main branch.
