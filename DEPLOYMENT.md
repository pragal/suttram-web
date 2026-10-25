# Suttram Brand Website — Netlify package

Suttram / சுற்றம் — a Pragalya initiative.

## Contents

- `/` — public Suttram homepage, ready for the future web app to replace. **No automatic redirect.**
- `/about` — full Suttram brand/marketing experience with English / தமிழ் language switching and real mobile previews.
- `/privacy` — public Privacy Policy.
- `/terms` — public Terms of Service.
- `/assets` — approved Suttram brand art and original device previews.
- `robots.txt`, `sitemap.xml`, `_headers` — basic public-site metadata and safe response headers.

This is a **ready-to-publish static site**. No package installation, build command, Node.js backend or environment variables are required.

## Deploy to your existing Netlify site

1. Open the existing Suttram project in Netlify and go to **Deploys**.
2. Use the manual deploy option to upload this ZIP, or extract it and drop the folder **containing this `index.html`**.
3. Verify the resulting Netlify preview URLs for `/`, `/about`, `/privacy`, and `/terms`.
4. When ready, attach `suttram.pragalya.com` as a custom domain in Netlify. Add the specific DNS record Netlify requests in Namecheap.
5. After HTTPS is active, check the same four routes on the custom domain. Only then use them in Google's OAuth Branding fields.

## Google OAuth Branding URLs

- Application homepage: `https://suttram.pragalya.com/`
- Privacy Policy: `https://suttram.pragalya.com/privacy`
- Terms of Service: `https://suttram.pragalya.com/terms`
- Authorized domain: `pragalya.com` (subject to verification and Google's current instructions)

No root-to-`/about` redirect is included. The root describes the product, and links directly to both legal pages.

## Approved brand assets

Use the original supplied brand art without editing it:

- `assets/suttram-icon.png` — approved Suttram app icon PNG
- `assets/suttram-wordmark.png` — approved Suttram crimson wordmark PNG
- `assets/suttram-wordmark.svg` — supplied wordmark SVG
- `favicon.ico` — multi-size browser favicon (16, 32 and 48 px)
- `assets/favicon-16x16.png` and `assets/favicon-32x32.png` — browser favicon PNGs
- `assets/apple-touch-icon.png` — 180 px icon on the Suttram cream background for iPhone bookmarks
- `assets/android-chrome-192x192.png` and `assets/android-chrome-512x512.png` — Android shortcut icons
- `site.webmanifest` — icon metadata for the public website (browser display mode; not a released web app)
- `brand/suttram-brand-colors-v1.0.md` — source of approved colours

Brand palette: **மஞ்சள்** `#F2AE0A`, **மகிழ்ச்சி** `#F26515`, **உயிர்** `#B6072C`, **அன்பு** `#CF3F5D`, **வளர்ச்சி** `#50AF67`, **மழலை** `#2D7ECA`.

## Final review before public release

- Confirm that `hello@pragalya.com` receives customer/privacy enquiries.
- Confirm the Privacy Policy matches the final app's implemented authentication, storage, sharing, security and deletion behaviour. It currently distinguishes **implemented sign-in** from **planned family features**.
- Review the privacy/terms text with an appropriate legal adviser when feasible; it is project-specific draft wording, not a certification of legal compliance.
- Update “Last updated” on the legal pages whenever their wording materially changes.
- Replace “Coming Soon” and preview messaging after the actual mobile app release, and add verified App Store / Play Store links.
- For the future full web app, replace the root application while retaining `/about`, `/privacy` and `/terms`.
