# estelair.com

The website for **estelair** — a radio alarm clock and sleep-sound app for Android.

Two static pages, served by GitHub Pages:

| Page | What it is |
|---|---|
| `index.html` | The landing page |
| `privacy.html` | The privacy policy — the URL Google Play checks on every app update, so it must stay reachable at a stable address |

## How it's built

Plain HTML with one inline stylesheet. **No external requests at all** — no web fonts, no
CDN, no analytics, no trackers. estelair's whole pitch is that it doesn't watch you, so its
website doesn't either. That also means there is nothing to break, no build step, and no
cookie banner to show.

The images in `assets/` are generated from the app's own artwork by a script that lives in
the app repository, so the site and the app can't drift apart. They are not hand-made here —
edit them there and copy the output over.

Total weight is about 420 KB for the entire site.

## Editing

Change the HTML, commit, push. GitHub Pages redeploys on push to `main`; there is no
pipeline and nothing to wait for beyond the build.

⚠️ **Every feature claim on this page is a testable assertion about the app.** The copy is
taken from the reviewed store listing rather than written fresh. If a feature changes in the
app, change it here in the same breath — a marketing page is the easiest place in a project
to end up lying by accident.

## Licence

The text, images and design are © estelair. The night scenes and app screenshots are not
free to reuse.
