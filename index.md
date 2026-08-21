---
layout: default
title: "Data Scientist for Internal Audit & Risk"
description: "Data scientist delivering insights and efficiencies for internal audit, risk, and compliance teams — real, deployed projects."
---

<a id="what-i-do"></a>

## What I Do

9 years delivering insights and efficiencies across internal audit, risk, and compliance — I turn manual, sample-based audit work into automated, full-population testing, and write the AI governance frameworks that make GenAI safe to use in high-stakes risk workflows. CIA-certified, MS in Business Analytics: the rare combination of real risk/audit domain depth and the engineering to build the automation, not just spec it.

Outside of work I ship real, working risk-analytics projects in public — no mockups, honest write-ups of what broke. Most multi-agent systems don't reach production and most RAG projects fail on corpus quality, not model choice; the two flagship projects in Featured Work below are proof I build that way — real orchestration, real evals, and the retrieval layer treated as infrastructure (schema-validated, linted, CI-checked).

<a id="featured-work"></a>

## Featured Work

### [Risk & Audit Analytics Portfolio](https://github.com/neifertg/risk-analytics-portfolio)

Eight real, working risk-analytics projects, each with real data, real metrics, and honest write-ups of what broke. The two flagship pieces below are the deepest AI-engineering proof; six more real audit-analytics tools follow.

<div class="card-flagship" markdown="1">
<span class="flagship-badge">Flagship</span>

