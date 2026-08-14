# Interaction Effect Reporting Tool

**Topic:** Moderation and Mediation
**Original source page:** https://www.hermanaguinis.com/interactions.html
**Primary cited source:** Murphy KR, Aguinis H (2022) Reporting interaction effects: Visualization, effect size, and interpretation. J. Management 48(8):2159–2166

## Description

Runs a real OLS regression engine in the browser (on pasted raw data or entered coefficients): full (untruncated) y-axis by default with a teaching toggle reproducing the truncation-inflation effect documented in a 96-paper review; an interpretable effect size (delta R-squared, f-squared, Liu & Yuan's index); interaction-type classification read from plotted slopes; and Johnson-Neyman region-of-significance analysis. Ships a synthetic N=220 dataset.

## Files

- `index.html` -- the tool itself. Self-contained HTML/JS, no external calls, no build step. Open directly in a browser.

## Data handling

Runs entirely client-side. See `/docs/data-handling-statement.md` at the repository root for the persistence model (localStorage vs. session-only) that applies to this tool.

## Citing this tool

Cite the parent repository via `CITATION.cff`, this folder path, and the version noted in `CHANGELOG.md` below, alongside the primary cited source above.
