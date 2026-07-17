# NT² Community — Product Feedback

Public backlog for **sanitised** bug reports and feature requests for [NT² Vault](https://nt2.me).

| | |
|---|---|
| **Issues** | https://github.com/nt2-community/product-feedback/issues |
| **Discussions** | https://github.com/nt2-community/product-feedback/discussions |
| **Local checkout** | `~/dev/nt2-community/product-feedback/` (sibling of the private `nt2` monorepo) |
| **Community hub** | https://community.nt2.me/ |
| **Discord** | https://discord.gg/K3YmGgwvV |

This repository is **not** a support ticket portal and **not** the private product codebase. Opening an Issue does **not** guarantee roadmap placement or a reply SLA.

## Channel routing

| Situation | Where to go |
|-----------|-------------|
| Reproducible, **non-sensitive** bug | **Open an Issue** here (Bug template) |
| Feature / roadmap idea | Start a **Discussions → Ideas** thread; staff may promote to an Issue |
| Needs auto environment + staff reply | **In-app** Settings → Report a problem (gives a `referenceCode`). You may paste that code on a public Issue **without** pasting secrets |
| Billing / account | `support@nt2.me` |
| Privacy / GDPR | `privacy@nt2.me` |
| Security vulnerability | `security@nt2.me` — see [SECURITY.md](./SECURITY.md) (**do not** open a public Issue for unfixed vulns) |
| Casual chat / quick votes | Discord `#🐞┃bug-reports` / `#💡┃roadmap-feedback` |
| Unreleased beta behaviour | Discord `#🔒┃beta-feedback` only — **not** here |

## Zero-knowledge red lines

**Never** post in Issues or Discussions:

- Master passwords, passphrases, or unlock hints
- Seed phrases / mnemonics, private keys, or recovery kit contents
- `.nt2backup` / `.nt2recovery` / `.nt2share` files
- Full Key DID, full vaultId, or vault item plaintext
- Screenshots that show secrets, account numbers, or personal data

Staff may edit or delete posts that leak sensitive material.

## How feedback becomes product work

```text
Discord discussion  →  GitHub Issue (durable)  →  private executable spec  →  ship  →  close Issue
```

Popular Issues are **signals** only. Shipping still requires a private feature spec in the NT² monorepo. Staff triage labels (`needs-triage` → `confirmed` / `needs-info` / `duplicate` / `planned` / `in-progress` / `shipped` / `wontfix`).

## Voting (v1)

Use GitHub **Reactions** (👍) on Issues and upvotes on Discussions. No third-party voting product.

## Contributing

See [CONTRIBUTING.md](./CONTRIBUTING.md). This repo is **Issues + Discussions first**. Pull requests are not accepted for product code (there is no application source here). Docs-only PRs to README / CONTRIBUTING may be considered; prefer opening an Issue first.

## Related

- End-user Help: https://nt2.me/help
- Contact: https://nt2.me/contact
- In-app / email support policy: private monorepo spec **044** (Dash inbox — environment stays private)
- Decision: public feedback lives here (**DEC-156** / feature **147**)
