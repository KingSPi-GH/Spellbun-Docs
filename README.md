# Spellbun-Docs

Public legal pages for **Spellbun**, a cute word-lane game for iOS and Android.

This repository is meant to be public and served with **GitHub Pages** so Google Play, the App Store, and in-app Settings can link to a stable HTTPS URL.

## Pages

| Document | Path on this site |
| --- | --- |
| Home | [/](https://kingspi-gh.github.io/Spellbun-Docs/) |
| [Privacy Policy](privacy/) | `https://kingspi-gh.github.io/Spellbun-Docs/privacy/` |
| [Terms & Conditions](terms/) | `https://kingspi-gh.github.io/Spellbun-Docs/terms/` |

The privacy policy covers anonymous and linked accounts, cloud save, Arcade records, Apple/Google sign-in, store purchases, GameAnalytics, Sentry, **AdMob interstitials + UMP consent**, retention, and in-app **Delete account & data**. The terms cover eligibility (13+), the license to play, ads, virtual items (Remove ads, BunBun coins), leaderboards, acceptable use, and store-specific notes.

Update the **Last updated** date on both legal pages when the Game’s data practices change. Keep Play Data safety and Apple privacy labels in lockstep with the policy.

## Enable GitHub Pages

1. Make this repository public.
2. On GitHub: **Settings → Pages**.
3. Source: **Deploy from a branch**.
4. Branch: `main`, folder: `/ (root)`.
5. Wait for the site to publish, then open the Privacy URL above in a private window to confirm it loads over HTTPS.

Paste the Privacy URL into Play Console (app content / Data safety) and App Store Connect. Use the same URL from Spellbun Settings (`OS.shell_open`). Use the Terms URL if a store field or Settings row asks for terms of use.

## Maintained here

- `index.html` — landing page
- `privacy/index.html` — privacy policy
- `terms/index.html` — terms & conditions
- `styles.css` — shared layout

Current Game facts to keep in the legal pages: English at launch, AdMob interstitial after completed stages (not losses, not Opening Day w1s1), no banners/rewarded ads, UMP not tagged for under-age, Remove ads skips the SDK.

## Contact

Issues for these documents: [KingSPi-GH/Spellbun-Docs](https://github.com/KingSPi-GH/Spellbun-Docs/issues).

Account deletion is handled in the Game (Settings → Delete account & data), not by filing an issue.
