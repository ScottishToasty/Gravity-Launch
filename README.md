# Gravity Launch

The permanent development and testing home for Gravity Launch by ScottishToasty.

## Play

[Play Gravity Launch](https://scottishtoasty.github.io/Gravity-Launch/) in a browser, including Safari on iPhone. The game is served directly by GitHub Pages without a hosting advertising banner.

Current version: **v6.2.2**. The playable HTML is an unchanged copy of the v6.2.2 developer build.

## Repository layout

| Path | Purpose |
| --- | --- |
| `index.html` | Current playable game |
| `builds/v6.2.2/index.html` | Archived v6.2.2 developer build |
| `release-notes/v6.2.2.md` | Original v6.2.2 release notes |
| `README.md` | Project information and version history |

## Development and testing

For each future release, keep an immutable versioned build under `builds/`, add its release notes, then update the root `index.html` and this version history. Git history records all changes.

GitHub Pages publishes from the **main** branch and **/(root)** folder. No build tools or dependencies are required to serve this single-file game. Browser saves remain local to the browser and site origin; progress from another hosting address does not automatically transfer.

To test locally, run `python3 -m http.server 8000` from the repository root and open `http://localhost:8000/`. Check gameplay and touch controls, Settings navigation, Sandbox object placement/editing, and persistence before promoting a later build.

## Version history

| Version | Changes |
| --- | --- |
| [v6.2.2](release-notes/v6.2.2.md) | Subdued Settings Home button styling; mobile-friendly categorised Sandbox object picker. |

Hosting setup only: no changes to gameplay, physics, progression, or developer features.
