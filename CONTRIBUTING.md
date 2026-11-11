# Contributing to VITALIS

## Team workflow

Start from the latest main branch, keep changes focused, and coordinate ownership through docs/team/roles-and-ownership.md. Agree on shared field names, types, units, timestamps, and validation in contracts/ before integration. Record material architecture choices as ADRs.

## Branch naming

Use short descriptive branches: feat/frontend-observation-list, fix/api-validation-error, docs/offline-sync-design, or test/analytics-data-quality. Avoid direct commits to main.

## Pull requests

1. Update your branch from main.
2. Make a focused change and include relevant documentation.
3. Review for secrets, credentials, personal health information, and dataset permissions.
4. Open a pull request describing purpose, scope, evidence, limitations, and follow-up decisions.
5. Request review from the relevant owner and resolve comments.
6. Merge only after required review and checks pass.

Keep main stable as a dependable integration point.

## Commit messages

Use concise imperative subjects with a category. Examples: docs: add offline architecture outline; feat(frontend): add observation view; fix(api): clarify validation response; test(analytics): cover missing timestamps.

## Protect sensitive information

Never commit passwords, API keys, tokens, private health information, or identifiable records. Use local environment files excluded by .gitignore, and share only approved, documented datasets. Report accidental exposure to maintainers and follow the incident process; deleting a visible copy alone may not remove it from history.