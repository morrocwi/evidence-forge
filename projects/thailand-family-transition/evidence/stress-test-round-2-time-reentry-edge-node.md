# Stress test round 2 — time horizon, post-marriage re-entry, and edge-vs-node economics

## Purpose

This round attacks the three weakest parts of the working architecture:

1. whether short versus long preparation time justifies different premarital pathways;
2. whether a route back after marriage has evidence beyond being intuitively attractive;
3. whether strengthening connections between existing services is economically preferable to adding new service capacity.

The goal is not to rescue the architecture. Claims are narrowed where evidence is weaker than the original wording.

---

# 1. Preparation time: urgent versus non-urgent

## 1.1 What direct evidence exists?

Direct evidence comparing **urgent marriage preparation** with **non-urgent marriage preparation** as two explicitly defined premarital pathways was not identified in this search round.

Therefore the binary distinction:

\[
Urgent \quad vs \quad NonUrgent
\]

should not be presented as an established evidence-based classification.

The better-supported variable is **time feasibility / temporal fit**.

Let:

\[
h_{i,t}
=
\text{time realistically available for preparation}
\]

and:

\[
b^{time}_{i,t}
=
\text{time/scheduling burden}
\]

The evidence supports treating time and effort as participation/adherence constraints.

---

## 1.2 Dose evidence challenges an overly optimistic rapid pathway

### Hawkins et al. programmatic-moderator meta-analysis

A meta-analysis coded 148 marriage/relationship-education evaluation reports.

Main dose finding:

- low dose: 1–8 contact hours;
- moderate dose: 9–20 contact hours;
- high dose: 21+ contact hours.

Moderate-dose programmes were associated with stronger effects than low-dose programmes. In controlled studies, high dose did not clearly outperform moderate dose.

### Implication

A very short pathway should **not** be assumed to produce the same communication or relationship-quality effects as a fuller programme.

Therefore:

\[
RapidCore
\neq
CompressedFullProgramme
\]

and:

\[
OutcomeTarget_{rapid}
\neq
OutcomeTarget_{deeper}
\]

The rapid core should be evaluated mainly for:

- essential orientation;
- safety/private-access literacy;
- reproductive/preconception navigation;
- recognition of red flags;
- knowing where and how to return.

A deeper programme can be evaluated for:

- communication skill;
- conflict-management skill;
- expectation alignment;
- relationship self-regulation;
- deeper parenting/finance/family modules.

---

## 1.3 Brief/flexible interventions can still have value

### Halford et al. 2015

A randomized trial of 182 couples tested flexible relationship education.

Couples with low initial relationship satisfaction receiving the flexible skill-based programme showed a moderate immediate improvement in satisfaction relative to control (\(d=0.50\)). Couples with high initial satisfaction showed little change.

### Four-year follow-up

The same trial later found that benefits for low-satisfaction couples attenuated between approximately 6 and 12 months, with no mental-health effects.

### Implication

Brief/flexible delivery can be useful for some groups, but:

\[
Brief
\neq
EquivalentToFullDose
\]

and:

\[
ImmediateEffect
\neq
MaintainedEffect
\]

---

## 1.4 Time and effort predict participation/adherence

Relationship-education implementation studies report that:

- perceived time/travel barriers predict non-participation in family-skills education;
- greater programme effort predicts lower completion;
- web-based relationship-education adherence is lower when participants report time constraints, work/school interference, external stress, or that treatment feels too demanding;
- virtual participants still report scheduling and pacing as important barriers.

### Implication

The strongest defensible statement is:

\[
TemporalFeasibility
\rightarrow
Participation/Adherence
\]

rather than:

\[
UrgentMarriage
\rightarrow
ShortCourseIsEquallyEffective
\]

---

## 1.5 Revised formulation

Use a continuous variable first:

\[
d^{feasible}_{i,t}
=
g(
h_{i,t},
b^{time}_{i,t},
stress_{i,t},
careload_{i,t},
work_{i,t}
)
\]

Then select intervention intensity:

\[
u^{prep}_{i,t}
=
\mathcal{P}
(
Need_{i,t},
Risk_{i,t},
d^{feasible}_{i,t}
)
\]

