# Mediation Study Design and Reporting Tool

**Topic:** Moderation and Mediation
**Original source page:** https://www.hermanaguinis.com/mediation.html
**Primary cited source:** Aguinis (2025), Research Methodology

## Description

Twelve modules, including a mechanism-quality scorer, a model-specification wizard (no default direct path), a design-quality rating tied to causal-language guardrails, a measurement-risk planner, an indirect-effect calculator (manual coefficients or an offline single-mediator OLS-plus-bootstrap engine on pasted CSV data), overclaiming warnings, and a reviewer/editor checklist.

## Files

- `index.html` -- the tool itself. Self-contained HTML/JS, no external calls, no build step. Open directly in a browser.

## Data handling

Runs entirely client-side. See `/docs/data-handling-statement.md` at the repository root for the persistence model (localStorage vs. session-only) that applies to this tool.

## Citing this tool

Cite the parent repository via `CITATION.cff`, this folder path, and the version noted in `CHANGELOG.md` below, alongside the primary cited source above.
