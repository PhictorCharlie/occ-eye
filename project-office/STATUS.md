# OCC-Eye Status

## Current phase
First project-planning cycle. Product discovery and planning are in progress; application implementation has not started.

## What is known
- The project name is OCC-Eye.
- The product purpose, primary users, core workflow, and first-release requirements are not yet defined in the project brief.
- The intended application should be accessible, responsive on mobile and desktop, and have clear visual hierarchy and simple navigation.
- Technical expectations include environment variables for external services, automated tests for core behavior, README setup/development/test/deployment instructions, and passing lint/build/test checks before completion.
- No application code should be created during this planning cycle.

## What is unknown
- What problem OCC-Eye solves.
- Who the primary users are.
- What the central user action is.
- What information users provide.
- What result or output the product produces.
- Whether accounts, storage, uploads, notifications, or integrations are required.
- Which technical stack, hosting target, external services, and data retention model should be used.

## Recommended specialist sequence
1. Product Butler: clarify product direction, target users, MVP boundaries, user stories, and acceptance criteria.
2. Project Manager Butler: convert approved direction into milestones and prioritized backlog.
3. Development Butler: only after Philip approves the product direction and MVP scope.
4. Formatting Butler: after a user-facing interface exists or wireframes are approved.
5. QA Butler: after requirements and implementation are available to verify.

## Work permitted now
- Maintain project-office planning records.
- Propose clearly labeled product interpretations and assumptions.
- Prepare questions and decisions for Philip.
- Draft non-code planning pull requests.

## Work not permitted yet
- Application code, product implementation, integrations, data models, or UI buildout.
- Treating any proposed interpretation as approved requirements.
- Selecting irreversible architecture or external-service dependencies without Philip's approval.

## Proposed product interpretations

### Option 1: Operations Command Center Eye
OCC-Eye could be a monitoring dashboard for an operations command center that helps coordinators see incidents, statuses, alerts, and unresolved actions in one place.

**Possible users:** operations managers, support leads, incident coordinators.

**Possible central action:** review and triage operational events.

**Possible output:** prioritized incident/status view with next actions.

**Assumption label:** This interpretation assumes "OCC" means Operations Command Center.

### Option 2: Optical Character Capture Eye
OCC-Eye could be a document/image review tool that extracts text from images, lets users verify extracted content, and exports structured results.

**Possible users:** administrative teams, analysts, records processors.

**Possible central action:** upload or paste an image/document for text extraction and review.

**Possible output:** verified text and structured fields.

**Assumption label:** This interpretation assumes "OCC" refers to optical character capture or OCR-adjacent work.

### Option 3: Occupancy/Compliance Check Eye
OCC-Eye could be a compliance observation tool that helps users record site checks, occupancy conditions, safety issues, and evidence for follow-up.

**Possible users:** facility managers, compliance inspectors, property operations teams.

**Possible central action:** complete an inspection/checklist and attach observations.

**Possible output:** compliance summary, issue list, and report.

**Assumption label:** This interpretation assumes "OCC" refers to occupancy or operational compliance checks.

## Recommendation, not approval
Recommend Option 1, Operations Command Center Eye, as the provisional direction because the name "Eye" suggests situational awareness and the planning records emphasize coordination, status, risks, and action tracking. This is only a recommendation and must not be treated as approved product scope until Philip confirms it.

## Latest update
- Created initial project-office records for the first planning cycle.
- Captured knowns, unknowns, proposed interpretations, recommendation, risks, backlog, and Philip decisions.