Two practical bands may still be useful operationally:

### Short-horizon band

Goal:

\[
Orientation + Safety + Navigation + ReturnRoute
\]

### Longer-horizon band

Goal:

\[
Core
+
SkillsPractice
+
DeeperModules
+
OptionalCounselling
\]

The bands are service-design conveniences, not biological or theoretical categories.

---

## 1.6 Current verdict

**Direct evidence for the binary urgent/non-urgent model: weak.**

**Evidence that time/effort constraints affect participation: moderate-to-strong.**

**Evidence that moderate MRE dose often outperforms low dose: moderate.**

**Evidence that brief/flexible programmes can help some couples: moderate.**

### Keep

- temporal fit;
- flexible intensity;
- minimum rapid orientation;
- later return route.

### Remove/avoid

- claim that rapid and planned pathways are equally effective;
- claim that a rapid pathway can substitute for a deeper skill-building programme.

---

# 2. Re-entry after marriage

## 2.1 The original claim was too broad

Original intuition:

\[
PremaritalContact
\rightarrow
PersistentReentry
\rightarrow
BetterLaterOutcomes
\]

Direct evidence for this exact generic chain is still incomplete.

However, three stronger evidence families now exist:

1. recurrent relationship checkups;
2. support spanning important life transitions;
3. evidence that one-time relationship-education effects can attenuate.

---

## 2.2 Recurrent relationship checkups: direct experimental evidence

### Marriage Checkup RCT — 215 couples

Couples were randomized to treatment or waitlist.

Treatment couples received:

- an assessment/feedback checkup near baseline;
- another checkup one year later.

Across two years, treatment showed small-to-moderate improvements in intimacy, acceptance and relationship distress compared with control.

This directly supports the feasibility and potential value of:

\[
BriefContact_t
+
BriefContact_{t+1}
\]

rather than a one-time endpoint.

### Private-practice RCT — 233 couples in Denmark

Couples received two checkups across 54 weeks.

After the second checkup, small-to-medium effects were found across four relationship-health measures.

### Five-year booster study

A subsample of 63 responder couples was randomized to a third checkup or control at year 5.

There were **no significant between-group effects** after randomization, although within-group improvements appeared in the booster group.

This is an important counterweight:

\[
RecurrentContact
\neq
GuaranteedIncrementalBenefit
\]

---

## 2.3 One-time effects can attenuate

The four-year follow-up of flexible relationship education found that gains in low-satisfaction couples dissipated between about 6 and 12 months.

This supports a maintenance problem:

\[
InitialGain_t
\not\Rightarrow
MaintainedGain_{t+k}
\]

but does not prove what maintenance schedule is optimal.

---

## 2.4 Support across a life transition has stronger evidence than generic indefinite re-entry

### Family Foundations

The original trial used:

- four prenatal sessions;
- four postnatal sessions.

A randomized sample of 169 couples showed effects on coparenting, parental mental health, parent–child relations and infant regulation.

Follow-up found effects on parenting, coparenting and child outcomes.

A larger replication with 399 couples used a nine-session programme with prenatal and postnatal components and found broad effects across coparenting, parent mental health, parenting, child adjustment and family violence measures.

### Meta-analysis of 21 controlled transition-to-parenthood interventions

Average effects were:

- small for communication;
- small for psychological well-being;
- very small for couple adjustment.

Stronger effects occurred when interventions:

- had more than five sessions;
- included both antenatal and postnatal components;
- were professionally led.

### Implication

Evidence is stronger for:

\[
SupportBeforeTransition
+
SupportAfterTransition
\]

than for a vague promise of lifelong always-on re-entry.

---

## 2.5 Transition points can be access opportunities

A study of couple relationship education at transition to parenthood found:

- 53% of eligible couples approached participated;
- 80% of participants had not previously accessed relationship education;
- roughly one-third had three or more risk factors;
- low education predicted dropout.

This supports the idea that **life transitions can open new access windows**, but also that reach is unequal.

---

## 2.6 Revised re-entry formulation

