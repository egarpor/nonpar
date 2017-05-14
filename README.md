Website for the *"First Nonparametric UC3M Workshop"*. The website is available at <http://www.est.uc3m.es/nonpar> (alternatively: <https://egarpor.github.io/nonpar/>).

Update workflow:

1. Edit `index.md`.
2. Run `jekyll serve` in the root folder to create `/_site`. This folde contains the wesbsite and `index.html`.

When moving `/_site` to halweb (`est.uc3m.es`), remember to:

- Rename `index.html` to `principal.html` if not done (or the web will not be served).
- Change paths `"/assets/*"` to `"assets/*"` (or the style files will not be read).
- Add favicon with `<link rel="icon" type="image/png" href="images/favicon.ico">` after `<meta name="viewport" content="width=device-width">`.
