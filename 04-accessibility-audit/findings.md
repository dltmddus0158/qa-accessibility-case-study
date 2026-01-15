# Accessibility Findings Summary (WCAG-Informed)

This accessibility audit focuses on navigation and search components of the
Center for Inclusive Design and Innovation (CIDI) website.
Findings are based on manual testing with keyboard navigation and heuristic review
aligned with WCAG 2.1 success criteria.

---

## Summary of Key Findings

| ID | Area | Issue | WCAG Reference | Severity |
|----|------|------|---------------|----------|
| A11Y-001 | Navigation | Insufficient keyboard focus visibility | 2.4.7 Focus Visible | S2 |
| A11Y-002 | Search | Lack of feedback on empty submission | 3.3.2 Labels or Instructions / 3.2.2 On Input | S3 |
| A11Y-003 | Structure | Need for ongoing validation of heading and landmark consistency | 1.3.1 Info and Relationships | S3 |

---

## Detailed Findings

### A11Y-001: Keyboard focus indicator is insufficiently visible on global navigation
- **WCAG:** 2.4.7 Focus Visible
- **Description:**  
  When navigating the global navigation menu using the keyboard, the focus indicator
  is difficult to distinguish from surrounding elements.
- **Impact:**  
  Keyboard-only and low-vision users may lose track of their current position,
  increasing navigation errors and cognitive load.
- **Severity:** S2 (Major barrier for keyboard users)
- **Related Bug:** `BUG-001`

---

### A11Y-002: Search submission provides no clear feedback when query is empty
- **WCAG:**  
  - 3.3.2 Labels or Instructions  
  - 3.2.2 On Input
- **Description:**  
  Submitting the search form with an empty input does not provide visible or
  perceivable feedback to the user.
- **Impact:**  
  Users may be unsure whether the search feature is functioning, which can be
  particularly challenging for users with cognitive disabilities or first-time users.
- **Severity:** S3 (Moderate usability and accessibility concern)
- **Related Bug:** `BUG-002`

---

### A11Y-003: Structural consistency should be monitored for long-term accessibility
- **WCAG:** 1.3.1 Info and Relationships
- **Description:**  
  While the site generally presents a clear visual hierarchy, consistent validation
  of heading order and landmark usage is recommended as content grows.
- **Impact:**  
  Inconsistent structure can reduce navigability for screen reader users over time.
- **Severity:** S3 (Preventative / maintainability-related)

---

## Strengths Observed

- Clear visual layout and spacing support content scanning
- Navigation placement is consistent across pages
- Section titles are generally descriptive and meaningful

These strengths provide a solid foundation for maintaining accessibility as the site evolves.

---

## Recommendations

### High Priority
- Improve focus visibility for all interactive navigation elements
- Ensure focus styles meet contrast and visibility expectations

### Medium Priority
- Provide explicit feedback or instructions for search submission behavior
- Validate keyboard and screen reader feedback for form interactions

### Ongoing / Preventative
- Establish and document heading and landmark conventions
- Periodically review navigation and search components as content changes

---

## Notes

This audit represents a targeted review of navigation and search components
and is not a full WCAG conformance evaluation.
Findings are intended to support iterative improvement and risk-based prioritization.
