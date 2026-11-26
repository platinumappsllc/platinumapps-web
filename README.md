# platinumapps-web

The website for Platinum Apps LLC, to be served at https://platinumappsllc.com. Plain HTML and one
stylesheet: no build step, no scripts, nothing to install. Open `index.html` to look at it.

- `index.html`: the company's home page, one card for each app.
- `cribbage/`: Cribbage Platinum's page, its privacy policy and its support page.
- `app-ads.txt`: the ad sellers authorised for the apps. It must be served at the root of the
  domain that the App Store listing names as the developer's website. It started as a copy of
  mflplatinum.com's, which covers the same AppLovin account.
- `styles.css`, `assets/`.

Published by GitHub Pages from `main`: a merge there is live within a minute or two. The custom
domain is set in the repository's Pages settings.

- `cribbage/privacy.html` is the app's privacy policy, effective 2026-11-25. It has to stay true
  of the app: when the app changes what it collects, change this page first and its date with it.
- "Cribbage Platinum" is a working name and the App Store link is missing.
