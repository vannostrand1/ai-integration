# AI Integration

Public origin for Google Cloud / Google Developers Console.

Intended live host: **https://xyzwft.com** (GoDaddy-owned).

## DNS at GoDaddy (apex + www)

Point the domain at GitHub Pages:

**A records** for `@` (xyzwft.com):

- `185.199.108.153`
- `185.199.109.153`
- `185.199.110.153`
- `185.199.111.153`

**CNAME** for `www`:

- `www` → `vannostrand1.github.io`

Then in the repo: Settings → Pages → Custom domain `xyzwft.com` → Enable HTTPS.

Fallback Pages URL: `https://vannostrand1.github.io/ai-integration/`
