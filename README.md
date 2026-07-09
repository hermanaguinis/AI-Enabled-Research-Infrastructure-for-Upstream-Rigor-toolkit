# Research Methodology Toolkit

**Better, Not More: An Open, Auditable AI-Enabled Research Infrastructure for Upstream Rigor**

Herman Aguinis · The George Washington University

34 interactive, browser-based tools that operationalize peer-reviewed, vetted best-practice recommendations for organizational and social science research design, data collection, analysis, and reporting. Each tool was authored with AI assistance (Claude Sonnet 5, built by Anthropic, and GPT-5.5 Thinking) but requires no AI access, account, or subscription to use: every tool runs as a single, self-contained HTML/JavaScript page in an ordinary web browser.

This repository is the public home of that toolkit, submitted as reusable research infrastructure to the Organization Science special issue *AI-Enabled Frontiers in Organizational Science*.

---

## Why this exists

AI is currently pushing organizational and social science toward producing *more* research, not necessarily *better* research. This toolkit moves AI's leverage point upstream — into planning, design, and measurement, before data are collected and while choices are still reversible — rather than downstream, into drafting manuscripts faster. It converts tacit methodological knowledge that usually lives in experts' heads into free, public, executable infrastructure that any researcher, anywhere, can use: doctoral students, scholars at under-resourced institutions, journal editors and reviewers, instructors, and university leaders alike.

## Design principles

