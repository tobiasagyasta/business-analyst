# Decision Gates and Validation

Apply `methodology/indonesia-and-currency.md` and `methodology/evidence-and-confidence.md`. This is the authoritative standard for decision-changing uncertainties, gates, validation, reconsideration conditions, and research stop rules. It applies to proposed recommendations, not human approval.

## Purpose and Proportionality

Reduce uncertainty only when doing so could materially improve the decision. Do not research an unknown merely because it is unknown. Scale rigor to materiality, reversibility, downside exposure, deadline, and available evidence:

- Reversible, low-materiality decisions may use one critical uncertainty, one bounded test or check, and one review trigger.
- Material, costly, or hard-to-reverse decisions require a ranked uncertainty assessment, explicit gates, alternatives, challenge review, and stronger evidence before commitment.
- Use the lightest reliable method that can distinguish the viable options. Do not use a cheap weak test when strong evidence is necessary, or a costly test when a smaller one answers the decision-critical question.

## Decision-Changing Uncertainties

After synthesis and challenge review, identify only uncertainties capable of changing the recommended action, timing, scale, conditions, or need for human escalation. A missing fact that does not change any of these is not decision-critical.

For each material uncertainty, record as applicable:

| Rank | Uncertainty and affected option | Impact if wrong | Current evidence strength | Cost of being wrong / reversibility | Testability | Validation cost and time | Likelihood result changes decision | Next step |
|---|---|---|---|---|---|---|---|---|
| `[1]` | `[variable and decision effect]` | `[high/medium/low, why]` | `[HIGH/MEDIUM/LOW, why]` | `[consequence]` | `[high/medium/low]` | `[Rp/time/effort or UNKNOWN]` | `[high/medium/low, why]` | `[gate, validation, tolerate, or owner judgment]` |

This is a reasoned ranking, not a mandatory scoring formula. High-impact, weakly supported uncertainties normally receive priority. High-impact, strongly supported uncertainties normally do not need more research. Low-impact, weakly supported uncertainties are often tolerable. Record why an apparently important uncertainty is not pursued.

## Decision Gates

A gate is an observable condition that determines whether to proceed, proceed conditionally, experiment, gather information, defer, reject, or escalate for human judgment. A gate must identify the condition, evidence required, consequence, owner, timing, and threshold origin when a threshold is used.

Use the gate type that fits the decision. Do not force a numeric gate where informed judgment is the real constraint.

| Gate type | Appropriate conditions |
|---|---|
| Quantitative | Margin, cash reserve, CAC, conversion, payback, capacity, defects, or other measurable performance reaches a derived level. |
| Operational | SOP is tested, qualified staff are available, capacity is proven, or supplier redundancy exists. |
| Contractual / legal | Permit, liability, termination, payment, regulatory, or contract condition is acceptable. |
| Strategic | The action fits the target segment and positioning and does not create unacceptable dependency or conflict. |
| Evidence-based | A stated sample, repeat behavior, channel economics, observation, or other evidence threshold is met. |
| Human judgment | Owner choice about values, brand direction, lifestyle, growth speed, debt tolerance, ethical concern, or acceptable downside. |

For material recommendations, use this format where relevant:

| Gate | Type | Required evidence / condition | Threshold origin | If met | If not met | Owner and timing |
|---|---|---|---|---|---|---|
| `[name]` | `[type]` | `[observable condition]` | `[source]` | `[action]` | `[action]` | `[role/date]` |

Allowed threshold origins include `Derived from break-even model`, `Derived from scenario or sensitivity analysis`, `Observed historical baseline`, `Owner-defined constraint`, `Capacity limit`, `Contract or regulatory requirement`, `External benchmark`, `Experiment baseline`, and `UNKNOWN - requires analysis`. Do not use arbitrary round-number thresholds. A human-defined limit is valid when explicitly labeled as such.

## Validation Choice and Value

Classify the proposed next step before recommending it:

