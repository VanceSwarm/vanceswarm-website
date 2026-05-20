# VanceSwarm — Coming-Soon Site

Static one-page site for `vanceswarm.com`. Repository: [VanceSwarm/vanceswarm-website](https://github.com/VanceSwarm/vanceswarm-website).

## Files

| File | Purpose |
|---|---|
| `index.html` | The page. Self-contained — inline CSS + SVG glyph; no JS, no tracking, no external deps |
| `CNAME` | GitHub Pages custom-domain pointer → `vanceswarm.com` |
| `.nojekyll` | Tells GitHub Pages not to run Jekyll (serve files as-is) |

## Deploy steps (one-time)

1. Push these files to `main` (handled by source-control)
2. Repo Settings → Pages → Source: `main` branch, `/` root → Save
3. DNS at registrar (use the registrar where `vanceswarm.com` was purchased):
   - `A` records for apex (`@`) pointing to GitHub Pages IPs:
     - `185.199.108.153`
     - `185.199.109.153`
     - `185.199.110.153`
     - `185.199.111.153`
   - `CNAME` record for `www` pointing to `vanceswarm.github.io`
4. Wait ~15–60 min for DNS propagation; GH Pages auto-issues SSL via Let's Encrypt
5. Repo Settings → Pages → "Enforce HTTPS" once cert is provisioned
6. Update Vanced Corporation's website field in Atlas dashboard to `https://vanceswarm.com`

## Brand stack served by this site

- URL/host: vanceswarm.com (publisher pseudonym layer)
- Site display: VanceSwarm (h1; the collective publisher identity)
- Footer: Operated by Vanced Corporation (legal entity, retained for KYC + transparency)
- Interior name (TheSwarm) does not appear anywhere on this surface

## Maintenance

This is a coming-soon placeholder. When the real site replaces it, retire or repurpose. No analytics; no tracking — intentional, consistent with anonymity-discipline.
