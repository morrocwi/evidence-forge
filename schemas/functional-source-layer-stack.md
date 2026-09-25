# Functional Source Layer Stack

A literature review becomes stronger when source systems are separated by **function** rather than treated as interchangeable evidence.

This is a reusable Evidence Forge schema. It does not replace Glosa LRS; it adds a source-function map inside the review.

## Principle

```text
taxonomy / discovery
        ≠
conceptual reference
        ≠
primary source
        ≠
identity / metadata
        ≠
citation / knowledge graph
        ≠
index / validation surface
        ≠
claim-level verification
```

No layer is a universal authority over the others. Each answers a different question.

## Layers

### L1 — Taxonomy / disciplinary discovery

**Question:** What does the field call this object, and where does the field classify it?

Typical systems:
- disciplinary bibliographies
- subject taxonomies
- field-specific indexes
- controlled vocabularies

**Can do**
- discover canonical terms
- expose neighbouring concepts
- improve search vocabulary
- reveal disciplinary placement

**Cannot do**
- establish that a substantive claim is true
- replace reading the source

---

### L2 — Conceptual reference / field orientation

**Question:** How is the concept normally defined, distinguished and situated?

Typical systems:
- scholarly encyclopedias
- handbooks
- authoritative review essays
- field consensus/reference works

**Can do**
- orient constructs
- identify major debates
- expose standard distinctions
- locate seminal primary sources

**Cannot do**
- automatically establish empirical effects
- substitute for the original source when attributing an idea

---

### L3 — Primary / original scholarly source

**Question:** What did the author/study actually argue, define, observe or test?

Includes:
- original theory papers
- empirical studies
- primary historical texts
- original methodological papers
- official primary documents where relevant

**Can do**
- support direct attribution
- provide claim-level evidence
- reveal actual scope, population, method and limitations

**Cannot do**
- prove field-wide consensus by itself

---

### L4 — Identity / metadata / provenance

**Question:** Is this the correct scholarly object and version?

Typical systems:
- DOI registries
- author identifiers
- publication metadata registries
- repository/version records

**Can do**
- disambiguate titles/authors
- resolve DOI/version/date
- detect duplicate or revised records
- support provenance

**Cannot do**
- validate the content of the claim

---

### L5 — Citation / knowledge graph

**Question:** How is this work connected to other works, authors, institutions and topics?

Typical systems:
- open scholarly graphs
- citation networks
- author/institution/topic graphs

**Can do**
- forward/backward expansion
- find clusters and bridge papers
- identify later critiques, replications and descendants
- support citation chaining

**Cannot do**
- make a highly cited claim true
- replace direct reading

---

### L6 — Index / bibliometric corroboration

**Question:** Is the work visible in major scholarly indexing/citation systems, and what bibliometric context surrounds it?

Typical systems:
- major citation indexes
- field-specific indexing services
- institutional discovery systems

**Can do**
- corroborate publication/index status
- help audit coverage
- identify citation contexts and related literature

**Cannot do**
- confer truth, quality or correctness on a claim merely by inclusion

---

### L7 — Claim-level verification

**Question:** Does the opened source actually support the exact sentence we want to write?

Evidence Forge delegates this to **Glosa citation-card / independent-check discipline**.

Required:
- source actually opened
- exact passage or precise locator
- scope/population/context recorded
- what the source supports
- what it does not support
- contradictory evidence retained
- independent claim-match check before VERIFIED status

This is the layer that authorizes a source to bear on a manuscript claim.

## Cross-layer rule

A central claim should normally have a trace such as:

```text
L1 discover vocabulary
 ↓
L2 orient the concept
 ↓
L3 open primary source
 ↓
L4 verify identity/version
 ↓
L5 expand to descendants/challenges
 ↓
L6 audit coverage/index context
 ↓
L7 verify exact claim match
```

Not every claim requires every layer, but missing layers must be visible rather than silently assumed.

## Non-collapse rules

- taxonomy hit ≠ evidence
- encyclopedia definition ≠ empirical result
- DOI resolution ≠ claim validation
- citation count ≠ truth
- index inclusion ≠ quality certification
- graph proximity ≠ conceptual equivalence
- review summary ≠ original-source attribution
- source opened ≠ claim correctly matched
