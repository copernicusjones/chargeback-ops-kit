# Landing Pages Deployment Bundle

This folder is ready for static hosting.

## Contents
- `ai-agent-services/index.html`
- `chargeback-ops-kit/index.html`
- `netlify.toml`

## Quick Deploy Options

### Netlify
1. Drag the `deploy/` folder into Netlify Drop.
2. Or connect the vault repo and set publish directory to `projects/landing-pages/deploy`.
3. Verify both pages render and the form action points to AgentMail.

### Cloudflare Pages
1. Upload the `deploy/` folder or connect a repo.
2. Set the output/public directory to `projects/landing-pages/deploy`.
3. Confirm the root URL lands on Chargeback Ops Kit and the AI page is reachable at `/ai-agent-services/`.

### GitHub Pages
1. Commit the `deploy/` folder to a repo.
2. Enable Pages for the branch.
3. Use `/chargeback-ops-kit/` and `/ai-agent-services/` as the live paths.

## Manual post-deploy checks
- Page title matches the page content.
- CTA links still point to the correct Gumroad URL.
- Lead form submits successfully to FormSubmit.co.
- Mobile layout is intact.
