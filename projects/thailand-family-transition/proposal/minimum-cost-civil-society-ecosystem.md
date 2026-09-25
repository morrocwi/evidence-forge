# Minimum-cost civil-society architecture for stronger families and better child well-being

## Status

This is a **working theoretical proposal expressed as an optimisation problem**.

It does not claim that one intervention has already been proven to be the globally cheapest. The aim is narrower and more testable:

> Given that many expensive services already exist in government, health systems, schools, cultural/community institutions—including faith-based institutions—and NGOs, what is the **minimum additional civil-society layer** needed to make those resources easier to find, safer to use, better connected, and more useful across the family life course?

The proposal therefore minimises **new service duplication** and prioritises **connectivity, trust, safe access, navigation, caregiver support, parenting support and re-entry**.

---

# 1. Start from the existing equation

The larger problem has already been written as:

\[
Policy\ supply
\neq
Effective\ access
\neq
Family\ capability
\neq
Realized\ family\ opportunity
\neq
Population\ fertility
\tag{1}
\]

Civil society has limited capacity to directly finance the most expensive terms:

\[
\{
housing,\,
paid\ leave,\,
specialist\ health\ care,\,
ART,\,
income\ replacement,\,
large\ childcare\ infrastructure
\}
\tag{2}
\]

But it can act on the transitions between those systems.

Let existing public/private service capacity be:

\[
\mathcal{V}
=
\{
health,\,
social,\,
education,\,
cultural\ community,\,
legal,\,
mental\ health,\,
child\ protection,\,
fertility,\,
parenting,\,
community
\}
\tag{3}
\]

The central question becomes:

\[
\text{How can civil society increase the usable connectivity of } \mathcal{V}
\text{ at minimum additional cost?}
\tag{4}
\]

---

# 2. Change the optimisation target

Do not solve:

\[
\max Births
\tag{5}
\]

and do not solve:

\[
\max Number\ of\ programmes
\tag{6}
\]

Instead define a vector of outcomes:

\[
\mathbf{Y}_{i,t}
=
\langle
A^{eff},
Safe,
W^{caregiver},
R^{family},
M^{meaning},
Q^{child},
E^{equity}
\rangle_{i,t}
\tag{7}
\]

where:

- \(A^{eff}\) = effective access to appropriate services;
- \(Safe\) = safety, autonomy and confidential help access;
- \(W^{caregiver}\) = caregiver well-being;
- \(R^{family}\) = relationship/family functioning and repair capacity;
- \(M^{meaning}\) = the degree to which family life and support remain coherent with the person's endorsed values, identity, belonging and life purposes without coercive conformity;
- \(Q^{child}\) = child well-being/development;
- \(E^{equity}\) = whether vulnerable groups can use the system, not only formally qualify.

For child well-being, use the internationally established nurturing-care domains:

\[
Q^{child}
=
\langle
Health,\,
Nutrition,\,
Safety,\,
ResponsiveCaregiving,\,
Learning
\rangle
\tag{8}
\]

Caregiver well-being is treated as an enabling condition because caregivers' mental health and social support affect their capacity to provide nurturing care.


## 2.1 Culture and meaning are part of the outcome, not decoration

Culture is broader than religion.

For this paper, cultural context may include:

\[
C^{culture}_{i,t}
=
\langle
Language,\,
Kinship,\,
FamilyNorms,\,
GenderNorms,\,
ChildbearingMeaning,\,
CareNorms,\,
RitualBelief,\,
Place,\,
MigrationHistory,\,
Class,\,
Generation
\rangle_{i,t}
\tag{8a}
\]

Religion or faith can be one part of this context, but it is not the master category.

Two people who share a religion, ethnicity, village or nationality may still attach different meanings to marriage, childbearing, caregiving and a good life. Culture must therefore be treated as **dynamic, plural and internally contested**, not as a fixed label assigned to a community.

The design must preserve three non-collapse rules:

\[
CulturalFit \neq CulturalConformity
\tag{8b}
\]

\[
RespectForCulture \neq PreservationOfCoerciveNorms
\tag{8c}
\]

\[
CommunityApproval \neq PersonalMeaning
\tag{8d}
\]

A culturally responsive system should help people pursue support that is intelligible and meaningful in their context while protecting autonomy, safety and informed choice.

