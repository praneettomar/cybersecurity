# Cybersecurity Assessment Visuals

## 1. Purpose

This directory is intended to contain visual summaries that communicate the findings and recommendations of the Botium Toys cybersecurity assessment.

The objective is to make the assessment easier to understand for technical teams, business stakeholders, recruiters, and hiring managers.

Visuals should support the written analysis rather than replace it.

## 2. Planned Visuals

### Visual 1: Cybersecurity Risk Heat Map

**Objective:** Present the relative severity of identified risks using the proposed likelihood-and-impact scoring methodology.

**Planned content:**
- Likelihood scale from 1 to 5.
- Impact scale from 1 to 5.
- Risk ratings from Low to Critical.
- Risk IDs linked to the risk register.

**Source:** `docs/04-risk-assessment-methodology.md` and `docs/05-risk-register.csv`.

**Important note:** The heat map will use the portfolio's provisional risk estimates. It will not represent independently measured probabilities or official risk ratings.

### Visual 2: Security Control Overview

**Objective:** Summarise the principal controls reported as present, absent, or requiring improvement.

**Planned content:**
- Access management.
- Sensitive data protection.
- Backup and disaster recovery.
- Security monitoring.
- Endpoint protection.
- Network security.
- Physical security.
- Data governance.

The visual should distinguish reported control status from verified control effectiveness.

**Source:** `docs/03-controls-assessment.md`.

### Visual 3: Remediation Roadmap

**Objective:** Communicate the proposed sequence of cybersecurity improvements.

**Planned phases:**
- Days 0–30: Address urgent risks and establish ownership.
- Days 31–60: Strengthen access, data protection, and monitoring.
- Days 61–90: Improve recovery and operational security processes.
- Days 91–180: Validate controls and establish ongoing governance.

**Source:** `docs/08-remediation-roadmap.md`.

**Important note:** These are proposed planning periods, not approved implementation deadlines.

## 3. Visual Design Principles

All visuals should follow these principles:

- Use clear titles and descriptive labels.
- Keep text readable at normal screen size.
- Use consistent risk categories and terminology.
- Include the relevant source document or risk IDs.
- Explain assumptions and limitations where necessary.
- Avoid displaying confidential information.
- Ensure colours are not the only way to distinguish risk levels.
- Use a consistent, professional style across the portfolio.

## 4. File Naming Convention

Use descriptive, numbered filenames:

- `01-risk-heatmap.png`
- `02-control-overview.png`
- `03-remediation-roadmap.png`

If editable source files are created, retain them where practical so the visuals can be updated when the analysis changes.

## 5. Evidence and Accuracy

The visuals must remain consistent with the written assessment and risk register.

A visual must not imply that:
- Technical testing was completed when it was not.
- A proposed control has already been implemented.
- A preliminary risk rating is an independently verified measurement.
- A compliance framework has been formally certified.

## 6. Conclusion

Clear visuals can help translate cybersecurity analysis into business decisions. The planned diagrams will communicate risk prioritisation, control gaps, and the proposed improvement sequence while preserving the limitations of the underlying assessment.

