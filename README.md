# fusos-site

The public website for [Fusos](https://fusos.app): landing page and privacy policy, served by GitHub Pages. The app's code lives in a separate private repo.

Plain HTML and CSS, no build step and no third-party requests (the privacy policy says so; keep it true). Hanken Grotesk, the app's typeface, is self-hosted in `fonts/` under the SIL Open Font License (`fonts/OFL.txt`). Checked with the [impeccable](https://github.com/pbakaus/impeccable) detector: `npx impeccable detect --viewport 390x844 <url>` should stay clean. Screenshots in `img/` are taken from the app with Playwright.
