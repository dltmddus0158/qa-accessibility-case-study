# Test Strategy

## Overall Approach
Testing was conducted using a manual, exploratory-first approach to understand the site’s structure,
followed by targeted test cases to validate critical navigation and search behaviors.

An accessibility-first lens was applied throughout testing, informed by WCAG principles and prior
experience in document and web accessibility remediation.

## Testing Methods
- Exploratory testing to identify risk areas and common user paths
- Structured test cases for repeatability and clarity
- Manual keyboard-only testing to assess non-mouse access
- Heuristic accessibility review focused on navigation, structure, and feedback

## QA Process
The workflow followed a structured QA lifecycle:

1. Define scope and risks
2. Conduct exploratory testing
3. Document test cases and findings
4. Write reproducible bug reports
5. Review issues and prioritize based on impact

This approach is inspired by prior experience with multi-round remediation workflows
(R1 → optional additional pass → R2 cross-checking), emphasizing independent review
and quality verification.

## Prioritization Criteria
- **P0:** Blocks access to core navigation or information
- **P1:** Major usability or accessibility barriers
- **P2:** Minor usability issues or inconsistencies

## Technical Awareness

While this case study focuses on manual QA, testing decisions were informed by
an understanding of front-end behavior, including component state changes,
DOM structure, and client-side interactions.

Test scenarios consider how UI components may respond differently
based on user input, focus state, and navigation context.
