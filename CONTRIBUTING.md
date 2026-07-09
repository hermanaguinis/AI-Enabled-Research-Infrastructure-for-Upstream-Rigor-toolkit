# Contributing

This toolkit operationalizes published, peer-reviewed methodological guidance. Contributions are welcome, but changes to a tool's underlying recommendations must be evidence-first.

## Rules for contributions

1. **Evidence-first changes.** Any change to a tool's methodological logic, decision tree, or recommendation must cite a specific peer-reviewed source (article, chapter, or book). Cosmetic, accessibility, and bug fixes do not require a citation.
2. **No server-side data collection.** Every tool must remain fully client-side: no external network calls, no analytics beacons inside a tool, no account requirement, no server-side storage of user inputs. Pull requests that introduce any of these will not be merged.
3. **Self-contained tools.** Each `tools/*/index.html` must remain a single file with inline CSS/JS and no external library or CDN dependency, so it stays auditable and works offline.
4. **Pull-request checklist.**
   - [ ] Cites a specific source for any methodological change
   - [ ] Does not introduce network calls, accounts, or server-side storage
   - [ ] Updates the affected tool's `README.md` and `CHANGELOG.md`
   - [ ] Updates `docs/crosswalk.md` and `docs/manifest.json` if the tool's source or description changed

## How to propose a methodological correction

Open an issue using the **Methodological correction** template (`.github/ISSUE_TEMPLATE/methodological_correction.md`). Quote and cite the source supporting your correction rather than asserting an opinion. See `docs/governance.md` for how disputes that a pull request cannot resolve are adjudicated.

## Code of conduct

All contributions and discussion are governed by `CODE_OF_CONDUCT.md`.
