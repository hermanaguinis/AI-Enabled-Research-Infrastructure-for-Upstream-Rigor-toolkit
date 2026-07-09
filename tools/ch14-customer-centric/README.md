# Customer-Centric Science Tool

**Topic:** Reporting Results
**Original source page:** https://www.hermanaguinis.com/customercentric.html
**Primary cited source:** Murphy & Myors (1998), Statistical Power Analysis (Lawrence Erlbaum)

## Description

Operationalizes a three-step sequence: an alpha-justification calculator based on the relative seriousness of Type I versus Type II error, an effect-magnitude calculator (Cohen's d/Hedges' g, R-squared/adjusted R-squared with confidence intervals) that argues against fixed small/medium/large cutoffs, and a qualitative, practical-significance study planner.

## Files

- `index.html` -- the tool itself. Self-contained HTML/JS, no external calls, no build step. Open directly in a browser.

## Data handling

Runs entirely client-side. See `/docs/data-handling-statement.md` at the repository root for the persistence model (localStorage vs. session-only) that applies to this tool.

## Citing this tool

Cite the parent repository via `CITATION.cff`, this folder path, and the version noted in `CHANGELOG.md` below, alongside the primary cited source above.
