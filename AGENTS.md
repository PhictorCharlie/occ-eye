# AGENTS.md

## Project
Philip Butler Workspace

`occ-eye` is a legacy repository name with no confirmed product meaning. Do not infer or assign meanings to OCC-Eye.

## Working rules
- Inspect the repository before changing documentation or code.
- State assumptions clearly when requirements are incomplete.
- Prefer small, understandable components and focused commits.
- Keep workspace documentation clear, accessible, and easy to maintain.
- Add or update tests only for meaningful behavior changes in future approved code projects.
- Run available checks before proposing completion.
- Never commit secrets, tokens, credentials, or private user data.
- Do not commit directly to the default branch for feature work.
- Create a feature branch and prepare a draft pull request.
- Explain major architecture and dependency decisions in the pull request when architecture or dependencies are part of the change.

## Butler operating model
- Read `butlers/HEAD_BUTLER.md` for cross-functional or ambiguous work.
- Use the smallest set of specialist butlers needed for the task.
- Product definition belongs to `PRODUCT_BUTLER.md` only when Philip defines a product or application idea.
- Delivery tracking belongs to `PROJECT_MANAGER_BUTLER.md`.
- Application implementation belongs to `DEVELOPMENT_BUTLER.md` only after Philip approves a code-producing project.
- Visual presentation belongs to `FORMATTING_BUTLER.md`.
- Verification belongs to `QA_BUTLER.md`.
- Keep `project-office/STATUS.md`, `BACKLOG.md`, `DECISIONS.md`, `RISKS.md`, and `AWAITING_PHILIP.md` current when relevant.
- Do not combine unrelated product, implementation, visual redesign, and QA work into one uncontrolled change.
- Move completed or retired work to `project-office/ARCHIVE.md` rather than deleting its history.

## Initial task behavior
Begin by clarifying the workspace purpose from `PROJECT_BRIEF.md`. If details are missing, create clearly labeled assumptions and questions for Philip rather than silently inventing product requirements.
