# Whatever Ventures website

**Canonical commercial site:** https://whateverventures.onrender.com/

**GitHub Pages fallback URL (source prepared; Pages activation pending):** https://whateverventures.github.io/whatever-ventures-website/

**Source repository:** https://github.com/whateverventures/whatever-ventures-website

A dependency-free HTML site maintained in this GitHub repository, with a separate research and open-project continuity page in `docs/index.html`.

## Architecture and intended roles

- `index.html`: corporate homepage published through the Render static service named `whateverventures`. GitHub is the source of truth for the HTML.
- `docs/index.html`: non-commercial project portfolio and continuity page prepared for GitHub Pages. Points visitors to the canonical commercial site, public repository, Whatever Signal, and email contact.
- Whatever Signal: https://whateversignal.substack.com/ is the editorial publication home.
- Email: whateverventures@gmail.com. Website contact uses a visitor-initiated `mailto:` link, not a server-side form.
- Social accounts: footer icons point to previously identified social accounts. TikTok is visible but inactive pending exact profile verification.
- Product Viability Kill Test: separate free interactive tool; no ungated paid fulfillment promoted.
- SALT: not offered or advertised as production SaaS.

## GitHub Pages activation required

The GitHub Pages source files are committed on `main` under `/docs`. The current GitHub connector can edit repository contents, but cannot change GitHub Pages publishing settings. Do not call the fallback URL live until Pages is configured and its public HTTP response verified.

Open the GitHub repository **Settings > Pages**:
1. Under **Build and deployment**, select **Deploy from a branch**.
2. Select branch `main` and folder `/docs`, then save.
3. Verify `https://whateverventures.github.io/whatever-ventures-website/` shows our non-commercial portfolio and expected links.

GitHub Pages is intended for public projects and archives, not our primary ecommerce/paid fulfillment website. Enabling Pages starts the initial Pages publication. Do not enable unrelated GitHub Actions workflows or any recurring agent jobs.

## Render operation

- Primary Render service: https://dashboard.render.com/static/srv-dbubp11srm7s73ecsjjg
- Automatic deployments are off. Source commits do not automatically publish to Render.
- A manual deployment and public QA is required to publish changes to the primary site.
- Historical dashed Render URL: https://whatever-ventures.onrender.com/. Preserve until dependencies and redirects are reviewed.

## Content and identity safeguards

The corporate homepage avoids unverified legal entity, client history and production-readiness claims. Original brand palette from Whatever Ventures Brand Style Guide v21: `#1C1C1C`, `#A67C52`, `#5A5A5A`, `#D9D6D2`, `#F3F0EC`, and `#EEE9E4`.

No external tracking scripts, customer payment forms, cookies, new scheduled automations, paid hosting plan, or autonomous background tasks were created through this repository update.

## Local preview

From the repository root:

```sh
python3 -m http.server 8000
```

Open `http://localhost:8000/` for the main site and `http://localhost:8000/docs/` for the fallback.

**Account governance:** Preserve the November 7 global automation shutdown. No spending, domain registration, DNS changes or new paid subscriptions without explicit approval.
