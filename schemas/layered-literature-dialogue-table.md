# Layered Literature Dialogue Table

Use this with Glosa architecture-first review when the literature base spans several source functions.

## One row = one source × one proposition/node × one role

| Field | Meaning |
|---|---|
| proposition_id | P1–P10 or project claim id |
| node_id | architecture node |
| source_id | stable project source id |
| source_layer | L1–L7 |
| source_function | what this source is being used to do |
| relation | SUPPORTS / CHALLENGES / EXTENDS / PENDING |
| what_source_sees | distinction/mechanism visible in the source's own terms |
| what_source_does_not_see | part of the project architecture outside source scope |
| exact_bearing | exact claim/relation the source may bear |
| boundary_condition | where that bearing stops |
| rival_or_conflict | competing explanation / contrary result |
| next_layer_action | what must be checked next |
| verification_status | DISCOVERED / CANDIDATE / SOURCE_OPENED / CLAIM_MAPPED / INDEPENDENT_CHECK / VERIFIED |

## Example logic

A review article may appear as:

```yaml
source_layer: L2
source_function: conceptual_orientation
relation: EXTENDS
```

The same review's DOI metadata may appear separately as:

```yaml
source_layer: L4
source_function: identity_resolution
relation: PENDING
```

Its citation network may generate:

```yaml
source_layer: L5
source_function: challenge_discovery
relation: PENDING
```

Only an opened source whose exact claim has been independently matched can reach L7 `VERIFIED`.

## Prohibited shortcuts

- L1 category placement → cannot become SUPPORTS by itself.
- L2 reference summary → cannot be cited as the origin of an L3 construct unless it is the original source.
- L4 DOI match → cannot upgrade evidence strength.
- L5 citation count → cannot be converted into weight of truth.
- L6 index inclusion → cannot certify quality.
- L7 verification → verifies claim match, not universal truth.
