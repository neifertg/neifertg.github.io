---
layout: default
title: G. Seth Neifert
description: "Data scientist delivering insights and efficiencies for internal audit, risk, and compliance teams — real, deployed projects."
---

<section class="hero" id="top">
<div class="container hero-inner">
<div class="hero-text">
<p class="eyebrow">Data scientist · Internal audit &amp; risk</p>
<h1>Risk, controls, and analytics | Turning messy data into insights and efficiencies | CIA, MS Business Analytics</h1>
<p class="hero-lede">More than eight years across internal audit, risk, and compliance. I find faster, more complete ways to test controls and surface risk, and I keep the judgment with people.</p>
<div class="button-row">
<a class="button" href="#featured-work">See featured work</a>
<a class="button-secondary" href="/assets/resume.pdf">Download résumé (PDF)</a>
</div>
</div>
<div class="hero-photo">
<img src="/assets/profile.jpg" alt="Photo of G. Seth Neifert" width="200" height="200">
</div>
</div>
</section>

<section class="section" id="featured-work">
<div class="container">
<div class="section-head">
<h2>Featured work</h2>
<a href="https://github.com/neifertg">All projects on GitHub →</a>
</div>
<p class="section-intro">The 10-K drift report and the analytics tools below are meant to answer a risk, controls, or audit question from the source material, or hand it to the right tool, and show the work. If the source does not support a conclusion, they say so.</p>

<div class="card-grid">
<article class="card">
<h3><a href="https://neifertg.github.io/10k-drift-detector/">10-K disclosure drift</a></h3>
<p>Compares Item 1A (Risk Factors) and Item 9A (Controls and Procedures) across consecutive Form 10-Ks, then compares those changes between peers in six sectors, including Walmart and Costco. Every finding on the company and peer pages quotes the filing sentence it came from and links to that filing. If a comparison is not supported, the report says so and does not fill the gap.</p>
<div class="card-links"><a href="https://neifertg.github.io/10k-drift-detector/">Live demo →</a><a href="https://github.com/neifertg/10k-drift-detector">Code →</a></div>
</article>

<article class="card">
<div class="card-media"><img src="https://raw.githubusercontent.com/neifertg/risk-analytics-portfolio/main/assets/audit-engagement-co-pilot-architecture.svg" alt="A question goes to a Sonnet supervisor, which dispatches to three scoped Haiku sub-agents (sampling, fraud-risk, standards), each calling only its own tools on a shared MCP server; the supervisor reconciles their answers into one cited response." loading="lazy"></div>
<p class="card-label is-flagship">Flagship · Multi-agent AI</p>
<h3><a href="https://github.com/neifertg/risk-analytics-portfolio/tree/main/audit-engagement-co-pilot">Audit Engagement Co-Pilot</a></h3>
<p>An auditor asks one question and gets one cited answer, assembled from sampling, fraud-risk, and standards checks. A Sonnet supervisor dispatches to specialist sub-agents over a real MCP server, with fan-out, reconciliation, and a 6/6 multi-agent eval suite. Deployed live via Docker on Render.</p>
<div class="card-links"><a href="https://audit-engagement-co-pilot.onrender.com">Live demo →</a><a href="https://github.com/neifertg/risk-analytics-portfolio/tree/main/audit-engagement-co-pilot">Code →</a></div>
</article>

<article class="card">
<div class="card-media"><img src="https://raw.githubusercontent.com/neifertg/risk-analytics-portfolio/main/assets/audit-rag-assistant-demo.png" alt="Audit Procedures RAG Assistant answering a question with cited sources and per-session cost tracking" loading="lazy"></div>
<p class="card-label is-flagship">Flagship · RAG</p>
<h3><a href="https://github.com/neifertg/risk-analytics-portfolio/tree/main/audit-rag-assistant">Audit Procedures RAG Assistant</a></h3>
<p>Answers a procedure question from a written audit library, and declines when that library does not support an answer. Now also demos real-organization tailoring: University of California's own public audit records toggled against generic guidance, side by side.</p>
<div class="card-links"><a href="https://84abkcnqvptyedbbssztx8.streamlit.app/">Live demo →</a><a href="https://github.com/neifertg/risk-analytics-portfolio/tree/main/audit-rag-assistant">Code →</a></div>
</article>

<article class="card">
<p class="card-label is-flagship">Flagship · Interactive guide</p>
<h3><a href="https://neifertg.github.io/ml-field-guide/">ML Field Guide</a></h3>
<p>Helps a reader without a statistics background pick a machine-learning technique and explain why it fits. 19 techniques, each with plain-English mechanics, good and poor fits, and a verified citation, plus a decision flowchart, a step-by-step wizard, and a review quiz.</p>
<div class="card-links"><a href="https://neifertg.github.io/ml-field-guide/">Explore the guide →</a></div>
</article>

<article class="card">
<p class="card-label">Developer tool · Open source</p>
<h3><a href="https://github.com/neifertg/capitan">capitan</a></h3>
<p>Keeps AI coding agents on course: every change starts from a one-page plan tied to a goal, gets checked by a second agent before it merges, and leaves its lessons for the next plan. Works with any AI coding tool.</p>
<div class="card-links"><a href="https://github.com/neifertg/capitan#how-it-works">See how it works →</a></div>
</article>
</div>

<div class="band">
<p><strong>Risk &amp; Audit Analytics Portfolio:</strong> six more working audit-analytics tools, each with real data, real metrics, and honest write-ups of bugs and fixes over time.</p>
<a class="band-link" href="https://neifertg.github.io/risk-analytics-portfolio/">Explore the portfolio →</a>
</div>

