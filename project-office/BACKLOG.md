# OCC-Eye Backlog

## Planning tasks

### 1. Confirm product interpretation
- **Purpose:** Select the intended meaning and problem space for OCC-Eye before implementation.
- **Owner or butler:** Product Butler / Philip
- **Status:** Blocked by Philip decision
- **Priority:** Critical
- **Dependencies:** Philip selects or revises product direction.
- **Acceptance criteria:** A single product statement, target user, primary problem, and central workflow are approved and recorded in DECISIONS.md.
- **Next action:** Philip answers the product-direction decision in AWAITING_PHILIP.md.

### 2. Define MVP boundaries
- **Purpose:** Prevent uncontrolled scope by defining what belongs in the first release.
- **Owner or butler:** Product Butler
- **Status:** Not started
- **Priority:** Critical
- **Dependencies:** Confirmed product interpretation.
- **Acceptance criteria:** MVP features, explicit non-goals, acceptance criteria, and measurable outcome are documented.
- **Next action:** Start after product interpretation is approved.

### 3. Identify data and privacy requirements
- **Purpose:** Determine whether OCC-Eye handles sensitive user, operational, document, location, or compliance data.
- **Owner or butler:** Product Butler / Development Butler
- **Status:** Not started
- **Priority:** High
- **Dependencies:** Confirmed product workflow and user-provided information.
- **Acceptance criteria:** Data inputs, storage needs, retention expectations, export needs, and privacy constraints are documented.
- **Next action:** Ask Philip what data users provide and whether it may be stored.

### 4. Select technical approach
- **Purpose:** Choose a stack and architecture only after product needs are understood.
- **Owner or butler:** Development Butler
- **Status:** Not started
- **Priority:** Medium
- **Dependencies:** Approved MVP boundaries and data requirements.
- **Acceptance criteria:** Architecture proposal includes framework, persistence, testing, deployment, and external-service decisions with tradeoffs.
- **Next action:** Defer until product direction and MVP are approved.

### 5. Draft README requirements outline
- **Purpose:** Prepare documentation structure required by the project brief.
- **Owner or butler:** Project Manager Butler / Development Butler
- **Status:** Not started
- **Priority:** Medium
- **Dependencies:** Technical approach.
- **Acceptance criteria:** README includes setup, development, test, and deployment sections once implementation begins.
- **Next action:** Defer until stack selection.

### 6. Establish verification plan
- **Purpose:** Ensure future work can be tested against approved requirements.
- **Owner or butler:** QA Butler
- **Status:** Not started
- **Priority:** Medium
- **Dependencies:** Approved user stories and acceptance criteria.
- **Acceptance criteria:** Test plan maps primary workflows and edge cases to acceptance criteria.
- **Next action:** Defer until MVP acceptance criteria exist.
