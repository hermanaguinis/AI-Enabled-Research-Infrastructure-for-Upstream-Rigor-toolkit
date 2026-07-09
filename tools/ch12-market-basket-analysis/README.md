# Market Basket Analysis (MBA) Implementation Tool

**Topic:** Market Basket Analysis, Experience Sampling, and Bayesian Analysis
**Original source page:** https://www.hermanaguinis.com/marketbasketanalysis.html
**Primary cited source:** Aguinis (2025), Research Methodology

## Description

Six-step guided workspace from suitability screening through transaction definition, data sourcing, requirement verification, a live lift/support/confidence calculator (single-rule, histogram cutoff, and batch modes on pasted transaction matrices), and interpretation guidance, plus a documented list of three classic MBA pitfalls.

## Files

- `index.html` -- the tool itself. Self-contained HTML/JS, no external calls, no build step. Open directly in a browser.

## Data handling

Runs entirely client-side. See `/docs/data-handling-statement.md` at the repository root for the persistence model (localStorage vs. session-only) that applies to this tool.

## Citing this tool

Cite the parent repository via `CITATION.cff`, this folder path, and the version noted in `CHANGELOG.md` below, alongside the primary cited source above.
