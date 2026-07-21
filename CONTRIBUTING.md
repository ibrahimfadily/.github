# Contributing

## Workflow

1. Create a focused branch from the repository's default branch.
2. Keep changes limited to one concern.
3. Run the repository's lint, type-check, test and build commands.
4. Open a pull request with the problem, root cause, implementation and validation steps.
5. Do not commit secrets, environment files, generated builds or local machine artifacts.

## Commit style

Use clear conventional commits where practical:

- eat: new functionality
- ix: bug fix
- docs: documentation
- efactor: internal restructuring
- chore: maintenance
- ci: automation and delivery

Direct production changes and force pushes to protected branches are not accepted.