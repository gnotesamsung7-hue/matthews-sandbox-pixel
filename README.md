# Matthew's Sandbox (pixel edition)

A pixel-art ragdoll physics sandbox for phones. Everything (characters, items, stages and sounds) is drawn and made in code.

- `www/index.html` - the game inside the APK (works offline with the local `matter.min.js`)
- `docs/index.html` - the same game for GitHub Pages
- `.github/workflows/main.yml` - builds the APK on every push to `main`
- `icons/` - app icon; `debug.keystore` - keeps the signing key the same so updates install over the old app

Download the APK from **Releases > apk-latest**.
To update the game, replace `www/index.html` and `docs/index.html` (in `www/` keep `<script src="matter.min.js">`).
