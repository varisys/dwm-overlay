# Security Policy

## Scope

This repository is a documentation-only showcase. It does not distribute source code, binaries, loaders, symbols, memory signatures, or credentials.

## Reporting a problem

Open a private GitHub security advisory for accidental disclosure, unsafe documentation, or a credential found in repository history. Do not paste a secret into a public issue.

Public issues are appropriate for documentation typos and non-sensitive compatibility observations.

## Credential hygiene

- Never embed API keys, webhook URLs, tokens, or account identifiers in source code.
- Load development secrets from environment variables or an ignored local secret store.
- Treat any credential committed to a file—even briefly—as compromised.
- Revoke the credential first, then remove it from the current tree and repository history.
- Do not publish debug logs or screenshots until they have been reviewed for secrets and personal data.

## Supported content

Security reports requesting binaries, source code, loading instructions, capture-policy bypasses, or target-specific modifications are out of scope and will be closed.

