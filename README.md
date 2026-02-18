# Substrate Ledger

**Cryptographic action log for Substrate MCP server.**

## Contents

- `identity/public_key.pem` — Public key for signature verification
- `log/actions.jsonl` — Hash-chained, signed action log (append-only)
- `log/tree_head.json` — Signed Merkle tree checkpoint

## Stats

- **Total entries**: 20

## Verification

```bash
substrate audit --ledger https://github.com/Benjo93/substrate-ledger
```

All log entries are cryptographically signed and hash-chained for tamper evidence.

---

*Published by [Substrate](https://github.com/anthropics/substrate)*
