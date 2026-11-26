# platinumapps-web

The website for Platinum Apps LLC, to be served at https://platinumappsllc.com. Plain HTML and one
stylesheet: no build step, no scripts, nothing to install. Open `index.html` to look at it.

- `index.html`: the company's home page, one card for each app.
- `cribbage/`: Cribbage Platinum's page, its privacy policy and its support page.
- `app-ads.txt`: the ad sellers authorised for the apps. It must be served at the root of the
  domain that the App Store listing names as the developer's website. It started as a copy of
  mflplatinum.com's, which covers the same AppLovin account.
- `styles.css`, `assets/`.

Not yet published. Before it is:

- `cribbage/privacy.html` is a draft. It describes the app with ads and with the consent prompt
  for Europe turned on, so it must go live together with a build that has both. Check each ad
  partner's privacy link in a browser.
- "Cribbage Platinum" is a working name and the App Store link is missing.
