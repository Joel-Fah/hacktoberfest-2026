# hacktoberfest-2026

Here we centralise every initiative taken by OSSCameroon during Hacktoberfest 2026.

**Hacktoberfest Cameroon 2026** runs from 3 to 31 October 2026: four weekly sprints kicked off every Saturday, organised by OSSCameroon with Atori Space and partner hubs, and closed by a finale on 31 October.

- Website: https://osscameroon.github.io/hacktoberfest-2026/
- Telegram: https://t.me/+UpKZh_KXTaTx7JD7

## What's in this repo

| Path | Content |
| --- | --- |
| [`site/`](site/) | The event website (static HTML/CSS, no build step) |
| [`docs/programme.md`](docs/programme.md) | The full programme: tracks, weekly schedule, hubs and finale |
| [`docs/contribute-track.md`](docs/contribute-track.md) | Shortlist of African open-source projects for the Contribute Track (draft, pending maintainer confirmation) |

## Preview the site locally

```sh
python3 -m http.server 8000 -d site
```

Then open http://localhost:8000.

## Deployment

Every push to `main` that touches `site/` deploys the website to GitHub Pages via [`.github/workflows/pages.yml`](.github/workflows/pages.yml). The workflow can also be run manually from the Actions tab.