- **Research** produces information without changing the business, such as internal-data analysis, financial or scenario modeling, interviews, surveys, observation, competitor research, supplier quotations, vendor interviews, expert consultation, legal/accounting review, negotiation, wait-and-observe, or no further research.
- **Experiment** introduces a bounded, controlled business action to measure behavior, such as a prototype, pilot, A/B test, limited rollout, pricing or geographic test, preorder, pop-up, landing page, paid-ad test, manual simulation, shadow process, staff trial, temporary supplier test, capacity test, or technical proof of concept.
- **Commitment** creates material or difficult-to-reverse exposure, such as a lease, hire, equipment purchase, debt, or long-term contract.

When a decision-changing uncertainty remains, prefer research or experiment before commitment only if it has positive decision value. Compare feasible methods on uncertainty reduced, chance of changing the decision, reliability and scope fit, cost in `Rp` where relevant, elapsed time, effort and operational disruption, reversibility, dependencies, and whether a result can satisfy the gate. Select the smallest reliable method, or explicitly choose no further research.

Validation plans must state: uncertainty tested; method and rationale; population or scope; cost/time limit; measurement and baseline; pass, fail, and inconclusive handling; guardrails; decision linked to the result; and a stop rule. If the result cannot plausibly change the action, do not validate it.

## Recommendation States and Reconsideration

Use these recommendation states when useful. They describe the proposed course; decision-record status remains governed by `methodology/decision-method.md` and requires a human change from `proposed`.

| Proposed state | Meaning |
|---|---|
| `PROCEED` | Current evidence and gates support the action; no material unresolved uncertainty requires validation. |
| `PROCEED CONDITIONALLY` | Action may proceed only under stated gates, safeguards, or review points. |
| `EXPERIMENT` | A bounded business action is the best way to resolve a decision-changing uncertainty. |
| `DEFER AND VALIDATE` | A commitment should wait for stated evidence or a validation result. |
| `DEFER` | Timing, constraints, or irreducible uncertainty make action inappropriate now; no useful validation is proposed. |
| `REJECT` | Evidence, constraints, or downside makes the option unsuitable. |
| `ESCALATE FOR HUMAN JUDGMENT` | A material owner preference, value, risk tolerance, or strategic identity trade-off is unresolved. |

Every material proposed recommendation must state what would change it, including the relevant uncertainty, observable condition, direction of recommendation change, evidence source, owner, and review timing. `No currently known condition would change the recommendation` is allowed when supported by the record. Do not present monitoring as a reconsideration condition unless a specific trigger and action are defined.

## Stop Rules

Stop research or validation when one or more conditions applies:

- The proposed decision is unchanged across plausible remaining uncertainty.
- The gate's required evidence threshold has been met.
- Marginal validation cost, delay, or disruption exceeds its likely decision value.
- The deadline requires an owner decision.
- The uncertainty is inherently irreducible at a reasonable cost.
- Only low-impact uncertainties remain.
- Options are sufficiently separated under plausible scenarios.
- Human judgment, rather than missing evidence, is the limiting factor.

Record the applicable stop rule and the residual uncertainty accepted. A stop rule does not convert a proposed recommendation into approval.

## Proportionality Checks

Use these checks to confirm the method fits the decision without performing an analysis in this standard:

| Decision type | Expected application |
|---|---|
| Major expansion | Rank demand, financial, operational, legal, and strategic uncertainties; derive financial and readiness gates; validate only unresolved high-impact variables before a hard commitment. |
| Price change | Evaluate economics and customer response; a reversible bounded price test may be preferable to broad market research when evidence is weak. |
| Hire | Test whether a sustained capacity constraint and labor economics justify a full-time commitment; compare a trial, temporary, or process alternative when relevant. |
| Marketing spend | Derive contribution and CAC conditions; use a capped campaign test when current evidence cannot establish channel economics. |
| Supplier switch | Gate on quality, reliability, cost, terms, and switching risk; a sample order or temporary supply trial may answer the critical uncertainty before switching. |
| Small operating-hours change | Use a lightweight incremental-contribution and capacity check, with a short reversible trial only if needed; do not require a committee or broad research. |
