# ANCOVA with Fallible Covariates: EIV Correction Tool

**Topic:** Moderation and Mediation
**Original source page:** https://www.hermanaguinis.com/ANCOVA.html
**Primary cited source:** Fuller (1987), Measurement Error Models (Wiley)

## Description

Implements Fuller's errors-in-variables (EIV) correction end to end: a bias/Type-I-error risk calculator, a live Type-I-error-inflation explorer across covariate reliabilities, a full EIV engine (raw CSV or covariance-matrix input) that disattenuates coefficients and computes Fuller (1987) standard errors, a comparison table of EIV against Lord's method, SEM, and naive OLS ANCOVA, and copyable R/Stata code. Self-tests against the source's worked example on load.

## Files

- `index.html` -- the tool itself. Self-contained HTML/JS, no external calls, no build step. Open directly in a browser.

## Data handling

Runs entirely client-side. See `/docs/data-handling-statement.md` at the repository root for the persistence model (localStorage vs. session-only) that applies to this tool.

## Citing this tool

Cite the parent repository via `CITATION.cff`, this folder path, and the version noted in `CHANGELOG.md` below, alongside the primary cited source above.