This matters because reproductive decisions are shaped by social norms, kinship, gender expectations and meanings attached to children and family life, while coercive norms can also restrict reproductive agency.

---

# 3. Minimum-cost formulation

Let \(z\) be the set of civil-society actions.

The optimisation problem is:

\[
z^{*}
=
\arg\min_{z}
C(z)
\tag{9}
\]

subject to:

\[
\Delta A^{eff}\ge a^{*}
\tag{10a}
\]

\[
Safe\ge s^{*}
\tag{10b}
\]

\[
\Delta W^{caregiver}\ge w^{*}
\tag{10c}
\]

\[
\Delta Q^{child}\ge q^{*}
\tag{10d}
\]

\[
E^{equity}\ge e^{*}
\tag{10e}
\]

\[
M^{meaning}\ge m^{*}
\tag{10f}
\]

\[
Autonomy\ge a^{autonomy*}
\tag{10g}
\]

and:

\[
SpecialistSubstitution=0
\tag{10h}
\]

Equation (10f) is essential. Civil society should not minimise cost by making unqualified volunteers perform the work of doctors, psychologists, child-protection specialists, violence responders or lawyers.

The low-cost solution must therefore come mainly from:

\[
\text{better interfaces}
+
\text{earlier recognition}
+
\text{navigation}
+
\text{safe disclosure}
+
\text{group/community support}
+
\text{targeted referral}
+
\text{re-entry}
\tag{11}
\]

rather than from duplicating expensive specialist services.

---

# 4. Model the ecosystem as a network

Let:

\[
G=(V,E)
\tag{12}
\]

where:

- \(V\) = existing service and community nodes;
- \(E\) = usable pathways between them.

Examples of nodes:

\[
V=
\{
clinic,\,
hospital,\,
mosque,\,
church,\,
civil\ society,\,
school,\,
family\ centre,\,
child\ protection,\,
mental\ health,\,
legal\ aid,\,
parenting\ programme,\,
fertility\ service
\}
\tag{13}
\]

In many settings, adding a new specialist node is expensive:

\[
c_{node}^{specialist}
\gg
c_{edge}^{navigation/referral}
\tag{14}
\]

Therefore the first civil-society strategy should be:

\[
\min NewNodes
\quad
\text{while}
\quad
\max SafeUsableEdges
\tag{15}
\]

This does not mean that new services are never needed. It means that the lowest-cost first move is to test whether existing capacity is being lost because the graph is disconnected.

---

# 5. Minimum safe connectivity constraint

For every person/family \(i\) with a relevant need \(k\), require at least one usable path:

\[
\exists \pi_{i,k}
:
Entry_i
\rightsquigarrow
Service_k
\tag{16}
\]

with:

\[
Accessible(\pi_{i,k})=1
\tag{17a}
\]

\[
Safe(\pi_{i,k})=1
\tag{17b}
\]

\[
Understandable(\pi_{i,k})=1
\tag{17c}
\]

\[
Followable(\pi_{i,k})=1
\tag{17d}
\]

\[
Reenterable(\pi_{i,k})=1
\tag{17e}
\]

A directory that nobody can understand or safely use does not satisfy the constraint.

A referral that gives a phone number but has no practical path to completion does not satisfy the constraint.

---

# 6. Civil society should build a thin layer, not a parallel welfare state

The minimum-cost civil-society layer contains nine functions.

## 6.1 Map

Maintain a verified map of:

- health services;
- reproductive/preconception services;
- fertility/infertility services;
- mental-health services;
- violence and child-protection services;
- family counselling;
- legal/social support;
- parenting/child-development support;
- Islamic, Christian and other trusted community supports.

The map should state:

- who is eligible;
- cost;
- language;
- location/digital channel;
- privacy conditions;
- operating hours;
- required documents;
- emergency versus non-emergency use.

The value is not the database itself. The value is reducing:

\[
LearningCost + SearchCost + WrongDoorCost
\tag{18}
\]

---

## 6.2 Trusted entry points

Use places people already approach:

- mosque;
- church;
- community organisation;
- family centre;
- school;
- health clinic;
- marriage-preparation programme;
- civil society service;
- digital community.

Do not require every trusted node to deliver every service.

Require only that each node can:

