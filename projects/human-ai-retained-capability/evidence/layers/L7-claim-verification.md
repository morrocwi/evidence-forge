# L7 — Claim-level verification

## Purpose

Decide whether an opened source can legitimately bear the exact manuscript claim.

This layer is governed by Glosa source-first citation and independent-check rules.

## Verification object

For each proposition/source pair:

| Field | Requirement |
|---|---|
| proposition_id | P1–P10 |
| source_id | stable project id |
| source opened | yes |
| exact passage / locator | required |
| source scope | recorded |
| manuscript claim | exact sentence or proposition |
| supports | explicit |
| does not support | explicit |
| relation | SUPPORTS / CHALLENGES / EXTENDS |
| contradictory source | recorded where relevant |
| identity/version | resolved |
| independent claim-match | pass required for VERIFIED |

## Status ladder

```text
DISCOVERED
→ CANDIDATE
→ SOURCE_OPENED
→ CLAIM_MAPPED
→ INDEPENDENT_CHECK
→ VERIFIED
```

Any failed step remains visible. Do not collapse "not checked" into "checked and found nothing."
