# Reproducibility Guide

## Clone the repository

```
git clone https://github.com/hermanaguinis/AI-Enabled-Research-Infrastructure-for-Upstream-Rigor-toolkit.git cd AI-Enabled-Research-Infrastructure-for-Upstream-Rigor-toolkit
```

## Open a tool locally

Each tool is a single, dependency-free HTML file. Open it directly:

```
open tools/ch02-ethics/index.html      # macOS
start tools/ch02-ethics/index.html     # Windows
```

Or double-click the file in a file browser. No build step, server, or internet connection is required.

## Inspect a tool's logic

Every tool inlines its own CSS and JavaScript, so "View Source" (or opening the `.html` file in a text editor) shows the complete implementation -- there is no minified bundle or external script to chase down.

## Cite a specific tool version

1. Note the tool's folder (e.g., `tools/ch09-mediation`).
2. Note the version in that folder's `CHANGELOG.md`, or the commit hash / release tag if citing an exact snapshot.
3. Cite the repository as a whole via `CITATION.cff`, plus the primary cited source listed for that tool in `docs/crosswalk.md`.
