# AGENTS.md

## Project
OCC-Eye

## Working rules
- Inspect the repository before changing code.
- State assumptions clearly when requirements are incomplete.
- Prefer small, understandable components and focused commits.
- Keep the application accessible and responsive.
- Add or update tests for meaningful behavior changes.
- Run available tests, linting, and build checks before proposing completion.
- Never commit secrets, tokens, credentials, or private user data.
- Do not commit directly to the default branch for feature work.
- Create a feature branch and prepare a draft pull request.
- Explain major architecture and dependency decisions in the pull request.

## Butler operating model
- Read `butlers/HEAD_BUTLER.md` for cross-functional or ambiguous work.
- Use the smallest set of specialist butlers needed for the task.
- Product definition belongs to `PRODUCT_BUTLER.md`.
- Delivery tracking belongs to `PROJECT_MANAGER_BUTLER.md`.
- Application implementation belongs to `DEVELOPMENT_BUTLER.md`.
- Visual presentation belongs to `FORMATTING_BUTLER.md`.
- Verification belongs to `QA_BUTLER.md`.
- Keep `project-office/STATUS.md`, `BACKLOG.md`, `DECISIONS.md`, `RISKS.md`, and `AWAITING_PHILIP.md` current when relevant.
- Do not combine unrelated product, implementation, visual redesign, and QA work into one uncontrolled change.
- Move completed or retired work to `project-office/ARCHIVE.md` rather than deleting its history.

## Initial task behavior
Because this repository is newly initialized, begin by clarifying the product purpose from `PROJECT_BRIEF.md`. If details are missing, create a proposed architecture and clearly label assumptions rather than silently inventing requirements.
