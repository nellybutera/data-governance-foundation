# Data Governance Foundation

A collection of practical data governance labs and case studies exploring AI fairness, regulatory compliance, and data quality in real-world African tech contexts.

---

## Overview

This repository documents hands-on work across four core data governance domains: bias detection in AI systems, enterprise data governance frameworks, multi-jurisdictional compliance, and data quality investigation. Each module is grounded in realistic African business scenarios.

---

## Modules

### 1. Bias Detection

**Scenario:** QA investigation of HireScore — an AI recruitment ranking tool deployed by TalentMatch AI, a Ghanaian HR tech company — following client complaints about unfair candidate scoring.

**What's covered:**
- Identifying historical, sampling, measurement, and proxy bias in training data
- Tracing bias entry points through the full ML pipeline
- Proposing tiered mitigation strategies (immediate, short-term, long-term)
- Evaluating trade-offs between fairness definitions (demographic parity, equalized odds, equal opportunity)

**Deliverable:** `Bias Investigation Report.pdf` — full bias audit with evidence, pipeline mapping, and a prioritised action plan.

---

### 2. Capstone — QuickLoan Data Governance Review

**Scenario:** End-to-end governance review of QuickLoan, a fintech lending platform, assessing data handling practices, risk exposure, and governance maturity.

**What's covered:**
- Governance framework gap analysis
- Data flow mapping and lineage documentation
- Risk identification and recommended controls
- Corrected data flow diagram

**Deliverables:**
- `QuickLoan_Governance_Review.pdf` — full written report
- `corrected_data_flow.png` — revised data flow diagram

---

### 3. Data Quality Detective Challenge

Investigative lab focused on identifying, classifying, and resolving data quality issues across common enterprise data scenarios.

---

### 4. Multi-Jurisdiction Compliance — ShopGhana

**Scenario:** Cross-border compliance assessment for ShopGhana, an e-commerce platform operating across multiple African jurisdictions with varying data protection regimes.

**What's covered:**
- Mapping applicable regulations per jurisdiction
- Gap analysis against regional data protection requirements
- Structured compliance response matrix

**Deliverable:** `ShopGhana_Compliance_Response_Matrix.pdf` — jurisdiction-by-jurisdiction compliance breakdown with remediation recommendations.

---

### Reference Material

| Document | Purpose |
|---|---|
| `Rwanda DPO.pdf` | Rwanda Data Protection Office regulatory guidance — used as a primary reference for East African data protection obligations |

---

## Structure

```
.
├── Bias Detection/
│   ├── Bias Investigation Report.pdf
│   └── Lab Description.txt
├── Capstone/
│   ├── QuickLoan_Governance_Review.pdf
│   └── corrected_data_flow.png
├── Data Quality Detective Challenge/
├── Multi-Jurisdiction/
│   └── ShopGhana_Compliance_Response_Matrix.pdf
└── Rwanda DPO.pdf
```
