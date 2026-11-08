# wvrstudios.com

The WVR Studios site, served by GitHub Pages from `main`. Plain HTML and one stylesheet; no build step.

- `/` studio home
- `/nonagon/` Nonagon's page (App Store marketing URL)
- `/nonagon/privacy/` Nonagon's privacy policy (App Store Connect and the in-app paywall link)
- `/wanderfell/` Wanderfell's page (App Store marketing URL)
- `/wanderfell/privacy/` Wanderfell's privacy policy (App Store Connect privacy URL)
- `/wanderfell/press/` Wanderfell's press kit
- `/support/` support and contact for both apps (App Store support URL)

Colours come from Nonagon's Frost theme. Preview locally with `python3 -m http.server` and open http://localhost:8000.

Wanderfell's images in `assets/wanderfell-*.png` are crops of the app's contact sheets (`SNAPSHOT_DIR=… swift test --filter renderContactSheets` in its AscentKit package) and its icons are exported from `App/Icons` with Icon Composer's `ictool`.

If Nonagon or Wanderfell starts collecting any data, update its privacy policy and its date before shipping that build, along with the App Privacy answers in App Store Connect.
