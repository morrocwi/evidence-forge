# Evidence workflow

This project does not invent a new review method. It delegates review discipline to **Glosa LRS** and adds the Evidence Forge **Functional Source Layer Stack** to prevent source-role collapse.

## Two orthogonal questions for every source

Every source interaction must answer both:

1. **What is this source doing?** → L1–L7 source layer.
2. **What does it say to our proposition?** → SUPPORTS / CHALLENGES / EXTENDS / PENDING.

These axes must not be collapsed.

A DOI registry can be excellent at L4 while saying nothing about whether P8 is true.  
A review can be useful at L2 while not being the original source for an attributed construct.  
A primary experiment can bear on P5 at L3 while still failing L7 if the manuscript overstates its result.

## Binding workflow

1. Freeze the paper architecture before searching.
2. Assign the question to relevant **source layers** before selecting databases.
3. Use L1 taxonomy/discovery to establish vocabulary and neighbouring terms.
4. Use L2 conceptual orientation to establish existing distinctions and locate original sources.
5. Run a separate Glosa search episode for each focal proposition / falsifier.
6. Acquire and open L3 primary/original sources.
7. Resolve L4 identity/version/provenance.
8. Run L5 backward/forward citation chaining, including challenge descendants.
9. Run L6 cross-discipline / cross-index coverage audit.
10. Create a source-first citation card with exact passage and locator.
11. Map the source to architecture nodes using only:
    - SUPPORTS
    - CHALLENGES
    - EXTENDS
    - PENDING
12. Record what the source sees **and what it does not see**.
13. Run L7 independent claim-match verification before calling a relation VERIFIED.
14. Preserve null, adverse and contradictory findings.
15. Feed only appropriately verified relations into the claim–evidence matrix.
16. Send revision recommendations back to the preprint; do not let the evidence workspace silently rewrite the conceptual source of record.

## Layered dialogue format

Use `schemas/layered-literature-dialogue-table.md`.

The goal is not:

```text
Paper A says X.
Paper B says Y.
Paper C says Z.
```

The goal is:

```text
Our proposition P
  ↔ field taxonomy (L1)
  ↔ established conceptual distinctions (L2)
  ↔ primary claims/results (L3)
  ↔ resolved identity/version (L4)
  ↔ descendants/challenges (L5)
  ↔ cross-field coverage (L6)
  ↔ exact verified claim match (L7)
```

Then write the synthesis from the pattern of relations, not from source count.

## Review label

Initial mode: **TARGETED_SEARCH / architecture-first comparative review**, not systematic review.

This may change only if the human author deliberately freezes and executes a systematic-review protocol.

## Citation rule

A bibliography entry copied from the preprint is a discovery lead, not verified evidence. The original source must be opened.

## Functional non-collapse

```text
taxonomy ≠ evidence
reference orientation ≠ primary attribution
metadata ≠ validation
citation graph ≠ truth
index inclusion ≠ quality certification
opened source ≠ correctly matched claim
```
