# Outlier Detection & Management Tool

**Topic:** Outlier Management
**Original source page:** https://www.hermanaguinis.com/Outliers.html
**Primary cited source:** Aguinis (2025), Research Methodology

## Description

A five-part decision guide distinguishing error, interesting, and influential outliers; a 39-technique identification reference filterable by analytic context (regression, SEM, MLM, meta-analysis, time series) and outlier type; a live cutoff calculator (leverage, Mahalanobis distance, Cook's D, DFFITS, DFBETAS, Bonferroni-corrected thresholds) driven by user-entered n and k; and a methods-paragraph generator.

## Files

- `index.html` -- the tool itself. Self-contained HTML/JS, no external calls, no build step. Open directly in a browser.

## Data handling

Runs entirely client-side. See `/docs/data-handling-statement.md` at the repository root for the persistence model (localStorage vs. session-only) that applies to this tool.

## Citing this tool

Cite the parent repository via `CITATION.cff`, this folder path, and the version noted in `CHANGELOG.md` below, alongside the primary cited source above.
