# sands-search

Live prototypes for the **Search & Navigation** area of *entwickler intelligence* (entwickler.de / SandS Media).

Root is the prototype. Everything under `flows/` is an annotated user-flow prototype.

| Path | What it is | Link |
|---|---|---|
| `/` | **Search v8** — the new search surface inside the navigation shell. The bridge between Home (browse) and Intelligence (work): find a POC, preview it, open it in the controller. | [open](https://tcappelletti-stack.github.io/sands-search/) |
| `/flows/PROD-1556/` | **New Search v8 — flows (find + ask).** Annotated state-and-transition frames: typing a query, previewing a POC, starting an AI conversation from a result. Each arrow is labelled with its trigger. | [open](https://tcappelletti-stack.github.io/sands-search/flows/PROD-1556/) |

Ticket: [PROD-1556](https://sandsmedia.myjetbrains.com/youtrack/issue/PROD-1556)

All prototypes are self-contained single-file HTML — no build, no install, no login.

**All prototypes:** [sands-prototypes](https://tcappelletti-stack.github.io/sands-prototypes/)

## Notes

- A **POC** = a Piece of Content (article, talk recording, magazine issue, tutorial).
- Prototypes are design artefacts, not production code — they mock data and interactions to make the intended behaviour unambiguous. Where a flow and the current build disagree, the flow is the request.

## Updating

Replace the relevant `index.html` and commit. GitHub Pages redeploys automatically.
