# Bayesian Analysis Companion

**Topic:** Market Basket Analysis, Experience Sampling, and Bayesian Analysis
**Original source page:** https://www.hermanaguinis.com/Bayesian.html
**Primary cited source:** Aguinis (2025), Research Methodology

## Description

A working Metropolis MCMC sampler running a full Bayesian multiple linear regression in the browser (multiple chains, burn-in, trace/autocorrelation/R-hat diagnostics), prior specification and justification, HDI/ROPE-based decision rules, a Bayesian power-and-replication simulator that resamples from the fitted posterior, and a five-recommendation manuscript write-up generator.

## Files

- `index.html` -- the tool itself. Self-contained HTML/JS, no external calls, no build step. Open directly in a browser.

## Data handling

Runs entirely client-side. See `/docs/data-handling-statement.md` at the repository root for the persistence model (localStorage vs. session-only) that applies to this tool.

## Citing this tool

Cite the parent repository via `CITATION.cff`, this folder path, and the version noted in `CHANGELOG.md` below, alongside the primary cited source above.