\[
Recognise
\rightarrow
Orient
\rightarrow
Refer
\tag{19}
\]

within its competence.

---

## 6.3 Minimum universal orientation

The universal layer should be brief.

Its purpose is not to teach the entire life course.

It should ensure that people know:

1. what should be discussed now;
2. which warning signs require help;
3. where reproductive/preconception care can be found;
4. where mental-health help can be found;
5. how to access a private **พื้นที่ปลอดภัย**;
6. how to return later.

This keeps universal cost low.

---

## 6.4 Two preparation speeds

For marriage preparation:

\[
ShortTimeline
\Rightarrow
MinimumSufficientCore
+
ReturnRoute
\tag{20a}
\]

\[
LongerTimeline
\Rightarrow
Core
+
OptionalDeeperModules
+
Practice
\tag{20b}
\]

Do not force an urgent couple to complete the same time-intensive pathway as a couple preparing months in advance.

Do not treat the rapid pathway as inferior. Its objective is different.

---

## 6.5 พื้นที่ปลอดภัย / private safe access

Every entry system should provide a clearly visible confidential route independent of the shared couple channel.

Minimum specification:

\[
SafeSpace
=
Privacy
+
Confidentiality
+
IndividualAccess
+
SafeDisclosure
+
RiskRecognition
+
ProtectedReferral
\tag{21}
\]

Community, cultural or faith-based workers do not investigate violence. They recognise limits and refer.

---

## 6.6 Progressive referral intensity

Use a referral ladder as a **design sequence to test**, not as an assumed effectiveness ranking:

\[
Information
\rightarrow
Signposting
\rightarrow
WarmReferral
\rightarrow
AccompaniedReferral
\tag{22}
\]

A systematic review of warm handoffs found only five eligible studies and three reported improved service receipt. The evidence is therefore promising but limited.

Use the least intensive step that is adequate, then escalate when risk, literacy, complexity, prior referral failure or access barriers justify additional support.

For ordinary needs, signposting may be enough.

For harder-to-navigate or high-risk cases, warm or accompanied referral may be worth the additional cost, but referral completion and marginal cost must be measured.

---

## 6.7 Re-entry

Give people a persistent way back:

- QR code;
- LINE / WhatsApp / secure messaging;
- phone;
- community contact;
- scheduled check-in;
- culturally trusted community mentor or faith/community contact where appropriate.

Re-entry should be possible at:

\[
\{
fertility,\,
infertility,\,
pregnancy,\,
birth,\,
parenting,\,
school\ transition,\,
conflict,\,
mental\ health,\,
violence,\,
separation
\}
\tag{23}
\]

A major cost-saving implication follows:

\[
\text{Do not teach everything now}
\quad\Rightarrow\quad
\text{make later access reliable}
\tag{24}
\]

---

## 6.8 Open-access parenting support

Do not build a new proprietary parenting curriculum unless necessary.

Use/adapt evidence-based open resources where licensing permits, such as:

- Parenting for Lifelong Health;
- Care for Child Development;
- Caring for the Caregiver;
- other validated local programmes.

WHO describes Parenting for Lifelong Health as open access, non-commercialised and designed for low-resource settings.

UNICEF's Care for Child Development is explicitly designed to integrate responsive-caregiving support into existing services.

The lowest-cost deployment question is therefore not:

> “Can civil society invent another parenting programme?”

but:

> “Which evidence-based components can be embedded in existing trusted contacts with the least additional workforce and burden?”

---

## 6.9 Minimal data layer

Collect only the minimum necessary data.

Track:

- entry point;
- need category;
- referral offered;
- referral completed where knowable;
- re-entry;
- safety escalation;
- caregiver/child outcome measures in evaluation samples.

Do not create a large personal-data warehouse.

For safe-space cases, data minimisation and access control are part of safety.

---

# 7. Progressive support tiers

Use universal low-cost support for everyone, then spend more only where need rises.

## Tier 0 — information infrastructure

Cost: very low marginal cost after setup.

Functions:

- verified service map;
- universal orientation;
- QR/digital return route;
- basic self-navigation;
- privacy/safety information.

## Tier 1 — community support

Cost: low to moderate.

Functions:

- group learning;
- peer/community support;
- parenting groups;
- trained lay navigation;
- caregiver support;
- basic follow-up.

