# CyberStrategy Workbench 🛡️

A free, browser-based toolkit for cybersecurity leaders to build strategic plans, map stakeholders, prioritize initiatives, draft policies, and generate executive briefs — all without sending a single byte to a server.

**[→ Launch the Tool](https://SiteQ8.github.io/cyberstrategy-workbench/)**

---

## Features

| Module | What it does |
|--------|-------------|
| **90-Day Plan** | Structure your first 90 days across People, Process, Technology, and Governance phases |
| **Stakeholder Matrix** | Map stakeholders by influence and interest; view as table or 2×2 power/interest matrix |
| **Security Roadmap** | Add, prioritize, and sort security initiatives by criticality; run a SWOT analysis |
| **Policy Builder** | Generate structured policy documents for 6 common policy types |
| **Executive Brief** | Auto-generate a board-ready security summary from your metrics and narrative |

---

## Included Policy Templates

- 🔍 Vulnerability Management
- ☁️ Cloud Security
- 🤖 AI Security
- 🔑 Access Control
- 🚨 Incident Response
- 🗄️ Data Classification

---

## Hosting on GitHub Pages

1. **Fork or clone** this repository
2. Go to **Settings → Pages**
3. Under *Source*, select `main` branch and `/ (root)` folder
4. Click **Save** — your tool will be live at `https://[username].github.io/[repo-name]/`

No build step. No dependencies. No backend. Just open `index.html`.

---

## Local Use

```bash
# Just open the file directly
open index.html

# Or serve locally
npx serve .
python3 -m http.server 8080
```

---

## Design Principles

- **100% client-side** — nothing leaves your browser
- **Zero dependencies** — no npm, no build tools, no frameworks
- **Single file** — the entire tool is `index.html`
- **Copy/export** — all generated content can be copied to clipboard or pasted into documents

---

## Contributing

Pull requests welcome. Areas for improvement:
- Additional policy templates
- PDF export
- Local storage persistence
- Additional security frameworks (NIST, ISO 27001 alignment)

---

## License

MIT — use freely, attribution appreciated.

