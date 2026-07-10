# Philip Butler Workspace Risks

## Active risks

### R1. Legacy repository name may continue to imply a product
- **Severity:** Medium
- **Likelihood:** Medium
- **Owner or butler:** Head Butler
- **Impact:** Future work could accidentally reintroduce invented OCC-Eye meanings or assume an application exists.
- **Mitigation:** State in active documentation that `occ-eye` is a legacy repository name with no confirmed product meaning.
- **Status:** Open

### R2. Workspace and project records may blur together
- **Severity:** Medium
- **Likelihood:** Medium
- **Owner or butler:** Project Manager Butler
- **Impact:** Workspace-level decisions, project status, and project-specific tasks could be recorded in the wrong place.
- **Mitigation:** Keep workspace records in `project-office/` and project-level records in `projects/<project-slug>/`.
- **Status:** Open

### R3. Awaiting-Philip decisions could become mixed with general tasks
- **Severity:** Medium
- **Likelihood:** Medium
- **Owner or butler:** Project Manager Butler
- **Impact:** Philip-only decisions may be hidden in status text or backlog items, slowing progress.
- **Mitigation:** Keep `AWAITING_PHILIP.md` files limited to decisions only Philip can make, split by workspace and project scope.
- **Status:** Open

### R4. Premature application work
- **Severity:** High
- **Likelihood:** Low
- **Owner or butler:** Head Butler / Development Butler
- **Impact:** Code or architecture could be created for a product Philip has not requested.
- **Mitigation:** Do not create application code unless Philip later approves a specific application project.
- **Status:** Open

### R5. Sensitive project information could be committed
- **Severity:** High
- **Likelihood:** Medium
- **Owner or butler:** Head Butler / Project Manager Butler
- **Impact:** Private user data, private contact details, credentials, or other sensitive records could enter repository history.
- **Mitigation:** Keep privacy boundaries explicit in workspace and project records, and avoid committing sensitive details.
- **Status:** Open
