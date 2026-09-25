# Global Theory Collision — three already stress-tested streams

## Status

This file collides the **latest post-round-2 equations** against established global frameworks.

It does **not** test the earlier versions that were already narrowed or rejected.

The three streams already stress-tested elsewhere in this repository are:

1. temporal feasibility;
2. return route + triggered contact;
3. edge / node / hybrid economics.

The question for each stream is:

[
	ext{What does our formulation explain beyond the nearest established theory?}
]

If the answer is "nothing material", the construct is absorbed into the established framework and retained only as an operational variable or implementation rule.

---

# 1. Temporal feasibility

## Current project equations

The current project no longer uses a natural binary:

[
Urgent quad vs quad NonUrgent
]

as an evidence-based classification.

It uses:

[
d^{feasible}_{i,t}
=
g(
TimeAvailable,
WorkLoad,
CareLoad,
Stress,
Travel,
ProgrammeEffort
)
]

and then:

[
u^{prep}_{i,t}
=
mathcal{P}
(
Need_{i,t},
Risk_{i,t},
d^{feasible}_{i,t}
)
]

with:

[
RapidCore

eq
CompressedFullProgramme
]

This is the current object to test.

## Seminal / established neighbours

### Administrative burden

Moynihan, Herd & Harvey (2015) theorize administrative burden through:

- learning costs;
- psychological costs;
- compliance costs.

DOI: 10.1093/jopart/muu009.

This already explains why formally available support can become difficult to use.

### Cumulative Complexity Model

Shippee et al. (2012) model the relation between:

[
Workload
quad vs quad
Capacity
]

where workload includes demands on time and energy and capacity includes functional, financial, social and literacy resources.

DOI: 10.1016/j.jclinepi.2012.05.005.

This is a very close theoretical neighbour to the project's time/work/care/stress/effort formulation.

### Patient-centred access

Levesque, Harris & Russell (2013) distinguish service-side accessibility and people's abilities to perceive, seek, reach, pay and engage.

DOI: 10.1186/1475-9276-12-18.

Availability/accommodation already includes temporal and organizational fit.

### Life-course approach

WHO's 2025 life-course framework explicitly treats timing, critical periods, transitions, cumulative exposure and continuity across life stages as central to intervention design.

Source: WHO, *Framework to implement a life course approach in practice* (2025), ISBN 978-92-4-011257-5.

## Current review / synthesis

The 2021 scoping review of empirical applications of the Levesque access framework shows that multidimensional access barriers are commonly analyzed through both service characteristics and people's abilities.

The WHO 2025 life-course framework provides a current global synthesis of temporal action, life transitions and continuity.

## Direct evidence already in this repository

Round 2 found:

- time/travel/effort barriers predict participation or retention in relationship education;
- moderate-dose programmes often outperform low-dose programmes;
- brief/flexible programmes can help selected couples;
- very short preparation should not be treated as equivalent to full skill-building.

Therefore the strongest empirical statement is:

[
TemporalFeasibility
ightarrow
Participation/Adherence
]

not:

[
Urgency
ightarrow
ShortProgrammeIsEquivalent
]

## Counterevidence

- brief or flexible programmes can still benefit selected groups;
- high dose does not automatically outperform moderate dose;
- the relationship between time burden and outcomes is not monotonic;
- objective time alone may not explain adherence once broader workload and capacity are included.

## Collision result

### What established theory already explains

Administrative burden + cumulative complexity + access theory already explain almost all of:

[
Time,
Effort,
WorkLoad,
CareLoad,
Stress,
Capacity
ightarrow
Usability/Participation
]

Life-course theory already explains why **timing and transitions** matter.

### What remains useful in our formulation

The project adds a practical **intervention-selection bridge**:

[
TemporalFeasibility
+
Need
+
Risk
ightarrow
InterventionIntensity
]

and makes explicit that:

[
RapidCore

eq
CompressedFullProgramme
]

This is useful as an **operational decision rule**, but it is not yet a new standalone theory.

## Falsifier

If `TemporalFeasibility` adds no predictive or explanatory value beyond established measures of:

- workload;
- capacity;
- availability/accommodation;
- administrative/treatment burden;

then it should be removed as a separate construct and represented as a component of:

[
EffectivePossibility / AccessCapacity
]

## Decision

**ABSORB THEORETICALLY / RETAIN OPERATIONALLY**

Do not claim a new temporal-feasibility theory.

In equation compression, treat time as a dimension of effective possibility or conversion capacity unless direct evidence shows independent explanatory value.

---

# 2. Return route + triggered contact

## Current project equations

The original broad claim:

[
PremaritalContact
ightarrow
PersistentReentry
ightarrow
BetterLaterOutcomes
]

was already rejected as too broad.

The current formulation is:

[
R^{option}_{i,t}=1
]

when a person has a known, usable and safe route back.

Additional contact occurs when:

[
Trigger_{i,t}=1
]

and:

[
Contact_{i,t}
=
R^{option}_{i,t}
	imes
Trigger_{i,t}
]

with separate comparison among:

