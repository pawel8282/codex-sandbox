# Security policy

## Reporting a vulnerability

Do not publish passwords, tokens, private keys, seed phrases, wallet files, recovery codes, or personal data in an issue, pull request, commit, or discussion.

Report security problems privately through GitHub's **Report a vulnerability** / private vulnerability reporting feature when it is available for this repository. If private reporting is unavailable, contact the repository owner through a private channel before sharing technical details.

Include:

- a short description of the problem;
- the affected file, component, or commit;
- safe reproduction steps with secrets removed;
- the likely impact;
- a suggested remediation, if known.

## Exposed credentials

Treat any credential committed to Git as compromised, even if it is later deleted. Immediately:

1. revoke or rotate it at its provider;
2. check related account activity;
3. replace it with an environment variable or secret-manager reference;
4. remove it from current files and, when necessary, rewrite Git history;
5. run a secret scan before resuming work.

Never use repository work to connect wallets, sign transactions, or transfer funds.
