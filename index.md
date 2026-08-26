---
layout: default
title: "Data Scientist for Internal Audit & Risk"
description: "Data scientist delivering insights and efficiencies for internal audit, risk, and compliance teams — real, deployed projects."
---

<a id="what-i-do"></a>

## What I Do

9 years delivering insights and efficiencies across internal audit, enterprise risk, and compliance. I leverage data science, machine learning, and analytics to provide department and enterprise wide insights and efficiencies. CIA-certified, MS in Business Analytics: the rare combination of real risk/audit domain depth and the engineering to build out end to end automated workflows, not just spec it.

Outside of work I've started a working risk-analytics projects in a public repo. I've found that multi-agent systems don't reach production and most RAG projects fail on corpus quality, not model choice; the two flagship projects in Featured Work below are proof I build that way — real orchestration, real evals, and the retrieval layer treated as infrastructure (schema-validated, linted, CI-checked).

<a id="featured-work"></a>

## Featured Work

### [Risk & Audit Analytics Portfolio](https://github.com/neifertg/risk-analytics-portfolio)

Working risk-analytics projects, each with real data, real metrics, and honest write-ups of bugs and fixes over time. The two flagship pieces below are the deepest AI-engineering proof; six more real audit-analytics tools follow.

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

### [ML Field Guide](https://neifertg.github.io/ml-field-guide/)

<div class="card-flagship" markdown="1">
<span class="flagship-badge">Flagship</span>

![ML Field Guide's decision flowchart, routing from a plain-language question about your target variable down through the supervised and unsupervised branches to a recommended technique](https://raw.githubusercontent.com/neifertg/ml-field-guide/master/assets/images/flowchart-snapshot.png)

**[ML Field Guide](https://neifertg.github.io/ml-field-guide/)** — a from-scratch reference covering 19 ML techniques, each with plain-English mechanics, good/poor-fit cases, and a verified citation. Includes an interactive decision flowchart, a step-by-step wizard, and a review quiz, written for readers without a stats background.

[Explore the guide →](https://neifertg.github.io/ml-field-guide/)
</div>

**Currently building:** [wilderness-trail](https://github.com/neifertg/wilderness-trail) *(private — happy to walk through it, just ask)*, a GPS-aware, live-weather Oregon Trail-style survival sim with Duolingo-style species-ID training.

<a id="beyond-work"></a>

## Beyond Work

Most weekends I'm on on a family hike somewhere in Virginia or West Virginia, hiking or fishing, or I'm out for a run. I read a lot: *East of Eden* is the book I keep coming back to, and *Radical Candor* and *Dare to Lead* have shaped the leader and team member I strive to be. I'm also a Civil War history buff, and I am loving being so close to that history here in northern Virginia.

Lately I've been teaching myself electronics for fun, not work: I built a basketball shot-clock game with an Arduino and a VL53L0X time-of-flight sensor to detect made shots, and I'm working my way toward real robotics next.

<a id="background-resume"></a>

## Background & Résumé

**[Download résumé (PDF)](/assets/resume.pdf)**

<details class="resume-details" markdown="1">
<summary>Show full experience, education, certifications &amp; skills</summary>

### Experience

<div class="timeline" markdown="1">
<div class="timeline-entry" markdown="1">
<div class="timeline-header"><span class="timeline-role">Senior Risk Analyst &amp; Data Scientist</span><span class="timeline-meta">Fannie Mae · Feb 2022 – Present</span></div>

- Applied machine learning to Splunk-based event-log analysis across hundreds of millions of records to surface hidden behavioral and operational patterns for IT and Operations audits — findings drove substantial control redesign and enhancement recommendations.
- Automated 13 access, change-management, and incident-management controls, replacing manual sampling with full-population testing — ~930 hours/year saved.
- Built and rolled out an AI governance framework and a suite of GenAI coding agents with role-scoped guardrails aligned to IIA standards, enabling non-technical department staff to independently perform AI-assisted analytics with standardized documentation of results — cut analytics turnaround time 80%, expanded test coverage 3x.
- Currently architecting an internal department wiki extending that governance framework into a shared, trusted methodology base — scaling AI-assisted workflows with the same guardrails across the team.
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

- [GitHub](https://github.com/neifertg) — also see [family-meal-planner](https://github.com/neifertg/family-meal-planner) (meal planning) and [android-lab](https://github.com/neifertg/android-lab) (Android-as-server experiments)
- [LinkedIn](https://www.linkedin.com/in/g-seth-neifert-7668b6b6/)
- [Email](mailto:gsneifert@gmail.com)