Evidence supports trained lay counsellors and community-based workers for selected tasks, but supervision and role boundaries are required.

## Tier 2 — targeted professional support

Cost: moderate to high.

Functions:

- counselling;
- reproductive/preconception care;
- developmental assessment;
- specialised parenting intervention;
- mental-health treatment.

## Tier 3 — specialist/protective response

Cost: high but necessary for smaller numbers.

Functions:

- emergency safety response;
- violence/child protection;
- specialist psychiatry;
- complex medical/fertility care;
- legal protection.

The cost logic to test is:

\[
UniversalLightTouch
+
TargetedIntensity
stackrel{?}{<}
UniversalHighIntensity
\tag{25}
\]

This is an open economic proposition. It should only be retained if targeting, referral, outcomes and total programme costs—including supervision and coordination—show a genuine advantage.

---

# 8. Why child well-being is a central endpoint

The civil-society architecture should be evaluated against the five nurturing-care domains:

\[
Q^{child}
=
\langle
GoodHealth,\,
AdequateNutrition,\,
SafetySecurity,\,
ResponsiveCaregiving,\,
LearningOpportunities
\rangle
\tag{26}
\]

Civil society has different leverage over each domain.

| Child domain | Direct civil-society leverage | Indirect/referral leverage |
|---|---|---|
| health | health literacy, navigation | clinics, immunisation, treatment |
| nutrition | education, community support | nutrition/health services |
| safety/security | parenting, safe spaces, recognition | protection/violence services |
| responsive caregiving | strong direct leverage through parenting support | specialist help where needed |
| early learning | play/read/talk coaching, community activities | ECD/school services |

Therefore the lowest-cost civil-society contribution is expected to be strongest where:

\[
CommunityAction
\cap
LowSpecialistRequirement
\cap
HighRepeatedExposure
\tag{27}
\]

especially:

- responsive caregiving;
- violence prevention/positive parenting;
- caregiver social support;
- early learning;
- navigation into health and protection systems.

---

# 9. Caregiver well-being is not an optional side outcome

Let:

\[
W^{caregiver}
=
f(
MentalHealth,
SocialSupport,
Time,
EconomicPressure,
Safety,
CareBurden
)
\tag{28}
\]

If caregiver well-being falls far enough:

\[
W^{caregiver}\downarrow
\Rightarrow
CapacityForNurturingCare\downarrow
\tag{29}
\]

UNICEF's Caring for the Caregiver explicitly links caregiver emotional/social well-being to nurturing care.

A child-development ecosystem that only teaches parents what to do while ignoring whether they have the emotional and practical capacity to do it risks collapsing:

\[
Knowledge
\stackrel{?}{=}
Capability
\tag{30}
\]

which this project rejects.

---

# 10. Use trained community members, but do not exploit them

Evidence from low- and middle-income countries shows that trained community workers can improve selected service-use, behavioural and process outcomes, while clinical and cost-effectiveness results vary across domains.

But low cost must not mean unpaid, unsupported labour, and community delivery should not be assumed inherently affordable.

Let:

\[
C_{community}
=
Training
+
Supervision
+
Coordination
+
Safeguarding
+
FairCompensation
\tag{31}
\]

If compensation/supervision approach zero:

\[
ApparentLowCost
\rightarrow
HiddenLabourCost
+
QualityRisk
+
Burnout
\tag{32}
\]

The real optimisation must count those costs.

---

# 11. Evidence from parenting programmes changes the cost design

Parenting interventions can improve child cognitive, language and motor development in low- and middle-income countries, with heterogeneous effects.

WHO's Parenting for Lifelong Health is open access and explicitly designed for low-resource settings.

However, a 2026 Thai costing study estimated provider costs of approximately USD 82–195 per caregiver and nationwide one-year budget impact of USD 50–76 million across scaling scenarios. The authors concluded that national scaling could be prohibitively expensive and suggested exploring fewer sessions or hybrid delivery while maintaining quality.

This is critical.

It suggests that:

\[
EvidenceBasedProgramme
\neq
AffordableUniversalProgramme
\tag{33}
\]

Therefore:

\[
UniversalNavigation
+
TargetedParentingSupport
\tag{34}
\]

may be more financially plausible than delivering a full multi-session programme universally.

