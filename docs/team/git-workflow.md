# Git workflow

## Main branch
Keep main stable as the team's integration baseline. Do not commit unfinished or unreviewed work directly to it.
## Feature branches
Create short-lived branches from updated main with descriptive names such as feat/observation-history, fix/schema-validation, or docs/offline-flow.
## Pull requests
Keep each PR focused. Explain change, evidence, data implications, and limitations; link issues or ADRs.
## Code review
Request review from the responsible owner. Check correctness, documentation, accessibility, test evidence, privacy, and provenance.
## Conflict resolution
Update from main, resolve with relevant owners, and rerun applicable checks. Do not silently discard others' work.
## Commit messages
Use concise imperative messages with a category, e.g. docs: add source quality template or fix(backend): handle invalid timestamp.