Replace “persistent re-entry” as a presumed continuous service with:

## **persistent access option + transition-triggered re-contact**

Let:

\[
R^{option}_{i,t}=1
\]

mean the person retains a known, usable route back.

Actual additional contact occurs when:

\[
Trigger_{i,t}=1
\]

where triggers may be:

\[
\{
user\ request,\,
pregnancy,\,
birth,\,
parenting\ transition,\,
fertility\ difficulty,\,
relationship\ distress,\,
mental\ health,\,
safety\ concern
\}
\]

Then:

\[
Contact_{i,t}
=
R^{option}_{i,t}
\times
Trigger_{i,t}
\]

This is potentially cheaper than continuous universal follow-up.

Optional scheduled checkups can be tested separately:

\[
Checkup_{annual}
\quad vs \quad
TransitionTriggered
\quad vs \quad
UserInitiated
\]

---

## 2.7 Current verdict

**Evidence for repeated brief relationship checkups: moderate.**

**Evidence for interventions that span pre/post major family transitions: moderate-to-strong.**

**Evidence that one-time gains can attenuate: moderate.**

**Evidence that an always-open re-entry architecture improves broad family outcomes: still open.**

### Keep

- a route back;
- transition-triggered support;
- optional periodic checkups;
- re-entry as an access property.

### Narrow

Do not claim:

\[
Reentry
\Rightarrow
BetterFamilyOutcome
\]

without specifying the type, timing, population and intervention.

---

# 3. Economics of Missing Edge versus Missing Node

## 3.1 Original rule was too simple

Original intuition:

\[
C(AddEdge)
<
C(AddNode)
\]

and:

\[
AddEdgesBeforeNodes
\]

This cannot be treated as a general economic law.

The evidence is domain-dependent.

---

## 3.2 Integrated care can improve outcomes and sometimes lower costs

A systematic review/meta-analysis of 34 economic evaluations of integrated care found, overall:

- cost ratio approximately 0.94 compared with control;
- outcome ratio approximately 1.06;
- larger cost and outcome effects in studies with follow-up longer than 12 months.

However:

- study quality was moderate;
- heterogeneity was substantial;
- models differed widely.

Thus:

\[
Integration
\not\Rightarrow
AutomaticSavings
\]

but integration can be economically favourable in some settings.

---

## 3.3 Navigation can be cost-effective in some domains

### Cancer patient navigation

A 2019 systematic review identified 113 studies, including 14 cost/cost-effectiveness studies.

Among 10 cost-effectiveness analyses:

- 8 found navigation cost-effective;
- 2 did not.

However, 11 of 14 economic studies were rated weak quality.

A 2023 overview of 61 systematic reviews concluded that navigation improves screening participation and reduces delays from screening to diagnosis and diagnosis to treatment; US economic evaluations suggest potential cost-effectiveness in screening.

### Colorectal cancer economic review

Eight of nine included economic evaluations concluded that navigation was cost-effective for the outcomes studied.

### Important boundary

These findings are strongest in defined care pathways such as screening and diagnosis.

They cannot be generalized automatically to a whole family-support ecosystem.

---

## 3.4 Navigation is not reliably cost-effective across domains

### Social prescribing link workers

A systematic review found:

- eight controlled studies;
- low or very low certainty;
- no consistent HRQoL or mental-health benefit;
- no cost-effectiveness analyses identified.

### Stroke patient navigation

A systematic review found only two eligible economic studies:

- one suggested a 90% probability of cost-effectiveness at a stated threshold;
- one found similar QALYs at higher cost.

No general conclusion was possible.

Therefore:

\[
Navigation
\neq
UniversallyCostEffective
\]

---

## 3.5 Better edges can increase service use

This is not a failure if unmet need was previously hidden.

A large 2026 English social-prescribing matched cohort found that referred patients had approximately 24% more primary/secondary-care contacts in the first six months. By one year, the increase was much smaller and GP appointments were slightly lower. Total healthcare costs were less than 0.1% higher.

A large US mental-health navigation cohort found navigation associated with much higher conversion to therapy and more treatment sessions.

