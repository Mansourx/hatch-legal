# Hatch — legal pages

The hosted Privacy Policy and Terms for the **Hatch** app, filed with Google
Play and the App Store as URLs a reviewer opens by hand.

| | English | العربية |
|---|---|---|
| Privacy Policy | [privacy.html](https://mansourx.github.io/hatch-legal/privacy.html) | [privacy.ar.html](https://mansourx.github.io/hatch-legal/privacy.ar.html) |
| Terms of Use | [terms.html](https://mansourx.github.io/hatch-legal/terms.html) | [terms.ar.html](https://mansourx.github.io/hatch-legal/terms.ar.html) |

Every page here is generated — do not edit the HTML in this repo. The source of
truth is `src/data/legal/*.json` in the app repo, which also feeds the in-app
Legal screen, so the hosted page and the one inside the app can never drift.
Regenerate and republish from there with `npm run build:legal && npm run publish:legal`.
