# Metaregression Boundary-Condition Reporting Tool

**Topic:** Meta-Analysis and MASEM
**Original source page:** https://www.hermanaguinis.com/metaregression.html
**Primary cited source:** Gonzalez-Mule & Aguinis (2018), Journal of Management 44(6):2246-2273

## Description

An eight-stage pipeline implementing real statistics: forest plots, a Monte Carlo and approximate power check, a heterogeneity dashboard (Q, tau-squared, I-squared), a model-choice wizard defaulting to mixed effects with Knapp-Hartung inference and REML, moderator bubble plots, and an R-squared-Meta calculation, with two built-in worked datasets.

## Files

- `index.html` -- the tool itself. Self-contained HTML/JS, no external calls, no build step. Open directly in a browser.

## Data handling

Runs entirely client-side. See `/docs/data-handling-statement.md` at the repository root for the persistence model (localStorage vs. session-only) that applies to this tool.

## Citing this tool

Cite the parent repository via `CITATION.cff`, this folder path, and the version noted in `CHANGELOG.md` below, alongside the primary cited source above.
