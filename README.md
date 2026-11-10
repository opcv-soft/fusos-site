# fusos-site

The public website for [Fusos](https://fusos.app): landing page and privacy policy, served by GitHub Pages from `main`. The app's code lives in a separate private repo; the extension itself is on the [Chrome Web Store](https://chromewebstore.google.com/detail/fusos-meet-across-time-zo/gfbiapbddkabkhcecokkjmpogpikblal).

Plain HTML and CSS, no build step and no third-party requests (the privacy policy says so; keep it true). Hanken Grotesk, the app's typeface, is self-hosted in `fonts/` under the SIL Open Font License (`fonts/OFL.txt`). Checked with the [impeccable](https://github.com/pbakaus/impeccable) detector: `npx impeccable detect --viewport 1280x800 <url>` and `--viewport 375x812` should both stay clean. Screenshots in `img/` come from the app: the planner and email ones are rendered with Playwright, the "Fill from this email" and "Insert into email" ones are crops of the app repo's `media/` captures.
