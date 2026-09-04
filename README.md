# ugs

Hosted HTML game shells for the Galactic Games site.

Each file under `UGS-Files/` is a single-file game shell (from the Ultimate Game Stash / bubbls/ugs-singlefile collection). The games load their heavy assets from their own absolute CDN URLs, so serving these shells from any origin works.

The site loads them via direct iframe from:
`https://thisissonobodyplaysgame.github.io/ugs/UGS-Files/<file>.html`

Set GitHub Pages source to the `main` branch root. No build step needed.
