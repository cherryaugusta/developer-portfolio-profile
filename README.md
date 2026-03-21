# Cherry Augusta Portfolio

GitHub Pages portfolio for a London-based Junior Software Engineer focused on backend APIs, full-stack web applications, Angular and React frontend delivery, TypeScript-based integration, Python web engineering, SQL-backed development, Docker-based reproducibility, and OpenAPI-first engineering practices.

## Live Site

- **Portfolio:** https://cherryaugusta.github.io/developer-portfolio-profile/
- **Repository:** https://github.com/cherryaugusta/developer-portfolio-profile

## Professional Focus

This portfolio presents software engineering work centred on:

- Django and Django REST Framework API development
- Angular and React frontend integration with TypeScript
- Python web engineering and SQL-backed application development
- OpenAPI-first and contract-aware development
- Docker-based local reproducibility
- Testing, CI/CD, and structured delivery workflows
- Real-time and scheduled application behaviour with Redis, Channels, and Celery
- Governance-aware and secure-by-default implementation patterns

## Featured Projects

### [LawPulse](https://github.com/cherryaugusta/lawpulse.git)
AI-powered legal document auditor built with Django, Django REST Framework, Django Channels, React, TypeScript, Redis, PostgreSQL, and Docker Compose.

**Highlights**
- PDF upload and page-level text extraction
- Risky clause extraction and review workflow
- WebSocket progress updates
- OpenAPI documentation
- Request latency middleware
- Full Dockerised stack

### [GreenOps](https://github.com/cherryaugusta/greenops-carbon-accounting-platform.git)
Full-stack ESG reporting platform built with Django, Django REST Framework, React, TypeScript, PostgreSQL, Redis, JWT authentication, and Docker Compose.

**Highlights**
- Authenticated employee and manager workflows
- Audit trail and admin oversight
- Dashboard analytics and KPI summaries
- Multi-step validated form
- Drag-and-drop report builder

### [TradeFlow](https://github.com/cherryaugusta/TradeFlow.git)
Multi-source arbitrage tracker built with Django, Django REST Framework, React, TypeScript, Celery, Redis, PostgreSQL, and Docker Compose.

**Highlights**
- Scheduled ingestion with Celery Beat
- Historical price snapshot storage
- Arbitrage and analytics endpoints
- Sortable frontend dashboard
- Request latency logging
- Full reproducible local setup

### [EcoRoute LEZ Optimiser](https://github.com/cherryaugusta/EcoRoute-LEZ-Optimiser.git)
Portfolio-grade Django and Angular project focused on typed contracts, OpenAPI-first development, reproducibility, tracing, and governance-aware engineering.

**Highlights**
- Deterministic route audit responses
- Correlation ID propagation
- Typed Angular integration
- Dependency auditing and structural verification
- ADRs and governance artefacts

### [OpsSentinel](https://github.com/cherryaugusta/OpsSentinel.git)
Real-time anomaly and incident console built with Django, Django REST Framework, Channels, Celery, Angular, PostgreSQL, Redis, and Docker Compose.

**Highlights**
- Synthetic event ingestion and anomaly detection
- Explainability workflows
- WebSocket event streaming
- Periodic evaluation jobs
- Security-aware defaults and Docker-first verification

### [PolicyPulse](https://github.com/cherryaugusta/policypulse.git)
Full-stack decisioning application built with Django REST Framework, Angular, and TypeScript.

**Highlights**
- REST API endpoints with OpenAPI documentation
- Typed frontend-backend contracts
- Health checks and correlation ID tracing
- Governance scaffolding and structured repository design

## Supporting Projects

- **FinCrime GraphOps** — https://github.com/cherryaugusta/fincrime-graphops.git
- **LondonPlan RAG** — https://github.com/cherryaugusta/londonplan-rag-architecture.git
- **Scroll CTA Highlight Portfolio** — https://github.com/cherryaugusta/scroll-cta-highlight-portfolio
- **Weather Analytics System** — https://github.com/cherryaugusta/weather-analytics
- **Advanced Python Calculator** — https://github.com/cherryaugusta/advanced-python-calculator
- **GloBox A/B Testing Analysis** — https://github.com/cherryaugusta/GloBox_A-B_Testing_Analysis
- **Credit Card Customer Segmentation** — https://github.com/cherryaugusta/Credit-Card-Customer-Segmentation

