# Executable theory specification

## Goal

Translate the conceptual model into a reproducible protocol that can be implemented as a benchmark or experimental harness.

## Minimal state machine

~~~text
BASELINE
   ↓
ASSISTED
   ↓
WITHDRAWAL
   ↓
DELAYED RETENTION
   ↓
TRANSFER
~~~

## Required records

For each participant / agent / task instance:

~~~yaml
subject_id:
task_id:
baseline_score:
assistance_type:
assistance_intensity:
interaction_trace:
verification_actions:
assisted_score:
withdrawal_score:
delay:
delayed_retention_score:
transfer_task_id:
transfer_score:
confidence_assisted:
confidence_unassisted:
boundary_variables:
~~~

## Validation gates

1. assisted and unassisted states are distinguishable
2. task comparability is declared
3. AI contribution is not attributed automatically to the human
4. withdrawal condition is explicit
5. delay is explicit
6. transfer distance is explicit
7. missing data and tool leakage are detectable
8. protocol can be reproduced from versioned artifacts

## Future implementation

This file defines the target interface only. No executable benchmark is claimed to exist yet.
