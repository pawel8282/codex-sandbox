# Repository operating rules

## Purpose

This repository is a safe workspace for code prepared with Codex and other development tools.

## Security

- Never commit passwords, private keys, seed phrases, wallet files, recovery codes, API tokens, session cookies, or personal account data.
- Public cryptocurrency addresses may be committed only when they are deliberate test data and are clearly labelled.
- Use environment variables for credentials. Keep real values in a local `.env` file or an approved secret manager.
- Keep `.env.example` limited to variable names and non-sensitive placeholders.
- If a secret is found, stop using it, rotate or revoke it, and remove it from Git history before continuing.
- Never connect a wallet, sign a transaction, transfer funds, or publish account data as part of repository work.

## Changes

- Work on a separate branch.
- Keep commits small and describe their purpose.
- Review the diff before opening or merging a pull request.
- Do not merge to `main` without the repository owner's explicit approval.
- Run available tests, linters, and secret scanning before requesting review.

## Documentation

Document setup steps without real credentials. Examples must use reserved or obviously fake values.