[
PeriodicCheckup
quad vs quad
TransitionTriggered
quad vs quad
UserInitiated
]

The principle is:

[
DoNotFrontLoadEverything
Rightarrow
PreserveReliableReturnAccess
]

## Seminal / established neighbours

### Continuity of care

Haggerty et al. (2003) distinguish continuity across multiple providers and organizations and identify informational, management and relational dimensions.

DOI: 10.1136/bmj.327.7425.1219.

The central problem—people moving across fragmented services over time—is already well established.

### Continuum of care

WHO/PMNCH work on maternal, newborn and child health explicitly links care across:

[
pre	ext{-}pregnancy
ightarrow
pregnancy
ightarrow
birth
ightarrow
postnatal
ightarrow
childhood
]

as a continuum rather than isolated episodes.

### Life-course continuity

WHO's 2025 life-course framework explicitly includes:

- continuity across life stages;
- critical transitions;
- repeated action across time;
- person-centred service reorientation.

## Current review / synthesis

WHO's 2025 framework states that services should support people through transitions so that people do not fall through gaps between life stages.

The continuity-of-care literature already treats fragmented transitions as a central system problem.

## Direct evidence already in this repository

Round 2 found:

- recurrent Marriage Checkup RCTs produced small-to-moderate benefits on some relationship outcomes;
- Family Foundations and transition-to-parenthood interventions support spanning pre/post transition periods;
- one-time gains can attenuate;
- life transitions can become access windows.

## Counterevidence

- a five-year booster trial did not find significant between-group incremental benefits;
- evidence is stronger for specific transitions than for generic lifelong re-entry;
- repeated contact has cost and burden;
- scheduled follow-up may not be optimal for all groups.

## Collision result

### What established theory already explains

Continuity-of-care and life-course frameworks already explain:

[
OneShotService

eq
ContinuityAcrossTransitions
]

and already justify preserving pathways across time.

### What remains useful in our formulation

The project's useful contribution is **not a new continuity construct**.

It is a low-burden implementation architecture:

[
KnownReturnRoute
+
TriggeredContact
+
OptionalPeriodicCheckup
]

rather than universal continuous follow-up.

This reframes continuity as an **access option** that can remain latent until a relevant trigger occurs.

## Falsifier

If the triggered-return architecture:

- misses high-risk users;
- yields lower appropriate service uptake;
- increases delay;
- costs no less than scheduled follow-up;
- or produces no better continuity than ordinary referral systems;

then the implementation rule should be rejected.

If established continuity measures fully capture `R^{option}` without loss, `return route` should not remain a separate construct.

## Decision

**ABSORB INTO CONTINUITY / LIFE-COURSE THEORY; RETAIN AS IMPLEMENTATION PROPOSITION**

The theoretically compressed variable should likely be something like:

[
Continuity / Reenterability
]

inside effective possibility/access, not a standalone theory object.

---

# 3. Edge / node / hybrid economics

## Current project equations

The earlier rule:

[
AddEdgesBeforeNodes
]

was already rejected.

The current architecture diagnoses:

[
MissingEdge,
MissingNode,
MissingCapacity,
Mixed
]

For service node (j):

[
lambda'_j
=
lambda_j
+
Deltalambda^{edge}_j
]

and:

[
Slack_j
=
mu_j-lambda'_j
]

The action set is:

[
a
in
{
Edge,
Node,
Hybrid
}
]

with choice based on marginal outcome/cost under safety, equity, waiting-time and quality constraints.

## Seminal / established neighbours

### Network governance

Public-service and integrated-care network governance already studies coordination among autonomous organizations rather than assuming a single provider.

### Integrated care service networks

A systematic review of decision-making dilemmas in integrated-care networks identifies recurring tensions such as:

- autonomy vs interdependence;
- diversity vs coherence;
- self-interest vs common goals;
- inclusiveness vs efficiency.

PMCID: PMC9673607.

### Collaborative governance in healthcare networks

A 2024 scoping review reports that healthcare-network performance depends on:

- resource mobilization;
- staff pooling;
- coordination;
- trust;
- shared commitment;
- power sharing;
- information interoperability;
- capacity for joint action.

The review also reports inconsistent evidence for health-outcome improvement.

### Referral / navigation systems

Systematic reviews show that referral redesign and patient navigation can improve access in some settings, while effects and cost-effectiveness vary by pathway and context.

For example:

- structured referral/triage can shorten waiting times in elective surgical pathways;
- single-entry systems can reduce first-assessment waiting times;
- patient navigation often expands access for vulnerable populations.

## Current review / synthesis

The current integrated-care and collaborative-governance literature already treats service networks as combinations of:

- organizations/nodes;
- relationships/coordination/edges;
- resources/capacity;
- governance mechanisms.

Therefore the basic distinction between edge and node is not theoretically new.

## Direct evidence already in this repository

Round 2 found:

- integrated care can be economically favourable in some settings, but heterogeneous;
- navigation can be cost-effective in some cancer pathways;
- navigation is not universally cost-effective across sectors;
- better navigation can reveal latent demand and increase receiving-node load;
- edge-only interventions are insufficient when receiving capacity is saturated.