A 2026 Thai cluster randomised trial tested a blended programme using two brief in-person meetings plus facilitated LINE group chats. It **did not show a significant reduction in overall child maltreatment or physical abuse at one-month follow-up**, and the emotional-abuse estimate was higher in the intervention arm; the authors noted this might reflect reporting/awareness effects and called for refinement and longer-term testing. The study therefore supports the **feasibility of blended delivery**, not a claim that hybrid delivery has already been shown to reduce violence in this Thai trial.

---

# 12. Existing cultural/community systems may reduce entry cost

The master lens here is **culture**, not religion.

A mosque, church, temple, neighbourhood group, ethnic association, migrant network, women's group, youth organisation, family association or other community institution may already possess some combination of:

- trust;
- routine contact;
- language competence;
- knowledge of kinship and family norms;
- physical or digital space;
- communication channels;
- staff/volunteers;
- legitimacy around family life;
- locally meaningful ways of discussing marriage, children, care, ageing and responsibility.

Faith-based institutions remain important examples, but they are one subset of a wider cultural ecology.

A culturally embedded node may lower entry burden because it already speaks a language—literal and symbolic—that users understand. But this is not assumed automatically.

Treat the following as a hypothesis to test:

\[
C(NewInstitution)
\stackrel{?}{>}
C(AddInterface\ to\ ExistingCulturalNode)
\tag{35}
\]

and separately test:

\[
CulturalLegibility
\stackrel{?}{\longrightarrow}
Engagement
\tag{35a}
\]

Cultural legibility must never be purchased by suppressing autonomy.

Therefore:

\[
MeaningCompatibility
=
f(
Values,\,
Identity,\,
Belonging,\,
FamilyMeaning,\,
Voice,\,
Autonomy
)
\tag{35b}
\]

subject to:

\[
Safety\ge threshold
\quad\land\quad
Autonomy\ge threshold
\tag{35c}
\]

The interface should add:

\[
\{
navigation,\,
safe\ private\ route,\,
health\ referral,\,
mental\ health\ referral,\,
parenting\ support,\,
re\text{-}entry
\}
\tag{36}
\]

without requiring cultural/community institutions to provide specialist services outside their competence.

Islamic and Christian premarital systems should therefore be analysed as **specific cultural-institutional cases** within this larger architecture, alongside other community systems.

---

# 13. Minimal civil-society package

The smallest plausible package to test is:

\[
z_{min}
=
\{
Map,\,
CoreOrientation,\,
TrustedEntry,\,
SafePrivateRoute,\,
Referral,\,
Reentry,\,
TargetedParenting
\}
\tag{37}
\]

Optional add-ons:

\[
z_{+}
=
\{
LayCounselling,\,
PeerGroups,\,
CaregiverSupport,\,
ChildLearningActivities,\,
CaseNavigation
\}
\tag{38}
\]

The package should be expanded only when evaluation shows a bottleneck that the smaller package cannot resolve.

---

# 14. The design rule: add edges before adding nodes

Before creating a new service, test:

1. Does an adequate service already exist?
2. Do people know it exists?
3. Can they enter it?
4. Is the route safe?
5. Can they complete referral?
6. Can they return later?
7. Is the service culturally/institutionally acceptable?
8. Is capacity sufficient?

If the answer fails at 2–7, improve the edge.

If it fails at 1 or 8, a new node/capacity may actually be required.

Thus:

\[
MissingNode
\neq
MissingEdge
\tag{39}
\]

This distinction is central to cost control.

---

# 15. Evaluation

Do not evaluate the civil-society ecosystem only by:

- attendance;
- course completion;
- satisfaction;
- number of referrals issued;
- marriage persistence;
- birth count.

Evaluate:

## Access

\[
Reach,\ Discoverability,\ TimeToHelp,\ ReferralCompletion,\ Reentry
\tag{40}
\]

## Safety

\[
PrivateAccess,\ SafeDisclosure,\ AppropriateEscalation,\ ConfidentialityFailure
\tag{41}
\]

## Caregiver

\[
MentalHealth,\ SocialSupport,\ ParentingStress,\ CareBurden
\tag{42}
\]

## Child

\[
Health,\ Nutrition,\ Safety,\ ResponsiveCaregiving,\ Learning,\ Development
\tag{43}
\]

