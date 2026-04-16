# Cherry Augusta | Software Engineer Portfolio

This repository contains my static GitHub Pages portfolio website.

It presents the project work most relevant to **Software Engineer**, **Backend Engineer**, **Full-Stack Engineer**, **Python Developer**, and **AI Platform Engineer** roles, with the strongest emphasis on:

- backend systems
- workflow-heavy product design
- auditability
- evaluation
- grounded retrieval
- maintainable repository structure
- reviewer-friendly technical communication

## Live links

- **Portfolio website:** [cherryaugusta.github.io/developer-portfolio-profile](https://cherryaugusta.github.io/developer-portfolio-profile)
- **GitHub profile:** [github.com/cherryaugusta](https://github.com/cherryaugusta)
- **LinkedIn:** [linkedin.com/in/cherry-augusta-3957a916](https://www.linkedin.com/in/cherry-augusta-3957a916)
- **Portfolio repository:** [github.com/cherryaugusta/developer-portfolio-profile](https://github.com/cherryaugusta/developer-portfolio-profile)

## Portfolio positioning

The strongest projects in this portfolio are workflow-heavy systems rather than generic demos. They show backend and full-stack engineering through:

- Django and Django REST Framework APIs
- React and TypeScript frontend integration
- PostgreSQL, Redis, Celery, and Channels-backed workflows
- grounded retrieval and source visibility
- approval flows and review routing
- audit trails and evaluation runs
- production-minded documentation and local reproducibility

This remains stronger than a generic AI-engineer pitch because the evidence is more concrete around workflow systems, reviewability, governance-oriented application design, and operational clarity.

## Additional information

- **Location:** London, United Kingdom
- **Right to work:** Indefinite Leave to Remain (Settlement), UK
- **Languages:** English (Fluent), Indonesian (Native), Malay (Native), Norwegian Bokmål (Basic)
- **Target roles:** Software Engineer, Backend Engineer, Full-Stack Engineer, Python Developer, AI Platform Engineer

## Project tiers

### Flagship

#### Consumer Duty Evidence Engine
Repository: [consumer-duty-evidence-engine](https://github.com/cherryaugusta/consumer-duty-evidence-engine)

AI-assisted evidence review workflow for regulated-style artefacts, built around claim extraction, evidence sufficiency assessment, contradiction detection, review routing, evaluation, and audit-ready traceability.

#### Meridian Ledger
Repository: [meridian-ledger](https://github.com/cherryaugusta/meridian-ledger)

Full-stack knowledge operations platform for owner-scoped notes, asynchronous indexing, grounded retrieval-backed answers, and persisted evaluation workflows.

#### Agentic Compliance Auditor
Repository: [agentic-compliance-auditor](https://github.com/cherryaugusta/agentic-compliance-auditor)

Rules-first policy audit system for contradiction detection, drift analysis, typed findings, citations, review tasks, audit lineage, and degraded-mode visibility.

#### AI Model Governance Workbench
Repository: [ai-model-governance-workbench](https://github.com/cherryaugusta/ai-model-governance-workbench)

Internal AI governance control plane for prompt and model versioning, release candidates, evaluation gates, approvals, incidents, rollback, and audit history.

### Featured

- [Sentra Nexus](https://github.com/cherryaugusta/sentra-nexus)
- [LawPulse](https://github.com/cherryaugusta/lawpulse)
- [GreenOps](https://github.com/cherryaugusta/greenops-carbon-accounting-platform)
- [TradeFlow](https://github.com/cherryaugusta/TradeFlow)
- [Gmail MCP Server](https://github.com/cherryaugusta/gmail-mcp-server)

### Supporting

- [Python Contacts Manager](https://github.com/cherryaugusta/python-contacts-manager)
- [Advanced Python Calculator](https://github.com/cherryaugusta/advanced-python-calculator)
- [GloBox A/B Testing Analysis](https://github.com/cherryaugusta/GloBox_A-B_Testing_Analysis)
- [Credit Card Customer Segmentation](https://github.com/cherryaugusta/Credit-Card-Customer-Segmentation)
- [Predicting Heart Disease](https://github.com/cherryaugusta/Predicting-Heart-Disease)

## Repository structure

```text
developer-portfolio-profile/
├── about.html
├── contact.html
├── cv.html
├── index.html
├── projects.html
├── script.js
├── styles.css
├── README.md
├── LICENSE
├── assets/
│   └── og-preview.jpg
└── screenshots/
    ├── consumer-duty-evidence-engine/
    ├── meridian-ledger/
    ├── agentic-compliance-auditor/
    ├── ai-model-governance-workbench/
    ├── sentra-nexus/
    ├── lawpulse/
    ├── greenops/
    └── tradeflow/
```

## Design and implementation notes

This portfolio is intentionally built as a static site for **GitHub Pages** using:

* plain HTML
* plain CSS
* plain JavaScript

Reasons for this approach:

* zero-cost default hosting
* low maintenance burden
* strong portability
* fast loading
* easy inspection during technical review
* no dependency on paid templates, hosted form providers, or external app hosting

## Screenshot organisation

Current screenshot structure used by the site:

```text
screenshots/
├── consumer-duty-evidence-engine/
│   └── case-detail-weak-support.png
├── meridian-ledger/
│   └── grounded-answer-with-sources.png
├── agentic-compliance-auditor/
│   └── finding-detail-side-by-side.png
├── ai-model-governance-workbench/
│   └── release-candidate-blocked.png
├── sentra-nexus/
│   └── command-center.png
├── lawpulse/
│   └── frontend-selected-clause.png
├── greenops/
│   └── frontend-dashboard.png
└── tradeflow/
    └── frontend-dashboard.png
```

Optional future screenshot folders can be added later for other projects if they become referenced by the site.

## Accessibility and readability

The site is structured to support:

* semantic HTML
* keyboard navigation
* visible focus states
* skip link
* readable spacing
* restrained contrast-safe UI
* meaningful image alt text

## Contact strategy

The default contact path intentionally uses:

* direct email
* LinkedIn

Hosted forms are not used by default because the goal is a genuinely zero-cost, GitHub Pages-compatible contact flow.

## Local preview

Run all commands below from the portfolio repository root.

```powershell
python -m http.server 8080
```

Open:

```text
http://localhost:8080
```

This is a long-running process.

Press `CTRL + C` when you are finished previewing the site.

## GitHub Pages deployment notes

This repository is designed for the GitHub Pages project-site model.

Current live URL:

[https://cherryaugusta.github.io/developer-portfolio-profile](https://cherryaugusta.github.io/developer-portfolio-profile)

Keep internal links and asset paths relative so the site continues to work correctly under the project-site URL structure.

## Recommended repository settings

* Add a clear repository description
* Add portfolio-related topics
* Keep screenshots organised by project
* Use concise, descriptive alt text in README images
* Add or update an `assets/og-preview.jpg` social preview image

## License

This project is licensed under the MIT License.

See the [LICENSE](./LICENSE) file for full details.