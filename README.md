# Spellbun-Docs

Public legal pages for **Spellbun**, a cute word-lane game for Android.

This repository is meant to be public and served with **GitHub Pages** so Google Play and in-app Settings can link to a stable HTTPS URL.

## Pages

| Document | Path on this site |
| --- | --- |
| Home | [/](https://kingspi-gh.github.io/Spellbun-Docs/) |
| [Privacy Policy](privacy/) | `https://kingspi-gh.github.io/Spellbun-Docs/privacy/` |
| [Terms & Conditions](terms/) | `https://kingspi-gh.github.io/Spellbun-Docs/terms/` |
| [Delete account](delete/) | `https://kingspi-gh.github.io/Spellbun-Docs/delete/` |

The privacy policy covers anonymous and linked Google accounts, cloud save, Arcade records, Play Billing, GameAnalytics, Sentry, **AdMob interstitials + UMP consent**, retention, and in-app **Delete account & data**. The terms cover eligibility (13+), the license to play, ads, virtual items (Remove ads, BunBun coins), leaderboards, acceptable use, and Google Play notes.

Update the **Last updated** date on both legal pages when the Game’s data practices change. Keep Play Data safety in lockstep with the policy.

## Enable GitHub Pages

1. Make this repository public.
2. On GitHub: **Settings → Pages**.
3. Source: **Deploy from a branch**.
4. Branch: `main`, folder: `/ (root)`.
5. Wait for the site to publish, then open the Privacy URL above in a private window to confirm it loads over HTTPS.

Paste the Privacy URL into Play Console (app content / Data safety). Use the same URL from Spellbun Settings (`OS.shell_open`). Use the Terms URL if a store field or Settings row asks for terms of use. For the Data safety **account deletion** URL, use the Delete account page (it must work without reinstalling the game).

## Maintained here

- `index.html` — landing page
- `privacy/index.html` — privacy policy
- `terms/index.html` — terms & conditions
- `delete/index.html` — account / data deletion (in-app + web request)
- `styles.css` — shared layout

Current Game facts to keep in the legal pages: Android / Google Play at launch, English UI, AdMob interstitial after completed stages (not losses, not Opening Day w1s1), no banners/rewarded ads, UMP not tagged for under-age, Remove ads skips the SDK. Add iOS / App Store language when that build ships.

## Contact

Issues for these documents: [KingSPi-GH/Spellbun-Docs](https://github.com/KingSPi-GH/Spellbun-Docs/issues).

Account deletion: in the Game (Settings → Delete account & data), or a web request via the Delete account page if the game is uninstalled.
