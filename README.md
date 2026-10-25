# FairNest UK

**Business feasibility of an evidence-led accommodation decision platform for international students — Coventry pilot**

**Student:** Venkata Saranya Manthina  
**Student ID:** 15987220  
**Programme:** International Business Management  
**Module:** 7001SOM Postgraduate Project  
**Route:** Route 3 — Business Plan + Artefact

## Project purpose

FairNest UK investigates a decision-quality problem in student accommodation. International students can already find rooms through university accommodation services, PBSA operators and major property platforms, but comparison is difficult because headline rent, contract length, booking cash, bills, agreement type, evidence quality and location are presented inconsistently.

The project therefore does **not** claim that the market lacks accommodation platforms. It evaluates whether an independent decision-support layer can make existing information easier to compare, more transparent and more useful before money is committed.

## Research aim

To evaluate the commercial, operational and responsible-business feasibility of FairNest UK as a platform that standardises total contract cost, known booking cash, contractual context, commute and source provenance for international students choosing Coventry accommodation.

## Research questions

1. What decision challenges and information gaps do international students face when securing UK accommodation?
2. Which standardised cost and verification signals make comparison across housing types meaningful?
3. Where do existing platforms and university guidance leave residual gaps?
4. What legal, ethical and data-sourcing safeguards should govern a pilot?

## Method

The completed study uses **secondary research only**. Evidence is triangulated across:

- official statistics and regulator research;
- UK government and ICO guidance;
- Coventry local-market evidence;
- peer-reviewed scholarship;
- first-party accommodation prices and payment terms;
- live competitor/platform features;
- specialist commercial market intelligence.

No survey, interview or focus-group findings are claimed in this repository.

## Key findings

- HESA reported **2,863,180 UK HE students in 2024/25**, while international enrolment fell 6% and international postgraduate-taught entrants fell 10%. The opportunity is therefore not based on automatic international-student growth.
- The Office for Students found that **69%** of respondents said expected accommodation cost strongly influenced institution choice; **15%** reported difficulty covering accommodation costs; only **54%** of West Midlands respondents described accommodation as good value.
- Coventry's 2024 PBSA market study reported a **41,835** student demand pool and **25,590** PBSA beds, with a **1.62:1** student-to-bed ratio against a **2.12:1** nationally observed reference. The study interpreted this as relative oversupply.
- Existing platforms already provide useful property comparison, search, safety and budgeting functions. FairNest is therefore positioned around a **residual integration gap**: normalised cost, booking cash, contract context, source provenance, visible uncertainty and user-controlled ranking.
- Year 1 remains funding-negative in all three modelled commercial scenarios. The project recommends a **stage-gated Coventry pilot**, not an assumption-led national launch.

## Artefact

`04_artifact/FairNest_Decision_Engine.html` is a functional browser-based prototype.

It demonstrates:

- separate weekly rent, total contract cost and known booking cash;
- user-adjustable decision weights;
- commute and room-type comparison;
- agreement-context prompts;
- source links and evidence-check dates;
- explicit missing-data treatment;
- parent/sponsor summary;
- a transparent Fit Score.

The Fit Score is a **preference-fit measure only**. It is not a safety certificate, legal-compliance score or property-quality guarantee.

## Repository structure

```text
01_project_management/
    project_overview.md
    research_questions_and_objectives.md
    research_method_and_ethics.md
    research_log.csv
    supervisor_feedback_log.csv

02_research_evidence/
    FairNest_Evidence_and_Financial_Model.xlsx
    master_source_register.csv
    literature_matrix.csv
    evidence_register.csv
    coventry_listing_dataset.csv
    competitor_audit.csv
    legal_governance_rules.csv
    evidence_hierarchy.md

03_analysis/
    market_and_customer_analysis.md
    competitor_gap_analysis.md
    decision_framework.md
    financial_model_notes.md
    financial_scenarios.csv
    risk_register.csv

04_artifact/
    FairNest_Decision_Engine.html
    artefact_specification.md
    fit_score_methodology.md
    requirements_traceability.csv
    test_record.csv
    validation_summary.md

05_report/
    final_report.md

06_quality_assurance/
    route3_rubric_map.csv
    evidence_traceability_matrix.csv
    final_qa_checklist.md
    limitations_and_future_validation.md
```

## Evidence rules used in the project

1. Prefer first-party, official and peer-reviewed evidence.
2. Record source URLs and evidence-check dates.
3. Separate observed facts from managerial assumptions.
4. Retain missing information rather than silently imputing favourable values.
5. Do not treat a provider category as proof of suitability.
6. Do not use paid status as an input to the organic Fit Score.
7. Apply legal prompts only after agreement context is identified.
8. Treat the Coventry pilot as a proof of concept, not national validation.

## Reproducibility

The Excel workbook is the authoritative analytical file because it retains formulas, assumptions and source registers. Git-readable CSV extracts are included for inspection. The HTML prototype requires no installation; open it in a modern browser.

## Project boundary

The project evaluates pre-launch feasibility. It does not claim:

- national market validation;
- observed student or provider willingness to pay;
- live provider adoption;
- measured retention or customer-acquisition cost;
- legal advice;
- a safety guarantee.

These are explicit future-validation requirements rather than hidden weaknesses.