## Counterevidence

- social prescribing / some navigation models show weak or inconsistent outcomes;
- integration can add coordination burden;
- improved access can increase total service use;
- service capacity can adapt dynamically;
- node/edge categories may blur in real organizations.

## Collision result

### What established theory already explains

Network governance, integrated care and operations/capacity theory already explain:

[
Coordination

eq
ServiceCapacity
]

and:

[
BetterCoordination

otRightarrow
AdequateCapacity
]

They also already support contingent rather than universal integration benefits.

### What remains useful in our formulation

The project's strongest addition is a **diagnostic decision sequence**:

[
Diagnose Bottleneck
ightarrow
{
Edge,
Node,
Capacity,
Mixed
}
ightarrow
Compare Marginal Value
]

This is a compact operational model for a civil-society/family-support ecosystem.

It should not be presented as a new network-governance theory.

## Falsifier

The diagnostic rule fails if:

1. bottleneck classification does not predict which intervention improves outcomes;
2. the Edge/Node/Capacity categories cannot be reliably distinguished;
3. a unified service-deficit measure performs as well or better;
4. reasonable outcome weights change the recommended action so radically that the rule has no stable decision value.

## Decision

**ABSORB INTO NETWORK GOVERNANCE / INTEGRATED CARE / OPERATIONS THEORY; RETAIN THE BOTTLENECK DECISION RULE**

For equation compression, this can likely collapse into:

[
Structure/Capacity
]

plus a bottleneck-selection rule, rather than several core state variables.

---

# 4. Combined result of the three-stream collision

The three streams survive, but **not as three new theories**.

| Stream | Global theory collision | Keep? | Final role |
|---|---|---|---|
| Temporal feasibility | administrative burden + cumulative complexity + access + life course explain most of it | yes, narrowed | operational dimension of effective possibility |
| Return route + triggered contact | continuity of care + continuum/life-course theory explain the core | yes, narrowed | implementation proposition for reenterability/continuity |
| Edge/node/hybrid | network governance + integrated care + operations/capacity explain the theory base | yes, narrowed | bottleneck diagnostic / decision rule |

## Compression implication

These results support moving toward a smaller spine:

[
Structure
ightarrow
EffectivePossibility
ightarrow
Capability
ightarrow
Action
ightarrow
Family/ChildOutcome
]

where:

[
EffectivePossibility
=
f(
Access,
Time,
Safety,
Culture/Meaning,
Capacity
)
]

and where:

- return-route / re-entry belongs under continuity/access;
- temporal feasibility belongs under time + workload/capacity;
- edge/node/hybrid belongs under structure/capacity diagnosis.

This is a **working compression hypothesis**, not yet the final equation.

---

# 5. Coordination with Round 3

Because these three streams already have dedicated Round-2 stress tests and now a global-theory collision, the next evidence attack should **not duplicate them from zero**.

Treat them as anchored streams and focus new Round-3 effort on the remaining weak points:

1. meaning coherence;
2. experienced access;
3. felt safety;
4. culturally embedded entry;
5. tiered support;
6. opportunity cost;
7. transportability.

The three anchored streams should re-enter Round 3 only if new evidence directly challenges the narrowed formulation.

---

# 6. Source notes used for this collision

- Moynihan D, Herd P, Harvey H. Administrative burden: learning, psychological, and compliance costs in citizen-state interactions. *Journal of Public Administration Research and Theory*. 2015;25(1):43–69. DOI: 10.1093/jopart/muu009.
- Shippee ND et al. Cumulative complexity: a functional, patient-centered model of patient complexity can improve research and practice. *Journal of Clinical Epidemiology*. 2012. DOI: 10.1016/j.jclinepi.2012.05.005.
- Levesque JF, Harris MF, Russell G. Patient-centred access to health care: conceptualising access at the interface of health systems and populations. *International Journal for Equity in Health*. 2013;12:18. DOI: 10.1186/1475-9276-12-18.
- Haggerty JL et al. Continuity of care: a multidisciplinary review. *BMJ*. 2003;327:1219–1221. DOI: 10.1136/bmj.327.7425.1219.
- World Health Organization. *Framework to implement a life course approach in practice*. 2025. ISBN 978-92-4-011257-5.
- PMNCH/WHO. *Enable the Continuum of Care*. 2010.
- Decision-Making Dilemmas within Integrated Care Service Networks: A Systematic Literature Review. PMCID: PMC9673607.
- Unravelling collaborative governance dynamics within healthcare networks: a scoping review. *Health Policy and Planning*. 2024.
- Rathnayake D, Clarke M. The effectiveness of different patient referral systems to shorten waiting times for elective surgeries: systematic review. *BMC Health Services Research*. 2021;21:155. DOI: 10.1186/s12913-021-06140-w.
- The role of patient navigators in ambulatory care: overview of systematic reviews. PMID: 34706733.

## Claim ceiling

This is a first collision pass. It establishes a stronger **theory-boundary decision** than a literature count, but it is not yet a full independent Glosa L7 claim-verification pass.
