# ReadThisLater (marketing site)

Static marketing page for the Clipfile app — `index.html`, `faq.html`, icons. No build
step, no framework. Repo: `github.com/shearmds/ReadThisLater`.

**This is the website, not the app.** The app family it advertises:

| Repo | What it is |
|---|---|
| `ReadLater` | the iOS app (App Store) |
| `readlater-sync` | the Cloudflare Worker |
| `dia-read-later` | the browser extension |
| `read-this-later` | the Raycast extension |
| `readlater-privacy` | the privacy policy page |
| **this repo** | the marketing site |

The near-identical name against `read-this-later` (the Raycast extension) is the trap — confirm
which one you're in before editing.

## Publishing

Cloned by `mikeshear-site` at build time into `/coding/research-sync`. **Pushing here does not
update mikeshear.com** — that needs a `mikeshear-site` rebuild, which is what this repo's empty
"Trigger mikeshear.com rebuild on push" commit is for.

`readlater-privacy` is cloned in beneath it at `/coding/research-sync/privacy`, so the privacy
link here resolves only in the composed site, not when opening `index.html` locally.
