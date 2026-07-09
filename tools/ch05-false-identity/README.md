# False Identity Screening Tool

**Topic:** Survey Research Data Quality
**Original source page:** https://www.hermanaguinis.com/falseidentities.html
**Primary cited source:** Aguinis (2025), Research Methodology

## Description

Operationalizes the decision tree for detecting non-targeted (false-identity) survey respondents using duplicate-IP checks, ISP type, an IP threat score, and five supporting calculators (instructed-response scoring, two within-person reliability methods, open-ended completion, time-to-complete, location cross-check). No cookies, no local storage; all data stays in browser memory only and clears on tab close.

## Files

- `index.html` -- the tool itself. Self-contained HTML/JS, no external calls, no build step. Open directly in a browser.

## Data handling

Runs entirely client-side. See `/docs/data-handling-statement.md` at the repository root for the persistence model (localStorage vs. session-only) that applies to this tool.

## Citing this tool

Cite the parent repository via `CITATION.cff`, this folder path, and the version noted in `CHANGELOG.md` below, alongside the primary cited source above.
