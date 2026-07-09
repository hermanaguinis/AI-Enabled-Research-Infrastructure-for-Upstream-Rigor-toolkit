# Ethical Research Design and Implementation Tool

**Topic:** Research Ethics
**Original source page:** https://www.hermanaguinis.com/ethics.html
**Primary cited source:** Aguinis (2025), Research Methodology

## Description

A ten-module workspace covering project profiling, utilitarian/deontological ethics comparison, due diligence, recruitment safeguards (including a coercion-risk meter), participant rights and consent-form building, field-setting conflicts of interest, online/MTurk-specific safeguards, a misconduct taxonomy (trimming, cooking, forging, plagiarism, censoring), a deception decision tree built around the bogus-pipeline case, and a final action plan that exports IRB-ready text. All CSS/JS inline, no external libraries or CDNs, progress stored only in browser localStorage.

## Files

- `index.html` -- the tool itself. Self-contained HTML/JS, no external calls, no build step. Open directly in a browser.

## Data handling

Runs entirely client-side. See `/docs/data-handling-statement.md` at the repository root for the persistence model (localStorage vs. session-only) that applies to this tool.

## Citing this tool

Cite the parent repository via `CITATION.cff`, this folder path, and the version noted in `CHANGELOG.md` below, alongside the primary cited source above.
