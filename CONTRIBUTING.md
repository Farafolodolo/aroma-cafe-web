# Contributing to Aroma Café Web

## Branches
- `main`: stable production code.
- `develop`: integration branch.
- `feature/<name>`: new features, created from `develop`, merged back via Pull Request.
- `hotfix/<name>`: urgent fixes, created from `main`, merged into `main` **and** `develop`.

Remote `feature/*` and `hotfix/*` branches are never deleted.

## Commit convention
Use conventional commits: `feat:`, `fix:`, `style:`, `docs:`, `chore:`.

## Pull Request checklist
- [ ] Base branch is correct (`develop` for features, `main` for hotfixes/releases)
- [ ] Commits follow the convention
- [ ] Pages open correctly in the browser
- [ ] No unrelated changes included
- [ ] Description explains what and why
