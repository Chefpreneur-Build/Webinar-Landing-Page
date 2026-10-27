# Repository guidance

## Current state

This repository is named `Webinar-Landing-Page`. It currently contains only a
README with the project title. No application framework, package manager,
dependencies, build commands, or test suite has been established.

## Working in this repository

- Use the existing checkout at `/workspace/Webinar-Landing-Page`. Cloud tasks
  already run in isolated environments; do not create a Git worktree unless the
  user requests one.
- Inspect the repository again before starting work; these initial conditions
  may change as the application is implemented.
- Preserve existing user changes and keep changes focused on the requested task.
- Do not assume a technology stack or claim that build or test commands exist.
  When implementing the application, choose tools appropriate to the user's
  requirements and document the actual setup, development, build, and validation
  commands in the README.
- Once dependencies are introduced, use the selected package manager and commit
  its lockfile. Keep credentials out of source control and document required
  environment variable names without secret values.

## Validation

There are currently no automated checks to run. For future application changes,
run the relevant checks supplied by the project and verify the affected behavior.
Report which checks ran and any limitations; do not describe unrun checks as
passing.
