# Yara Field Kit

Unofficial Far Cry 6 companion: a single-page logbook for weapons, gear, missions and camp builds, with a Gemini-powered advisor.

- The whole app is `index.html`. No build step.
- Progress and the Gemini API key are stored in the browser only. Never put a key in this repo.

## Deploy on Cloudflare

1. In the Cloudflare dashboard, go to Workers & Pages and create a new Worker by importing this GitHub repo.
2. Name it `fieldkit` (it has to match `name` in `wrangler.jsonc`). Leave the build command empty and keep the default deploy command (`npx wrangler deploy`).
3. Open the `workers.dev` address on your phone, add your Gemini key under Settings, then Share, Add to Home Screen.

Fan-made. Not affiliated with or endorsed by Ubisoft.
