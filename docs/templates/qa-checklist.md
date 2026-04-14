# QA Checklist (Template)

Purpose: Standard checklist to ensure consistent QA coverage and traceability.

Before testing
- [ ] Acceptance criteria and DoD are documented in the backlog item
- [ ] Test environment is up-to-date and matches staging configuration
- [ ] Test data and accounts available for critical flows

Test types (apply as relevant)
- [ ] Unit tests: new/changed code has automated unit tests added
- [ ] Integration tests: verify cross-service or API interactions
- [ ] End-to-end / smoke tests: validate critical user journeys
- [ ] Accessibility checks for UI changes (contrast, keyboard nav)
- [ ] Performance checks for changes with expected load impact
- [ ] Security checks and SAST/DAST where applicable

During testing
- [ ] Run automated test suite and record results
- [ ] Execute manual exploratory tests on new flows
- [ ] Log defects with clear reproduction steps and environment details
- [ ] Verify fixes and regression areas

Before sign-off
- [ ] No open high-severity defects
- [ ] Acceptance criteria verified and signed off by Product
- [ ] QA findings and test coverage documented in PR or ticket