## Site Structure

```text
/
  index.html
  about.html
  projects.html
  cv.html
  contact.html
  styles.css
  script.js
  README.md
  assets/
    profile-photo.jpg
    profile-photo.webp
    og-preview.jpg
  screenshots/
    lawpulse/
      frontend-selected-clause.png
      frontend-completed-view.png
      frontend-processing.png
      frontend-empty-state.png
      backend-swagger-ui.png
      backend-admin.png
      backend-response-headers.png
    greenops/
      frontend-dashboard.png
      frontend-report-builder.png
      frontend-multistep-form.png
      backend-swagger-ui.png
      backend-admin-carbon-logs.png
      backend-admin-history.png
    tradeflow/
      frontend-dashboard.png
      frontend-flash-effect.png
      backend-swagger.png
      backend-admin-periodic-task.png
      docker-healthy-services.png
    ecoroute/
      angular-home-health-compute.png
      api-docs-swagger.png
      api-health-json.png
      docker-compose-running.png
      verify-tree-passing.png
      pre-commit-passing.png
    opssentinel/
      frontend-dashboard.png
      api-docs-browser.png
      api-health-browser.png
    policypulse/
      frontend-home.png
      api-redoc-browser.png
      api-health-browser.png
    fincrime-graphops/
      frontend-home.png
      api-docs-browser.png
      api-health-browser.png
    londonplan-rag/
      angular-health-page.png
      swagger-ui.png
``` 
## Primary screenshots used on the website 
* LawPulse → `screenshots/lawpulse/frontend-selected-clause.png` 
* GreenOps → `screenshots/greenops/frontend-dashboard.png` 
* TradeFlow → `screenshots/tradeflow/frontend-dashboard.png` 
* EcoRoute LEZ Optimiser → `screenshots/ecoroute/angular-home-health-compute.png` 
* OpsSentinel → `screenshots/opssentinel/frontend-dashboard.png` 
* PolicyPulse → `screenshots/policypulse/frontend-home.png` 
* FinCrime GraphOps → `screenshots/fincrime-graphops/frontend-home.png` 
* LondonPlan RAG → `screenshots/londonplan-rag/angular-health-page.png` 
## Alt text used for the primary screenshots 
* LawPulse: `LawPulse contract review interface with selected clause details visible` 
* GreenOps: `GreenOps dashboard showing ESG reporting charts and KPI summaries` 
* TradeFlow: `TradeFlow dashboard showing arbitrage opportunities and market data table` 
* EcoRoute: `EcoRoute LEZ Optimiser interface showing route input, health information, and computed output` 
* OpsSentinel: `OpsSentinel dashboard showing anomaly and incident monitoring` 
* PolicyPulse: `PolicyPulse Angular frontend for decision submission and review` 
* FinCrime GraphOps: `FinCrime GraphOps frontend showing sanctions and ownership risk exploration` 
* LondonPlan RAG: `LondonPlan RAG Angular application interface` 
## Technical Approach 
The site uses: 
* Semantic HTML 
* Shared CSS for consistent layout and styling 
* Small vanilla JavaScript for responsive navigation 
* Static hosting compatible with GitHub Pages 
* No build tooling 
## Design Direction 
This version keeps the site GitHub Pages-friendly while improving: 
* responsiveness across desktop, tablet, and mobile 
* stronger visual hierarchy 
* smoother spacing and card rhythm 
* more premium hero and CTA presentation 
* improved navigation behaviour on smaller screens 
* more polished shadows, gradients, and glass effects 
* stronger project-card presentation without changing the actual project content 
## Preparing Images 
### Profile image 
Add both: 
* `assets/profile-photo.jpg` 
* `assets/profile-photo.webp` 
Recommended: 
* square crop 
* 1200 × 1200 px 
* shoulders-up portrait 
* neutral background 
* professional presentation 
* optimised file size 
### Open Graph image 
Add: 
* `assets/og-preview.jpg` 
Recommended: 
* 1200 × 630 px 
* your name 
* your role 
* 3–4 core technologies 
* optionally one clean project screenshot strip 
### Project screenshots 
Use the real project subfolders and real filenames already captured, not flat placeholder names. 
Primary website screenshots: 
* `screenshots/lawpulse/frontend-selected-clause.png` 
* `screenshots/greenops/frontend-dashboard.png` 
* `screenshots/tradeflow/frontend-dashboard.png` 
* `screenshots/ecoroute/angular-home-health-compute.png` 
* `screenshots/opssentinel/frontend-dashboard.png` 
* `screenshots/policypulse/frontend-home.png` 
* `screenshots/fincrime-graphops/frontend-home.png` 
* `screenshots/londonplan-rag/angular-health-page.png` 
Recommended: 
* landscape format 
* 1600 px to 2000 px wide 
* consistent browser style 
* clean crop 
* no sensitive or cluttered content 
* application UI clearly visible 
## Education and Training 
* **Software Development Programme** — Primed Talent (Jan 2026 – Mar 2026) 
* Developed backend applications using Python and Django 
* Built frontend interfaces with TypeScript and Angular 
* Worked with SQL using SQLite and MongoDB 
* Applied Agile development practices and SDLC principles 
* **Data Analytics Programme** — Masterschool 
* **PhD in Religion, International Relations, and Politics** — King’s College London 
## Selected Certificates 
* **Angular** — Sololearn 
[https://www.sololearn.com/certificates/CC-CRVQI5FX](https://www.sololearn.com/certificates/CC-CRVQI5FX) 
* **Python Developer** — Sololearn 
[https://www.sololearn.com/certificates/CC-DHUE0BPR](https://www.sololearn.com/certificates/CC-DHUE0BPR) 
* **Web Development** — Sololearn 
[https://www.sololearn.com/certificates/CC-GY8ERAPW](https://www.sololearn.com/certificates/CC-GY8ERAPW) 
* **Python Intermediate** — Sololearn 
[https://www.sololearn.com/certificates/CC-DKZ7GS1T](https://www.sololearn.com/certificates/CC-DKZ7GS1T) 
* **JavaScript Intermediate** — Sololearn 
[https://www.sololearn.com/certificates/CC-TSMPZBXQ](https://www.sololearn.com/certificates/CC-TSMPZBXQ) 
* **SQL Intermediate** — Sololearn 
[https://www.sololearn.com/certificates/CC-RJRRIZD5](https://www.sololearn.com/certificates/CC-RJRRIZD5) 
* **Combining Tables in SQL** — DataQuest 
[https://app.dataquest.io/verify_cert/ZJ7F5Q6ELBGZK46ZWRD5/](https://app.dataquest.io/verify_cert/ZJ7F5Q6ELBGZK46ZWRD5/) 
* **Summarizing Data in SQL** — DataQuest 
[https://app.dataquest.io/verify_cert/3A36ZVM678G3BQ0YBLRA/](https://app.dataquest.io/verify_cert/3A36ZVM678G3BQ0YBLRA/) 
* **Intermediate Python for Data Science** — DataQuest 
[https://app.dataquest.io/verify_cert/C5CL33XE4P3WWTFYR3BS/](https://app.dataquest.io/verify_cert/C5CL33XE4P3WWTFYR3BS/) 
* **Hypothesis Testing in Python** — DataQuest 
[https://app.dataquest.io/verify_cert/6OF6NHN1GMT5WH2I9T71/](https://app.dataquest.io/verify_cert/6OF6NHN1GMT5WH2I9T71/) 
* **Introduction to Supervised Machine Learning in Python** — DataQuest 
[https://app.dataquest.io/verify_cert/E0R9MOGDEUAWTI1ENU40/](https://app.dataquest.io/verify_cert/E0R9MOGDEUAWTI1ENU40/) 
* **Introduction to Unsupervised Machine Learning in Python** — DataQuest 
[https://app.dataquest.io/verify_cert/CI5ERO9BV41DOV62I8J1/](https://app.dataquest.io/verify_cert/CI5ERO9BV41DOV62I8J1/) 
## Contact 
* **Email:** [cherryaugusta@gmail.com](mailto:cherryaugusta@gmail.com) 
* **LinkedIn:** [https://www.linkedin.com/in/cherry-augusta-3957a916](https://www.linkedin.com/in/cherry-augusta-3957a916) 
* **GitHub:** [https://github.com/cherryaugusta](https://github.com/cherryaugusta) 
 
---
