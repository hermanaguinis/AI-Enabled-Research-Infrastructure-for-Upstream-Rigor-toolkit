# Data Handling and Privacy Statement

Every interactive tool in this repository runs client-side with no server calls, no accounts, and no external libraries, fonts, or CDNs. All CSS and JavaScript are inline.

Persistence differs by tool and should not be assumed uniform:

- **Most tools** (for example, the Causal Inference Planning Tool, the Moderation and Mediation Tools, the PIDP Builder) save progress to browser `localStorage` so a session survives a page reload.
- **A smaller number of tools are explicitly session-only**, with no persistence at all. The False Identity Screening Tool and the Meta-Analysis Anatomy Toolkit hold data in browser memory only, cleared when the tab closes; the False Identity Tool specifically uses no cookies.
- **Several tools support explicit export** to JSON, CSV, HTML, or plain text (for example, the Response-Rate Tool, the Metaregression Tool, the Ethics Tool, and the ESM Designer) so a user can back up or transfer work between sessions.

None of the tools transmits data to any server, and none requires a login.

**Guidance for users:** Do not paste confidential, regulated, or otherwise sensitive participant data into any tool beyond what you would be comfortable storing in your own browser's local storage.

See each tool's own `README.md` for its specific persistence model.
