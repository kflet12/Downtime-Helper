# DT Code Finder

Web app for picking the right downtime code. Choose Producer or Injector, answer the questions, or search by keyword. Works offline once opened and can be saved to an iPhone home screen.

## Host on GitHub Pages
Repo Settings > Pages > Deploy from a branch > `main` / `(root)`. The site will be at `https://<user>.github.io/<repo>/`.

## Add to iPhone home screen
Open the URL in Safari > Share > Add to Home Screen.

## Edit
Everything is in `index.html`:
- `C`: code list. `N`: question flow. `ONLY`: producer-only / injector-only codes. `ALIAS`: search shorthand.

After changing any file, bump `VERSION` in `sw.js` so installed copies pick up the update.