![A question goes to a Sonnet supervisor, which dispatches to three scoped Haiku sub-agents (sampling, fraud-risk, standards), each calling only its own tools on a shared MCP server wrapping five shipped projects; the supervisor reconciles the sub-agents' answers into one synthesized, cited response.](https://raw.githubusercontent.com/neifertg/risk-analytics-portfolio/main/assets/audit-engagement-co-pilot-architecture.svg)

**[Audit Engagement Co-Pilot](https://github.com/neifertg/risk-analytics-portfolio/tree/main/audit-engagement-co-pilot)** — hierarchical multi-agent system: a Sonnet supervisor dispatching to specialist sub-agents (sampling, fraud-risk, standards) over a real MCP server, with genuine fan-out + reconciliation and a 6/6 multi-agent eval suite. Deployed live via Docker on Render.

[Live demo →](https://audit-engagement-co-pilot.onrender.com)
</div>

<div class="card-flagship" markdown="1">
<span class="flagship-badge">Flagship</span>

![Audit Procedures RAG Assistant answering a question with cited sources and per-session cost tracking](https://raw.githubusercontent.com/neifertg/risk-analytics-portfolio/main/assets/audit-rag-assistant-demo.png)

**[Audit Procedures RAG Assistant](https://github.com/neifertg/risk-analytics-portfolio/tree/main/audit-rag-assistant)** — LLM question-answering grounded in an audit-procedures corpus, with a groundedness guardrail that declines to answer rather than guess. Now also demos real-organization tailoring: University of California's own public audit records toggled against generic guidance, side by side.

[Live demo →](https://84abkcnqvptyedbbssztx8.streamlit.app/)
</div>

**Also in that portfolio — six more real, working audit-analytics tools:**

<div class="card-grid" markdown="1">
<div class="card" markdown="1">
**[Benford's Law Analyzer](https://github.com/neifertg/risk-analytics-portfolio/tree/main/benfords-law-analyzer)** — forensic-accounting screening run against ~6,400 real SEC EDGAR filings (chi-square p=0.20).
</div>
<div class="card" markdown="1">
**[Duplicate Vendor Payment Checker](https://github.com/neifertg/risk-analytics-portfolio/tree/main/duplicate-vendor-payment-checker)** — four named AP-recon techniques, 98% recall / 100% precision on a seeded ledger.
</div>
<div class="card" markdown="1">
**[Journal Entry Testing Analyzer](https://github.com/neifertg/risk-analytics-portfolio/tree/main/journal-entry-testing-analyzer)** — AU-C 240 / PCAOB AS 2401 fraud-risk journal-entry testing, 100% recall across five risk criteria.
</div>
<div class="card" markdown="1">
**[Segregation-of-Duties Conflict Checker](https://github.com/neifertg/risk-analytics-portfolio/tree/main/sod-conflict-checker)** — access-based SoD conflict detection, 100% recall and precision on synthetic access data.
</div>
<div class="card" markdown="1">
**[Statistical Audit Sampling Calculator](https://github.com/neifertg/risk-analytics-portfolio/tree/main/sampling-calculator)** — attribute and MUS/PPS sampling verified against 10 real published AICPA reliability-factor table values.
</div>
<div class="card" markdown="1">
**[Presentation Deck Builder](https://github.com/neifertg/risk-analytics-portfolio/tree/main/deck-builder)** — generator for branded, self-contained reveal.js training decks; real 16-slide "Anomaly Detection for Internal Audit" example. [Live demo](https://neifertg.github.io/risk-analytics-portfolio/deck-builder/decks/anomaly-detection-for-internal-audit/index.html)
</div>
</div>

Also in that repo, outside the audit domain — general applied-ML breadth:
**[Ames Housing Price Prediction](https://github.com/neifertg/risk-analytics-portfolio/tree/main/ames-housing-price-prediction)** (Ridge/Lasso/Random Forest, real Kaggle data) and **[IMDB Review Text Analytics](https://github.com/neifertg/risk-analytics-portfolio/tree/main/imdb-review-text-analytics)** (classical NLP — LDA topics, lexicon sentiment, a trained Naive Bayes classifier).

**[Explore the full portfolio →](https://neifertg.github.io/risk-analytics-portfolio/)**

**Currently building:** [wilderness-trail](https://github.com/neifertg/wilderness-trail) *(private — happy to walk through it, just ask)*, a GPS-aware, live-weather Oregon Trail-style survival sim with Duolingo-style species-ID training.

<a id="professional-impact"></a>

## Professional Impact

Enterprise-scale work built at Fannie Mae and HealthEquity — internal tools, not public repos, but the clearest proof of what I build at scale:

- **RADAR** (Risk Analytics Data for Access Review) — a web application automating 13 ITGC controls across access, change management, and incident management, replacing manual sampling with full-population testing. **~930 hrs/year** saved.
- **10 custom GitHub Copilot agents + AI governance framework** (`VS_Template_Files`) — role boundaries, IIA-aligned guardrails, and communication standards for safely using GenAI in audit work. Cut analytics time **80%**, expanded test coverage **3x**.
- **GXS Data XRAY** — R Shiny app automating data-quality assessment and field-level analysis across enterprise datasets, with AI-ready context packages for faster project onboarding.

Also on GitHub: [family-meal-planner](https://github.com/neifertg/family-meal-planner) (meal planning) · [android-lab](https://github.com/neifertg/android-lab) (Android-as-server experiments).

<a id="beyond-work"></a>

## Beyond Work

I'm a dad first — most weekends we're on a trail somewhere in Virginia or West Virginia, hiking or fishing, or I'm out for a run. I read a lot: *East of Eden* is the book I keep coming back to, and *Radical Candor* and *Dare to Lead* have shaped the leader and team member I strive to be. I'm also a die-hard Civil War history buff and an Abraham Lincoln admirer — living in Virginia means the battlefields are basically in my backyard. 

Lately I've been teaching myself electronics for fun, not work: I built a basketball shot-clock game with an Arduino and a VL53L0X time-of-flight sensor to detect made shots, and I'm working my way toward real robotics next.

I care about real results and creation, not smoke and mirrors — too much of the current AI conversation is leaders, professionals, and companies performing AI use without valuable outputs.

<a id="background-resume"></a>

## Background & Résumé

**[Download résumé (PDF)](/assets/resume.pdf)**

<details class="resume-details" markdown="1">
<summary>Show full experience, education, certifications &amp; skills</summary>

### Experience

<div class="timeline" markdown="1">
<div class="timeline-entry" markdown="1">
<div class="timeline-header"><span class="timeline-role">Senior Risk Analyst &amp; Data Scientist</span><span class="timeline-meta">Fannie Mae · Feb 2022 – Present</span></div>

- Built 10 custom GitHub Copilot agents and authored the supporting AI governance framework (role boundaries, IIA-aligned guardrails, communication standards) — reducing audit analytics time by 80% while expanding test coverage 3x.
- Built RADAR (Risk Analytics Data for Access Review), a web application automating 13 ITGC controls across access, change management, and incident management — replacing manual sampling with full-population testing and saving an estimated ~930 hours/year.
- Built and deployed ML models (NLP, anomaly detection, peer analysis), R Shiny dashboards, and automated ETL pipelines; partnered with IT, audit, and risk stakeholders to define KPIs and co-design scalable analytics aligned with enterprise data governance.
</div>
<div class="timeline-entry" markdown="1">
<div class="timeline-header"><span class="timeline-role">Senior Internal Auditor – Data Analytics Lead</span><span class="timeline-meta">HealthEquity · Feb 2018 – Feb 2022</span></div>

- Built analytics pipelines and Tableau dashboards for audit, risk, and compliance monitoring; automated controls testing using SQL, VBA, and Azure.
- Managed GRC system integrations and delivered data solutions for internal stakeholders.
</div>
<div class="timeline-entry" markdown="1">
<div class="timeline-header"><span class="timeline-role">Information Technology Services Specialist</span><span class="timeline-meta">Brigham Young University · Aug 2017 – Feb 2018</span></div>

- Provided Tier 1–2 technical support, tracked issues in JIRA, diagnosed IT/networking problems, and documented workflows.
</div>
<div class="timeline-entry" markdown="1">
<div class="timeline-header"><span class="timeline-role">Audit/Risk Management Intern</span><span class="timeline-meta">HealthEquity · May 2017 – Aug 2017</span></div>

- Enhanced the cybersecurity audit work program; assisted with SOX risk assessment, walkthroughs, and tests of operating effectiveness.
</div>
<div class="timeline-entry" markdown="1">
<div class="timeline-header"><span class="timeline-role">Internal Audit Intern</span><span class="timeline-meta">Aegion Corporation · May 2016 – Aug 2016</span></div>

- Built a tracking tool for internal audit testing progress; assessed business controls and internal controls over financial reporting (SOX).
</div>
<div class="timeline-entry" markdown="1">
<div class="timeline-header"><span class="timeline-role">Sales Associate & Bitcoin Market Researcher</span><span class="timeline-meta">Bit49 (now Revolve Labs) · Nov 2015 – Jun 2016</span></div>

- Managed sales/client communications for cryptocurrency mining hardware; researched Bitcoin mining economics, break-even analysis, and ROI forecasting.
</div>
<div class="timeline-entry" markdown="1">
<div class="timeline-header"><span class="timeline-role">Missionary/Volunteer</span><span class="timeline-meta">The Church of Jesus Christ of Latter-day Saints · Aug 2012 – Aug 2014</span></div>

- Humanitarian volunteer in Paraguay; taught English classes, developed fluency in Spanish, trained and led other volunteers.
</div>
</div>

### Education

- **MS, Business Analytics** — University of Utah
- **BS, Statistics** — Brigham Young University

### Certifications

- Certified Internal Auditor (CIA) — IIA, issued Jul 2021
- COSO Internal Control Certificate — IIA, issued Oct 2019
- AWS Certified Cloud Practitioner — issued Apr 2022, expires Jun 2028
- Splunk Core Certified User — issued Jul 2025

### Skills

- **Languages:** Python, R, SQL, PowerShell
- **AI Engineering & ML:** NLP, Predictive Modeling, Clustering, Anomaly Detection, RAG, Multi-Agent Orchestration, Prompt Engineering, Evals, AI Governance
- **Cloud & DevOps:** AWS (SageMaker AI, Bedrock), Docker, GitHub Actions (CI)
- **Platforms & Tools:** VS Code, GitHub Copilot, MCP, Git, Jupyter, Posit (R), Tableau, Jira, Bitbucket, GRC Tools

</details>

<a id="contact"></a>

## Contact

- [GitHub](https://github.com/neifertg)
- [LinkedIn](https://www.linkedin.com/in/g-seth-neifert-7668b6b6/)
- [Email](mailto:gsneifert@gmail.com)