Thus:

\[
BetterAccess
\rightarrow
DemandRevealed
\]

and potentially:

\[
BetterEdge
\rightarrow
HigherNodeLoad
\]

This is central.

A navigation system can be effective at access while increasing downstream capacity pressure.

---

## 3.6 Capacity must enter the equation explicitly

For service node \(j\):

Let:

- \(\lambda_j\) = baseline incoming demand;
- \(\Delta\lambda^{edge}_j\) = demand newly reaching the node after better navigation/referral;
- \(\mu_j\) = usable service capacity.

Then:

\[
\lambda'_j
=
\lambda_j
+
\Delta\lambda^{edge}_j
\]

Define capacity slack:

\[
Slack_j
=
\mu_j-\lambda'_j
\]

### Case A — edge bottleneck with spare capacity

If:

\[
Slack_j > 0
\]

and failed access is mainly caused by search/referral/coordination barriers, edge investment is plausible.

### Case B — node bottleneck

If:

\[
Slack_j \le 0
\]

then improving the edge without expanding capacity can increase:

- queues;
- waiting time;
- frustration;
- unmet demand after referral.

In this state:

\[
EdgeOnly
\]

is insufficient.

### Case C — mixed bottleneck

Many real systems require:

\[
Edge + Capacity
\]

together.

---

## 3.7 Urgency and capacity interact

Operations-research work on integrated appointment systems shows that first-come-first-served allocation can produce long delays for urgent patients and that reserving capacity by urgency can improve access-delay targets.

This is not marriage-preparation evidence, but it supports a general systems rule:

\[
Urgency
\]

should affect scarce-capacity allocation when delay itself has consequences.

For family-support services, urgency may include:

- immediate safety risk;
- acute mental-health risk;
- time-sensitive reproductive/clinical need;
- imminent marriage with minimum information/safety needs.

---

## 3.8 Replace “edge first” with a bottleneck decision rule

For any proposed civil-society investment \(a\):

\[
a
\in
\{
Edge,\,
Node,\,
Hybrid
\}
\]

Choose:

\[
a^{*}
=
\arg\max_a
\frac{\Delta Y(a)}{\Delta C(a)}
\]

subject to:

\[
Safety\ge s^{*}
\]

\[
Equity\ge e^{*}
\]

\[
Wait_j\le W^{*}_j
\]

\[
Quality_j\ge q^{*}_j
\]

and capacity feasibility.

The decision sequence becomes:

### Step 1 — Is the service itself missing?

If yes:

\[
MissingNode
\]

### Step 2 — Does the service exist but people fail to find/reach/complete it?

If yes:

\[
MissingEdge
\]

### Step 3 — If the edge improves, can the node absorb revealed demand?

If no:

\[
MissingEdge + MissingCapacity
\]

### Step 4 — Compare marginal value

\[
MCE_{edge}
=
\frac{\Delta Outcome_{edge}}{\Delta Cost_{edge}}
\]

\[
MCE_{node}
=
\frac{\Delta Outcome_{node}}{\Delta Cost_{node}}
\]

\[
MCE_{hybrid}
=
\frac{\Delta Outcome_{hybrid}}{\Delta Cost_{hybrid}}
\]

Do not assume the winner before measuring.

---

# 4. Three major revisions after round 2

## Revision A — from binary urgency to temporal feasibility

Before:

\[
Urgent
vs
NonUrgent
\]

After:

\[
TemporalFeasibility
=
f(
TimeAvailable,
Work,
CareLoad,
Stress,
EffortBurden
)
\]

with two operational bands only where useful.

---

## Revision B — from generic persistent re-entry to access option + triggered contact

Before:

\[
PersistentReentry
\]

After:

\[
KnownReturnRoute
+
TransitionTriggeredContact
+
OptionalPeriodicCheckup
\]

This is better aligned with recurrent-checkup and transition-to-parenthood evidence.

---

## Revision C — from “edges before nodes” to capacity-aware bottleneck diagnosis

Before:

\[
AddEdgesBeforeNodes
\]

After:

