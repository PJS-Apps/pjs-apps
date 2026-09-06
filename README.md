# PJS Apps site

Static pages for **https://pjs-apps.com**, published with GitHub Pages. No extra host.

Live as soon as Pages is on: [https://skordaschristofanis.github.io/pjs-apps/](https://skordaschristofanis.github.io/pjs-apps/)

After DNS: [https://pjs-apps.com](https://pjs-apps.com)

Ecliptic (App Store URLs):

| Page | URL |
| --- | --- |
| Home | https://pjs-apps.com/ecliptic/ |
| Privacy | https://pjs-apps.com/ecliptic/privacy/ |
| Terms | https://pjs-apps.com/ecliptic/terms/ |
| Support | https://pjs-apps.com/ecliptic/support/ |

GitHub Pages allows one custom domain per site, so the studio and Ecliptic share this repo. `ecliptic.pjs-apps.com` would need a second Pages repo; until then these paths are the public URLs.

## DNS (optional, for pjs-apps.com)

In the domain registrar:

1. **Apex** `pjs-apps.com` — A records to GitHub Pages:
   - `185.199.108.153`
   - `185.199.109.153`
   - `185.199.110.153`
   - `185.199.111.153`
2. **www** — CNAME to `skordaschristofanis.github.io`

This repo already has a `CNAME` file for `pjs-apps.com`. GitHub will request HTTPS once the records exist.

## Local

Open `index.html` in a browser, or:

```bash
python3 -m http.server 8080
```
