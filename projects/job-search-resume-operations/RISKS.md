# Job Search and Resume Operations Risks

## Active risks

### R1. Unconfirmed job-search details could be recorded as facts
- **Severity:** High
- **Likelihood:** Medium
- **Owner or Butler:** Head Butler / Project Manager Butler
- **Impact:** The project could contain invented employers, applications, dates, accomplishments, or contacts.
- **Mitigation:** Record only Philip-confirmed information and keep unknowns in `AWAITING_PHILIP.md`.
- **Status:** Open

### R2. Sensitive personal or contact information could be committed
- **Severity:** High
- **Likelihood:** Medium
- **Owner or Butler:** Project Manager Butler
- **Impact:** Private job-search data could be exposed in repository history.
- **Mitigation:** Do not commit secrets, credentials, private recruiter messages, private contact details, or sensitive personal data.
- **Status:** Open

### R3. Workspace-level and project-level records could drift
- **Severity:** Medium
- **Likelihood:** Medium
- **Owner or Butler:** Head Butler
- **Impact:** Workspace status and project status could contradict each other.
- **Mitigation:** Keep workspace-level records in `project-office/` and project-level records in `projects/job-search-resume-operations/`.
- **Status:** Open
