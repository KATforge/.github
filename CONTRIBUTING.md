# Contributing to KATforge

Follow the [KATforge Engineering Handbook](https://katforge.atlassian.net/wiki/spaces/KAT/pages/393217/Engineering+Workflow).

## Workflow

- Start repository work in a Git worktree on a branch cut from `develop`, named for
  the work, for example `feature/gear-goblins-character-routes`.
- KATforge doesn't use Jira tickets. Keep ticket keys out of branches, commits,
  and pull requests.
- Follow repository-native instructions and run its configured checks.
- Target a complete change, including callers, contracts, migrations, tests,
  generated artifacts, and documentation.

## Commits

Use Conventional Commits:

```text
type(scope): imperative summary

Optional explanation of why the change was necessary.
```

Use `feat`, `fix`, `refactor`, `perf`, `test`, `docs`, `build`, `ci`, `chore`,
or `revert`.

Keep each commit coherent. Do not add AI attribution or co-author trailers.

## Pull requests

- Use the shared pull request template.
- Keep one coherent outcome per pull request.
- Report validation, risk, rollback, and delivery impact, and link any design
  document.
- Resolve review threads and required checks before integration.
- Record the exact delivery state on the pull request. Merged does not mean
  deployed.

See the detailed [Git and Commit Standard](https://katforge.atlassian.net/wiki/spaces/KAT/pages/458753/Git+and+Commit+Standard)
and [Pull Request Standard](https://katforge.atlassian.net/wiki/spaces/KAT/pages/458774/Pull+Request+Standard).
