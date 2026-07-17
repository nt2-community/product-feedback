# Contributing to NT² product feedback

Thank you for helping improve NT² Vault. Please read the [README](./README.md) channel-routing table before opening anything.

## Before you open an Issue

1. **Search** existing [Issues](https://github.com/nt2-community/product-feedback/issues) and [Discussions](https://github.com/nt2-community/product-feedback/discussions).
2. Prefer **Discussions → Ideas** for early brainstorming; open a **Feature** Issue when the ask is concrete.
3. For bugs that need environment details or a staff reply, use **in-app Report a problem** first, then optionally open a public Issue and paste only the **`referenceCode`** (no vault secrets, no full environment dump).

## Bug reports

Use the **Bug** Issue template. Include:

- Platform (PWA / Desktop / iOS / Android)
- App version
- Steps to reproduce
- Expected vs actual

**Do not** attach passwords, mnemonics, private keys, backups, full Key DID / vaultId, or sensitive screenshots.

## Feature requests

Use the **Feature** Issue template (or start in Discussions → Ideas). Explain the user problem, why current UX is insufficient, and any acceptable constraints (e.g. Desktop-only, Premium-only).

## Staff triage (maintainers)

1. New Issues should carry `needs-triage` (add manually if missing).
2. Triage to `confirmed`, `needs-info`, `duplicate`, or `wontfix`.
3. Confirmed work that will ship is planned **internally** by staff — public Issues are **signals**, not the engineering backlog.
4. When shipped, close with an app/version note and label `shipped`.

Opening an Issue does **not** guarantee roadmap placement or an SLA.

## Pull requests

This repository has **no application source**. Product code is not contributed here.

- **Default:** do not open PRs.
- **Docs-only:** small fixes to README / CONTRIBUTING / SECURITY / CODE_OF_CONDUCT may be accepted after an Issue; maintainers may prefer editing directly.

## Code of conduct

See [CODE_OF_CONDUCT.md](./CODE_OF_CONDUCT.md).