<details class="more">
<summary>Show the six tools</summary>
<div class="card-grid">
<div class="card"><p><strong><a href="https://github.com/neifertg/risk-analytics-portfolio/tree/main/benfords-law-analyzer">Benford's Law Analyzer</a></strong> — Screens a set of financial figures for an unusual leading-digit pattern, a standard forensic check. Run against ~6,400 real SEC EDGAR filings (chi-square p=0.20).</p></div>
<div class="card"><p><strong><a href="https://github.com/neifertg/risk-analytics-portfolio/tree/main/duplicate-vendor-payment-checker">Duplicate Vendor Payment Checker</a></strong> — Flags likely duplicate vendor payments. Four named AP-recon techniques, 98% recall / 100% precision on a seeded ledger.</p></div>
<div class="card"><p><strong><a href="https://github.com/neifertg/risk-analytics-portfolio/tree/main/journal-entry-testing-analyzer">Journal Entry Testing Analyzer</a></strong> — Flags journal entries that match standard fraud-risk tests. AU-C 240 / PCAOB AS 2401 journal-entry testing, 100% recall across five risk criteria.</p></div>
<div class="card"><p><strong><a href="https://github.com/neifertg/risk-analytics-portfolio/tree/main/sod-conflict-checker">Segregation-of-Duties Conflict Checker</a></strong> — Flags users who hold both sides of a duty that should be split between two people. 100% recall and precision on synthetic access data.</p></div>
<div class="card"><p><strong><a href="https://github.com/neifertg/risk-analytics-portfolio/tree/main/sampling-calculator">Statistical Audit Sampling Calculator</a></strong> — Plans an audit sample and checks the math against published audit tables. Attribute and MUS/PPS sampling verified against 10 real published AICPA reliability-factor table values.</p></div>
<div class="card"><p><strong><a href="https://github.com/neifertg/risk-analytics-portfolio/tree/main/deck-builder">Presentation Deck Builder</a></strong> — Turns an outline into a branded training deck: self-contained reveal.js decks, with a real 16-slide "Anomaly Detection for Internal Audit" example. <a href="https://neifertg.github.io/risk-analytics-portfolio/deck-builder/decks/anomaly-detection-for-internal-audit/index.html">Live demo</a></p></div>
</div>
<p class="note">Also in that repo, outside the audit domain: <a href="https://github.com/neifertg/risk-analytics-portfolio/tree/main/ames-housing-price-prediction">Ames Housing Price Prediction</a> (Ridge/Lasso/Random Forest on real Kaggle data) and <a href="https://github.com/neifertg/risk-analytics-portfolio/tree/main/imdb-review-text-analytics">IMDB Review Text Analytics</a> (LDA topics, lexicon sentiment, a trained Naive Bayes classifier).</p>
</details>

<p class="note"><strong>Currently building:</strong> wilderness-trail <em>(private, in progress; happy to walk through it, just ask)</em>, a GPS-aware, live-weather Oregon Trail-style survival sim with Duolingo-style species-ID training.</p>
</div>
</section>

<section class="section" id="about">
<div class="container about-grid">
<div class="about-text" id="what-i-do">
<h2>About</h2>
<p>I work across risk, controls, and compliance, and I look for faster, more complete ways to test controls and surface risk. At Fannie Mae I automated IT controls testing, saving an estimated 930 hours a year, and cut audit analytics time by 80% while tripling test coverage. I use IIA-aligned standards to govern AI responsibly, and I leave the judgment with people. CIA. MS Business Analytics (Utah). BS Statistics (BYU). Fluent Spanish.</p>
<p id="beyond-work">Most weekends I'm on a family hike somewhere in Virginia or West Virginia, hiking or fishing, or I'm out for a run. I read a lot: <em>East of Eden</em>, <em>Radical Candor</em>, <em>Dare to Lead</em>, and <em>Never Split the Difference</em> are some of my favorites this year. I'm also a Civil War history buff, and love exploring northern Virginia.</p>
</div>
</div>
</section>

<section class="section" id="background-resume">
<div class="container" markdown="1">
<h2>Résumé</h2>
<div class="resume-cta">
<a class="button" href="/assets/resume.pdf">Download résumé (PDF)</a>
</div>

<details class="more" markdown="1">
<summary>Show full experience, education, certifications &amp; skills</summary>

### Experience

<div class="timeline" markdown="1">
<div class="timeline-entry" markdown="1">
<div class="timeline-header"><span class="timeline-role">Senior Risk Analyst &amp; Data Scientist</span><span class="timeline-meta">Fannie Mae · Feb 2022 – Present</span></div>

- Applied machine learning to Splunk-based event-log analysis across hundreds of millions of records to surface hidden behavioral and operational patterns for IT and Operations audits — findings drove substantial control redesign and enhancement recommendations.
- Saved an estimated 930 hours a year by automating IT controls testing across the full population instead of samples.
- Cut audit analytics time by 80% and tripled test coverage, and wrote AI governance standards aligned with IIA guidelines.
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
</div>
</section>

<section class="contact" id="contact">
<div class="container contact-inner">
<div>
<h2>Let's talk</h2>
<p>Questions about any of these projects, or about working together, are welcome.</p>
</div>
<ul>
<li><a href="https://github.com/neifertg">GitHub</a></li>
<li><a href="https://www.linkedin.com/in/g-seth-neifert-7668b6b6/">LinkedIn</a></li>
<li><a href="mailto:gsneifert@gmail.com">Email</a></li>
</ul>
</div>
</section>