## Equity and meaning

Compare outcomes across:

\[
Income,\ Gender,\ Disability,\ Migration,\ Language,\ DigitalAccess,\ Geography,\ CulturalContext
\tag{44}
\]

Also examine:

\[
MeaningCoherence,\ Belonging,\ Voice,\ Autonomy,\ CulturalAcceptability
\tag{44a}
\]

Do not score cultural conformity as a positive outcome. The relevant question is whether people can pursue valued family lives and obtain support without losing voice, safety or autonomy.

## Cost

\[
CostPerReachedFamily
\tag{45a}
\]

\[
CostPerCompletedReferral
\tag{45b}
\]

\[
CostPerImprovedParentingOutcome
\tag{45c}
\]

\[
CostPerImprovedChildOutcome
\tag{45d}
\]

---

# 16. Research design to test minimum cost

Do not begin with national scale.

Use staged optimisation.

## Stage 1 — graph audit

Map existing nodes and edges in one area.

Measure:

- duplication;
- missing links;
- waiting time;
- drop-off;
- unsafe channels;
- dead ends.

## Stage 2 — add only the thin layer

Introduce:

- map;
- universal orientation;
- safe private access;
- referral;
- re-entry.

Measure whether connectivity improves.

## Stage 3 — add targeted group parenting/caregiver support

Only for families whose needs are not solved by navigation alone.

## Stage 4 — compare marginal gain

For each added component \(z_k\):

\[
MCE_k
=
\frac{\Delta Outcome_k}{\Delta Cost_k}
\tag{46}
\]

Retain components with meaningful marginal gain.

Remove or redesign components with low value, burden or harm.

---

# 17. What civil society cannot repair cheaply

The proposal must not become an excuse to shift state responsibilities onto families or volunteers.

Civil society cannot cheaply substitute for:

- housing affordability;
- income security;
- labour regulation;
- paid parental leave;
- universal childcare;
- specialist health care;
- fertility treatment;
- formal child protection;
- justice/legal protection.

Therefore:

\[
CivilSocietyConnectivity
\neq
StructuralPolicyReplacement
\tag{47}
\]

The architecture can improve conversion of existing resources into lived access.

It cannot manufacture absent structural resources at negligible cost.

---

# 18. Falsifiers

The proposal should be weakened if evidence shows that:

1. mapping/navigation does not improve effective access;
2. warm referral does not improve completion over ordinary signposting;
3. trusted community entry points do not improve reach;
4. private safe routes do not improve safe disclosure/help-seeking in relevant risk groups;
5. re-entry adds no value;
6. targeted parenting support performs worse economically than universal delivery;
7. community delivery creates unacceptable fidelity/safety problems even with supervision;
8. better connectivity fails because specialist capacity is the true binding constraint;
9. child outcomes do not improve despite better caregiver/support outcomes;
10. marginal costs of coordination are not meaningfully lower than creating new service capacity.

---

# 19. The strongest current proposition

The lowest-cost role for civil society is unlikely to be building a second welfare state.

A more plausible **first hypothesis to test** is whether civil society creates more value by making the existing ecosystem **legible, connected, safe, re-enterable and capable of escalating intensity only when needed** before creating additional high-cost specialist capacity.

In compact form:

\[
\boxed{
\min Cost
\quad
\text{by}
\quad
\max
\left(
Connectivity
+
SafeAccess
+
Navigation
+
Reentry
+
CulturalLegibility
+
MeaningCompatibleSupport
+
TargetedCommunitySupport
\right)
}
\tag{48}
\]

subject to:

\[
Quality\ge threshold
\tag{49a}
\]

\[
Safety\ge threshold
\tag{49b}
\]

\[
Equity\ge threshold
\tag{49c}
\]

\[
MeaningCompatibility\ge threshold
\tag{49d}
\]

\[
Autonomy\ge threshold
\tag{49e}
\]

\[
SpecialistSubstitution=0
\tag{49f}
\]

and with child well-being evaluated through:

\[
\boxed{
Health
+
Nutrition
+
Safety
+
ResponsiveCaregiving
+
Learning
}
\tag{50}
\]

This is the version that should now be attacked with global citations, economic evaluations, implementation science and counterexamples before it is translated into ordinary language.