1. **Client-side only.** Every tool runs entirely in the browser — no server, no account, no data leaving the machine it runs on.
2. **No AI required to use a tool.** Tools are built with AI assistance, but end users need no AI access, login, or subscription; each tool is static HTML/JavaScript.
3. **Auditable by design.** All CSS and JavaScript are inlined in each tool. Any reviewer can read the full logic directly rather than trust a black box.
4. **Traceable to peer-reviewed sources.** Every tool operationalizes the specific recommendations of one or more cited, peer-reviewed articles, books, or book chapters, with a one-to-one crosswalk maintained in [`docs/crosswalk.md`](docs/crosswalk.md).
5. **Advisory, not gating.** Tools surface recommendations, warnings, and exportable manuscript language. No tool blocks a user or claims to be the final word on a methodological choice — methodological disagreement can be raised through [Issues](.github/ISSUE_TEMPLATE/methodological_correction.md) and [pull requests](CONTRIBUTING.md).
6. **Free and open.** No login, license fee, or paywall. Code is MIT-licensed; explanatory text, checklists, and documentation are CC BY-NC 4.0-licensed (see [Licensing](#licensing) below).

## Repository map

```
research-methodology-toolkit/
├── README.md
├── LICENSE
├── CONTENT_LICENSE.md
├── CITATION.cff
├── CHANGELOG.md
├── CONTRIBUTING.md
├── CODE_OF_CONDUCT.md
├── .github/
│   └── ISSUE_TEMPLATE/
│       ├── bug_report.md
│       ├── methodological_correction.md
│       └── feature_request.md
├── docs/
│   ├── manifest.json              # machine-readable catalog of all 34 tools
│   ├── crosswalk.md               # tool → folder → cited source, human-readable
│   ├── data-handling-statement.md # privacy-by-design model
│   ├── reproducibility-guide.md   # clone, run, inspect, and cite a tool
│   └── governance.md              # how methodological disputes are resolved
└── tools/
    └── ch##-topic/
        ├── index.html             # the tool itself (self-contained, inline CSS/JS)
        ├── README.md              # that tool's cited source(s), inputs, and outputs
        └── CHANGELOG.md           # that tool's own version history
```

Folder names under `tools/` mirror the chapter structure of *Research Methodology: Best Practices for Rigorous, Credible, and Impactful Research* (Aguinis, 2025), so a folder name maps directly to a book chapter and topic.

## The 34 tools

| Folder | Tool | Topic |
|---|---|---|
| `ch02-ethics` | Ethical Research Design and Implementation Tool | Research Ethics |
| `ch03-theory-contribution` | Theory Contribution Builder | Theory Development |
| `ch03-theory-elaboration` | TheoryForge: Interactive Theory Elaboration Navigator | Theory Development |
| `ch04-causal-inference` | Causal Inference Research Planning Tool | Causal Inference and Control Variables |
| `ch04-control-variables` | Control Variable Decision Tool | Causal Inference and Control Variables |
| `ch05-false-identity` | False Identity Screening Tool | Survey Research Data Quality |
| `ch05-response-rate` | Response-Rate Validity Assessment Tool | Survey Research Data Quality |
| `ch07-vignettes` | EVM Study Designer | Vignettes, Online Samples, and Thought Experiments |
| `ch07-mturk` | MTurkGuard | Vignettes, Online Samples, and Thought Experiments |
| `ch07-thought-experiments` | Thought Experiment Designer | Vignettes, Online Samples, and Thought Experiments |
| `ch08-outliers` | Outlier Detection & Management Tool | Outlier Management |
| `ch09-moderation` | Moderation Study Design and Audit Tool | Moderation and Mediation |
| `ch09-interactions` | Interaction Effect Reporting Tool | Moderation and Mediation |
| `ch09-mediation` | Mediation Study Design and Reporting Tool | Moderation and Mediation |
| `ch09-ancova-eiv` | ANCOVA with Fallible Covariates: EIV Correction Tool | Moderation and Mediation |
| `ch10-cross-level-interactions` | Cross-Level Interaction Workbench | Multilevel Modeling and Cross-Level Interactions |
| `ch10-cross-level-power` | Cross-Level Interaction Power Workbench | Multilevel Modeling and Cross-Level Interactions |
| `ch11-meta-analysis` | Meta-Analysis Anatomy Toolkit | Meta-Analysis and MASEM |
| `ch11-meta-regression` | Metaregression Boundary-Condition Reporting Tool | Meta-Analysis and MASEM |
| `ch11-masem` | Meta-Analytic Structural Equation Modeling (MASEM) Study Builder | Meta-Analysis and MASEM |
| `ch12-market-basket-analysis` | Market Basket Analysis (MBA) Implementation Tool | Market Basket Analysis, Experience Sampling, and Bayesian Analysis |
| `ch12-esm` | Experience Sampling Methodology (ESM) Study Designer | Market Basket Analysis, Experience Sampling, and Bayesian Analysis |
| `ch12-bayesian` | Bayesian Analysis Companion | Market Basket Analysis, Experience Sampling, and Bayesian Analysis |
| `ch13-key-informant-interviews` | Key Informant Interview Research Tool | Qualitative and Mixed-Methods Research |
| `ch13-cata` | CATA Accuracy Toolkit | Qualitative and Mixed-Methods Research |
| `ch13-method-lit-review` | Methodological Literature Review Builder, Evaluator, and Teaching Toolkit | Qualitative and Mixed-Methods Research |
| `ch13-qual-transparency` | Transparency and Replicability Tool for Qualitative Research | Qualitative and Mixed-Methods Research |
| `ch13-mixed-methods` | Mixed Methods Study Designer | Qualitative and Mixed-Methods Research |
| `ch14-customer-centric` | Customer-Centric Science Tool | Reporting Results |
| `ch14-effect-sizes` | Effect-Size Benchmark Interpreter | Reporting Results |
| `ch14-limitations` | Limitations & Future Directions Builder | Reporting Results |
| `ch15-transparency` | Methodological Transparency Companion | Research Transparency |
| `ch16-impact` | Scholarly Impact Toolkit | Scholarly Impact |
| `ch16-pidp` | Personal Impact Development Plan (PIDP) Builder | Scholarly Impact |

The full catalog, including each tool's cited source(s) and module-level description, is maintained in [`docs/crosswalk.md`](docs/crosswalk.md) and [`docs/manifest.json`](docs/manifest.json). A browsable index of all 34 tools is also available at [hermanaguinis.com/research-methodology-book.html](https://www.hermanaguinis.com/research-methodology-book.html).

## Using a tool

Every tool is a single, self-contained HTML file with no build step and no external dependencies:

1. Open `tools/<folder>/index.html` directly in a browser (double-click it, or clone the repository and open the file locally), **or**
2. Use the hosted version linked from [hermanaguinis.com/research-methodology-book.html](https://www.hermanaguinis.com/research-methodology-book.html).

Nothing is installed, no account is created, and no data leaves your browser. Most tools save progress to browser `localStorage` so a session survives a page reload; a smaller number are explicitly session-only. See [`docs/data-handling-statement.md`](docs/data-handling-statement.md) for the handling model of each tool, and [`docs/reproducibility-guide.md`](docs/reproducibility-guide.md) for how to clone, run, and inspect a tool's underlying logic.

## Citing this repository or an individual tool

To cite the repository as a whole, use [`CITATION.cff`](CITATION.cff) (GitHub and tools such as Zenodo can auto-generate a formatted citation from this file). To cite a specific tool, cite its individual folder and version as documented in that tool's own `README.md` and `CHANGELOG.md`, alongside the peer-reviewed source(s) it operationalizes (listed in `docs/crosswalk.md`).

The toolkit as a whole is based on:

> Aguinis, H. (2025). *Research Methodology: Best Practices for Rigorous, Credible, and Impactful Research.* SAGE, Thousand Oaks, CA.

## Contributing

Contributions are welcome, particularly methodological corrections grounded in peer-reviewed evidence. See [`CONTRIBUTING.md`](CONTRIBUTING.md) for the pull-request process and [`CODE_OF_CONDUCT.md`](CODE_OF_CONDUCT.md) for how disagreement and correction are conducted respectfully. Three issue templates are available:

- **Bug report** — coding, rendering, or export errors.
- **Methodological correction** — challenges a tool's methodological recommendation; requires a quoted, cited supporting source.
- **Feature request** — new modules or usability improvements.

Disputes that the standard pull-request process cannot resolve are handled as described in [`docs/governance.md`](docs/governance.md).

## Licensing

This project uses dual licensing:

- **Code** (all `index.html` application logic): [MIT License](LICENSE)
- **Content** (explanatory text, checklists, and documentation): [CC BY-NC 4.0](CONTENT_LICENSE.md)

## Data handling and privacy

No tool collects, transmits, or stores participant or personal data. All computation happens locally in the user's browser; no tool makes external network calls. See [`docs/data-handling-statement.md`](docs/data-handling-statement.md) for the full privacy-by-design model, including which tools use `localStorage` versus session-only memory.

## Background

This repository accompanies a proposal submitted to the *Organization Science* special issue **AI-Enabled Frontiers in Organizational Science** (Gartenberg, Hasan, Murray, and Pierce, 2026), under the submission type "Reusable research infrastructure." See the proposal for the full case for the toolkit's novelty, feasibility, auditability, ethicality, reproducibility, scalability, and potential for adoption and impact.