\[
Diagnose
\{
MissingEdge,\,
MissingNode,\,
MissingCapacity,\,
Mixed
\}
\]

then compare marginal cost-effectiveness.

---

# 5. Updated confidence

| Claim | Confidence after round 2 |
|---|---|
| time/effort burden affects participation | moderate-to-high |
| moderate MRE dose can outperform low dose | moderate |
| brief/flexible RE can help selected couples | moderate |
| short rapid preparation equals deeper preparation | **not supported** |
| recurrent relationship checkups can improve some outcomes | moderate |
| pre/post-transition family intervention can improve parent/child outcomes | moderate-to-strong |
| generic lifelong re-entry improves outcomes | open |
| integrated care can reduce cost and improve outcomes in some systems | moderate |
| navigation can be cost-effective in defined cancer pathways | moderate |
| navigation is cost-effective across sectors | **not supported** |
| better navigation can reveal/increase demand | moderate-to-strong |
| edge-only intervention works despite capacity shortage | **not supported** |
| capacity-aware edge/node/hybrid diagnosis | analytically strong; direct family-system testing still required |

---

# 6. Sources added in this round

## Preparation time / relationship education

- Hawkins AJ et al. *Exploring Programmatic Moderators of the Effectiveness of Marriage and Relationship Education Programs: A Meta-Analytic Study*. Behavior Therapy. 2012.
- Halford WK et al. *Immediate Effect of Couple Relationship Education on Low-Satisfaction Couples*. Behavior Therapy. 2015.
- Halford WK et al. *Four year effects of couple relationship education on low and high satisfaction couples*. Journal of Consulting and Clinical Psychology. 2017.
- Busby DM et al. *Flexible Delivery Approaches to Couple Relationship Education: Predictors of Initial Engagement and Retention of Couples*. 2014.
- Heyman RE et al. *Predicting Program Retention in a Flexibly-Delivered Relationship Education Program for Low-Income, Unmarried Parents*. 2020/2021.
- Megale A et al. *How Effective is Online Couple Relationship Education?* 2022.
- Turner JJ et al. *Couple Relationship Education: Before and During COVID-19*. 2022.

## Recurrent / transition-spanning support

- Cordova JV et al. *The Marriage Checkup: A Randomized Controlled Trial of Annual Relationship Health Checkups*. 2014.
- Trillingsgaard T et al. *A randomized controlled trial of the Marriage Checkup adapted for private practice*. 2016.
- Leth-Nissen AB et al. *A randomized controlled trial of a 5-year marriage checkup booster session*. 2023.
- Feinberg ME, Kan ML. *Establishing Family Foundations*. 2008.
- Feinberg ME et al. *Couple-Focused Prevention at the Transition to Parenthood, a Randomized Trial*. 2016.
- Pinquart M, Teubert D. *A Meta-analytic Study of Couple Interventions During the Transition to Parenthood*. 2010.
- Petch J et al. *Couple relationship education at the transition to parenthood: a window of opportunity to reach high-risk couples*. 2012.

## Edge / node economics

- Rocks S et al. *Cost and effects of integrated care: a systematic literature review and meta-analysis*. European Journal of Health Economics. 2020.
- Bernardo BM et al. *The efficacy and cost-effectiveness of patient navigation programs across the cancer continuum: A systematic review*. Cancer. 2019.
- Chan RJ et al. *Patient navigation across the cancer care continuum: An overview of systematic reviews and emerging literature*. CA Cancer J Clin. 2023.
- Kiely B et al. *Effect of social prescribing link workers on health outcomes and costs*. BMJ Open. 2022.
- Gervès-Pinquié C et al. *Economic evaluation of patient navigation programs in colorectal cancer care, a systematic review*. 2018.
- *Cost-effectiveness of patient navigation programs for stroke patients—A systematic review*. 2021.
- *Changes in healthcare use and cost associated with referrals to social prescribing link workers in England*. 2026.
- *A remote care navigation solution associated with improved utilization and outcomes of mental healthcare*. 2025.
- Van Oyen MP et al. *A Capacity Allocation Planning Model for Integrated Care and Access Management*. 2018.
