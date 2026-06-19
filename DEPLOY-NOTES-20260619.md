# NaghVPN site fix 2026-06-19

Changes:
- Replaced API base to `https://api.naghvpn.ru:2083` where needed.
- Changed partner admin API from `:4430` to `:2083`.
- Removed external Google Fonts links from HTML pages to avoid hangs without VPN.

After upload to GitHub Pages, purge Cloudflare cache: Caching → Purge Everything.
