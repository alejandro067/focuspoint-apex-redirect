# focuspoint-apex-redirect

Apex 301-style redirect: `thefocuspoint.org` → `https://www.thefocuspoint.org` via GitHub Pages.
Hard-path apex workaround for the Wix-registered domain (CF Pages can't serve an apex over external DNS).

**Public** because GitHub Pages free tier requires it. No secrets here.

DNS at the registrar:
- apex `A` → `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
- `www` CNAME → `focuspoint.pages.dev` (the real site, on Cloudflare Pages)
