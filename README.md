# AI Integration

Cloudflare Pages settings that work for this repo:

- Production branch: `main`
- Framework preset: None
- Build command: `exit 0`
- Build output directory: `public`
- Root directory: `/` (empty)

Do not choose Workers. Choose **Pages** → Connect to Git → `vannostrand1/ai-integration`.

After a green deploy, use the `*.pages.dev` URL in Google Cloud as the authorized origin.
The repo `CNAME` file points at `xyzwft.com`. Only attach that domain in Cloudflare after DNS is pointed at Pages.
