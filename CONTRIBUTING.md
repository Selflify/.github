# Contributing to Selflify

Thanks for contributing.

## Before opening a pull request

- Keep changes scoped and reviewable.
- Open or reference an issue first for larger features, refactors, or behavior changes.
- Follow any repo-specific instructions if they exist.

## Pull request expectations

- Explain what changed and why.
- Describe how you tested it.
- Include screenshots for UI changes when relevant.
- Avoid mixing unrelated changes in one PR.

## Local quality bar

Run the checks that make sense for the repository you are changing.

For the main `Selflify/Selflify` app repository this usually means:

```bash
yarn workflow:lint
yarn lint
yarn test:run
yarn typecheck
yarn build
```

## Commit style

Short, specific commit messages are preferred. Conventional prefixes such as `feat:`, `fix:`, `docs:`, and `chore:` are welcome but not mandatory unless the repository already uses them.

## Security

Do not open public issues for vulnerabilities. Follow the instructions in `SECURITY.md`.
