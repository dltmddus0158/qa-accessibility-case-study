# QA Accessibility Case Study

*This case study is for educational QA purposes only. No proprietary code or full content is included.*

## Overview

- **Target Website:** Center for Inclusive Design and Innovation (CIDI)  
  https://cidi.gatech.edu/  
  Georgia Tech – College of Design
- **Goal:** Demonstrate a manual QA and accessibility-focused testing workflow, including test planning, test case design, bug reporting, and accessibility auditing.
- **Role:** QA Analyst (manual testing, accessibility review, and documentation)

### Test Focus
- 🔍 Search functionality (discoverability, behavior, user feedback)
- 📂 Global navigation menu (structure, usability, and keyboard accessibility)

---

## What’s inside

- **Scope & Strategy:** `00-overview/`  
  Defines testing boundaries, assumptions, and overall QA approach.
- **Test Plan:** `01-test-plan/test-plan.md`  
  Documents objectives, test types, environments, and exit criteria.
- **Test Cases:** `02-test-cases/test-cases.md`  
  Structured test scenarios covering navigation, search, and accessibility.
- **Bug Reports:** `03-bug-reports/`  
  Reproducible bug reports with clear steps, expected vs. actual results, and impact.
- **Accessibility Audit:** `04-accessibility-audit/`  
  Checklist-based review and summarized accessibility findings.
- **Evidence (cropped):** `05-evidence/`  
  Supporting screenshots and visuals focused on issue areas only.
- **Retrospective:** `06-retrospective/lessons-learned.md`  
  Reflection on QA process, effectiveness, and improvement areas.

---

## QA Process (inspired by multi-round cross-checking)

- Plan → Execute → Report → Re-test
- Independent review mindset (“fresh eyes”) to reduce bias
- Risk-based prioritization to surface high-impact usability and accessibility issues first

This process is informed by prior experience in structured, multi-round remediation workflows
with peer cross-checking and weekly calibration discussions.

---

## Key Findings (sample)

1) Keyboard focus visibility on global navigation needs improvement — **P0 / Accessibility**
2) Search behavior lacks clear feedback when submitting empty queries — **P1 / Usability**
3) Heading and non-text content patterns should be reviewed for long-term consistency — **P2 / Accessibility**

(See full details in `03-bug-reports/` and `04-accessibility-audit/findings.md`.)

---

## How to review quickly (60 seconds)

1) Read the test scope and approach in `01-test-plan/test-plan.md`
2) Skim one representative bug report in `03-bug-reports/bug-001.md`
3) Review summarized accessibility findings in `04-accessibility-audit/findings.md`

---

## Contact

- **GitHub:** https://github.com/dltmddus0158  
- **LinkedIn:** https://www.linkedin.com/in/seungyeon-hannah-lee
