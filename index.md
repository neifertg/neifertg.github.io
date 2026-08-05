---
layout: default
title: "G. Seth Neifert — Internal Audit & Risk Analytics"
description: "Internal audit & risk analytics professional building automation, AI tooling, and real working audit-analytics projects."
---

<button id="toggle-dark" style="position:fixed;top:1rem;right:1rem;z-index:1000;" aria-label="Toggle dark mode" aria-pressed="false">🌙 Toggle Dark Mode</button>
<script>
  document.addEventListener('DOMContentLoaded', function() {
    const btn = document.getElementById('toggle-dark');
    const setMode = (on) => {
      document.body.classList.toggle('dark-mode', on);
      btn.setAttribute('aria-pressed', on ? 'true' : 'false');
      localStorage.setItem('darkMode', on ? '1' : '');
    };
    btn.onclick = () => setMode(!document.body.classList.contains('dark-mode'));
    if (localStorage.getItem('darkMode')) setMode(true);
  });
</script>

# G. Seth Neifert

**Internal Audit & Risk Analytics** — I build the automation and AI tooling most audit teams only talk about.

[GitHub](https://github.com/neifertg) · [LinkedIn](https://www.linkedin.com/in/g-seth-neifert-7668b6b6/) · [Email](mailto:gsneifert@gmail.com) · [Résumé & Experience](#background-resume)

---

## What I Do

I'm a Senior Associate on Fannie Mae's Internal Audit Data & Analytics team, where I build the tools that turn manual, sample-based audit work into automated, full-population testing — and I write the AI governance frameworks that make it safe to bring GenAI into audit workflows. Outside of work, I ship real, working risk-analytics projects in public: no mockups, honest write-ups of what broke and how it got fixed.

I hold a Certified Internal Auditor (CIA) designation and an MS in Business Analytics, and I work at the intersection most audit teams are still trying to figure out: deep domain knowledge of audit/risk standards *and* the engineering ability to actually build the automation.

---

## Featured Work

### [Risk & Audit Analytics Portfolio](https://github.com/neifertg/risk-analytics-portfolio)

![Audit Procedures RAG Assistant answering a question with cited sources and per-session cost tracking](https://raw.githubusercontent.com/neifertg/risk-analytics-portfolio/main/assets/audit-rag-assistant-demo.png)

My flagship public portfolio — six real, working internal-audit and risk-analytics projects, each with real data, real metrics, and honest write-ups of what broke:

- **[Audit Procedures RAG Assistant](https://github.com/neifertg/risk-analytics-portfolio/tree/main/audit-rag-assistant)** — LLM question-answering grounded in an audit-procedures corpus, with a groundedness guardrail that declines to answer rather than guess. [Live demo](https://84abkcnqvptyedbbssztx8.streamlit.app/)
- **[Benford's Law Analyzer](https://github.com/neifertg/risk-analytics-portfolio/tree/main/benfords-law-analyzer)** — forensic-accounting screening run against ~6,400 real SEC EDGAR filings (chi-square p=0.20).
- **[Duplicate Vendor Payment Checker](https://github.com/neifertg/risk-analytics-portfolio/tree/main/duplicate-vendor-payment-checker)** — four named AP-recon techniques, 98% recall / 100% precision on a seeded ledger.
- **[Journal Entry Testing Analyzer](https://github.com/neifertg/risk-analytics-portfolio/tree/main/journal-entry-testing-analyzer)** — AU-C 240 / PCAOB AS 2401 fraud-risk journal-entry testing, 100% recall across five risk criteria.
- **[Segregation-of-Duties Conflict Checker](https://github.com/neifertg/risk-analytics-portfolio/tree/main/sod-conflict-checker)** — access-based SoD conflict detection, 100% recall and precision on synthetic access data.
- **[Statistical Audit Sampling Calculator](https://github.com/neifertg/risk-analytics-portfolio/tree/main/sampling-calculator)** — attribute and MUS/PPS sampling verified against 10 real published AICPA reliability-factor table values.

**[Explore the full portfolio →](https://neifertg.github.io/risk-analytics-portfolio/)**

---

## Professional Impact

Enterprise-scale work built at Fannie Mae and HealthEquity — internal tools, not public repos, but the clearest proof of what I build at scale:

- **RADAR** (Risk Analytics Dashboard for Access Review) — an R Shiny platform automating ITGC controls testing across access, change management, and incident management, replacing manual sampling with full-population testing. Estimated **~930 hours/year** saved.
- **AI governance framework + custom GitHub Copilot agents** (`VS_Template_Files`) — role boundaries, IIA-aligned guardrails, and communication standards for safely using GenAI in audit work. Cut audit analytics time **80%** while expanding test coverage **3x**.
- **GXS Data XRAY** — an R Shiny application automating data quality assessment, document conversion, and field-level analysis across enterprise datasets, speeding up project onboarding with AI-ready context packages.

---

## Currently Building

- **[wilderness-trail](https://github.com/neifertg/wilderness-trail)** *(private repo — happy to walk through it, just ask)* — an active side project in TypeScript.
- New additions to the [risk-analytics-portfolio](https://github.com/neifertg/risk-analytics-portfolio) — this list grows as projects ship.

---

## Other Interests & Side Projects

- **[family-meal-planner](https://github.com/neifertg/family-meal-planner)** — a meal-planning application to help organize weekly family meals.
- **[android-lab](https://github.com/neifertg/android-lab)** — an experimentation lab turning an old Android phone into a remote server, plus feature/audio testing.
- **[economics](https://github.com/neifertg/economics)** — personal economics experiments and analysis.

---

<a id="background-resume"></a>

## Background & Résumé

### Experience

**Internal Audit — Senior Associate, Data & Analytics**
*Fannie Mae · Feb 2022 – Present*
- Architected and deployed RADAR, an R Shiny platform automating ITGC controls testing — full-population testing instead of manual sampling, ~930 hrs/year saved.
- Built custom GitHub Copilot agents and authored the supporting AI governance framework — cut audit analytics time 80% while expanding test coverage 3x.
- Built GXS Data XRAY, automating data quality assessment, document conversion, and field-level analysis across enterprise datasets.
- Led department-wide Data Labs training on advanced analytics, AI enablement, and practical GenAI use cases.
- Built and deployed ML models (NLP, anomaly detection, peer analysis), R Shiny dashboards, and automated ETL pipelines, partnering with IT, audit, and risk stakeholders.

**Internal Auditor**
*HealthEquity · Feb 2018 – Feb 2022*
- Project-managed the Data Analytics program aligning risk with team strategy; tools: SQL Management Studio, Azure, Windows PowerShell.
- Led issue-remediation reporting (Tableau, VBA-enabled workbooks) tracking high-risk issues through their lifecycle for IA and Executive management.
- Administered the GRC platform — data maintenance, dashboard development, partner relations, training, reporting, and user access.
- Participated in risk assessment, planning, fieldwork, and reporting for SOX and operational engagements.

**Information Technology Services Specialist**
*Brigham Young University · Aug 2017 – Feb 2018*
- Provided Tier 1–2 technical support, tracked issues in JIRA, diagnosed IT/networking problems, and documented workflows.

**Audit/Risk Management Intern**
*HealthEquity · May 2017 – Aug 2017*
- Enhanced the cybersecurity audit work program; assisted with SOX risk assessment, walkthroughs, and tests of operating effectiveness.

**Internal Audit Intern**
*Aegion Corporation · May 2016 – Aug 2016*
- Built a tracking tool for internal audit testing progress; assessed business controls and internal controls over financial reporting (SOX).

**Sales Associate & Bitcoin Market Researcher**
*Bit49 (now Revolve Labs) · Nov 2015 – Jun 2016*
- Managed sales/client communications for cryptocurrency mining hardware; researched Bitcoin mining economics, break-even analysis, and ROI forecasting.

**Missionary/Volunteer**
*The Church of Jesus Christ of Latter-day Saints · Aug 2012 – Aug 2014*
- Humanitarian volunteer in Paraguay; taught English classes, developed fluency in Spanish, trained and led other volunteers.

### Education

- **MS, Business Analytics** — University of Utah
- **BS, Statistics** — Brigham Young University

### Certifications

- Certified Internal Auditor (CIA) — IIA, issued Jul 2021
- COSO Internal Control Certificate — IIA, issued Oct 2019
- AWS Certified Cloud Practitioner — issued Apr 2022, expires Jun 2028
- Splunk Core Certified User — issued Jul 2025

### Skills

Python · R / Shiny · SQL · NLP · Machine Learning · GenAI / Copilot Agent Development · Tableau · VBA · Azure · AWS · Splunk · ETL Pipeline Design

---

## Contact

- [GitHub](https://github.com/neifertg)
- [LinkedIn](https://www.linkedin.com/in/g-seth-neifert-7668b6b6/)
- [Email](mailto:gsneifert@gmail.com)
