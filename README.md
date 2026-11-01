# AzSprue support site

The home page (`index.html`, Tailwind from its CDN, styled like the app), privacy policy and terms, for GitHub Pages. `screenshots/` holds the App Store screenshots at half size. `privacy.md` and `terms.md` are copies of the text under the line in `docs/PRIVACY_POLICY.md` and `docs/TERMS_OF_USE.md`. A unit test fails if they differ, so edit them in `docs/` and copy them here.

To publish: put these files in the root of a public repo (mine is `azsprue-site`) and turn on Settings → Pages → Deploy from branch `main`, folder `/`. The pages show up at `https://<user>.github.io/azsprue-site/`, `.../privacy/` and `.../terms/`.
