# vins.clinic

Tiny static gift site for GitHub Pages.

Files:
- `index.html` — the website
- `CNAME` — tells GitHub Pages to use `vins.clinic`

Deploy:
1. Push this repo to GitHub.
2. In GitHub repo settings, enable Pages from the `main` branch / root.
3. In Spaceship, add the DNS records listed below.

DNS records for apex domain:
- A `@` -> `185.199.108.153`
- A `@` -> `185.199.109.153`
- A `@` -> `185.199.110.153`
- A `@` -> `185.199.111.153`
- CNAME `www` -> `zain.github.io`

GitHub Pages will redirect `www.vins.clinic` to `vins.clinic` once the custom domain is set.
