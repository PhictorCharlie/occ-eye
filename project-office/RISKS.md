# OCC-Eye Risks

## Active risks

### R1. Undefined product purpose
- **Severity:** High
- **Likelihood:** High
- **Owner or butler:** Product Butler
- **Impact:** Implementation could solve the wrong problem or require major rework.
- **Mitigation:** Do not create application code until Philip approves product direction, target user, core workflow, and MVP boundaries.
- **Status:** Open

### R2. Ambiguous acronym and product name
- **Severity:** Medium
- **Likelihood:** High
- **Owner or butler:** Product Butler
- **Impact:** Multiple plausible interpretations could lead to conflicting architecture and UX decisions.
- **Mitigation:** Capture interpretations clearly and request Philip's decision.
- **Status:** Open

### R3. Unknown data sensitivity
- **Severity:** High
- **Likelihood:** Medium
- **Owner or butler:** Product Butler / Development Butler
- **Impact:** Poor choices around storage, uploads, exports, access control, or retention could create privacy or compliance issues.
- **Mitigation:** Determine user-provided data, sensitivity, storage, and access requirements before architecture selection.
- **Status:** Open

### R4. Premature technical decisions
- **Severity:** Medium
- **Likelihood:** Medium
- **Owner or butler:** Head Butler / Development Butler
- **Impact:** The project may adopt unnecessary dependencies or a stack unsuitable for the approved workflow.
- **Mitigation:** Defer stack and integration choices until product scope is approved.
- **Status:** Open

### R5. No testable acceptance criteria yet
- **Severity:** Medium
- **Likelihood:** High
- **Owner or butler:** QA Butler
- **Impact:** Future implementation cannot be objectively verified.
- **Mitigation:** Product Butler must define user stories and acceptance criteria before development begins.
- **Status:** Open
