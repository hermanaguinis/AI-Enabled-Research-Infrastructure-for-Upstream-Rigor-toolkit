# Control Variable Decision Tool

**Topic:** Causal Inference and Control Variables
**Original source page:** https://www.hermanaguinis.com/controlvariables.html
**Primary cited source:** Bernerth JB, Aguinis H (2016) A critical review and best-practice recommendations for control variable usage. Personnel Psychology 69(1):229–283. 

## Description

Operationalizes the control variable decision tree: a per-variable wizard ending in Include/Exclude/Stop plus reasoning chain, an auto-generated methods paragraph, and an explicit rebuttal of the purification principle, the residual-predictor problem, and the "conservative test" fallacy. All data stays in the browser; nothing is uploaded or transmitted.

## Files

- `index.html` -- the tool itself. Self-contained HTML/JS, no external calls, no build step. Open directly in a browser.

## Data handling

Runs entirely client-side. See `/docs/data-handling-statement.md` at the repository root for the persistence model (localStorage vs. session-only) that applies to this tool.

## Citing this tool

Cite the parent repository via `CITATION.cff`, this folder path, and the version noted in `CHANGELOG.md` below, alongside the primary cited source above.
