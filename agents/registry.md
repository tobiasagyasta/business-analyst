# Agent Capability Registry

Use this registry for capability-based routing. Select only agents whose capabilities materially reduce decision uncertainty. The orchestrator coordinates work; the Business Strategist owns strategic synthesis, not scheduling or approval. Every routed agent follows `methodology/indonesia-and-currency.md`.

| Agent definition | Domain and capabilities | Use when | Do not select when | Typical inputs | Typical output | Dependencies / parallelism |
|---|---|---|---|---|---|---|
| `business-strategist.md` | Strategic fit, business model, positioning, options, trade-offs | A decision needs cross-functional synthesis, material strategic choices, or portfolio effects | A narrow operational fact can be answered directly | Brief; relevant specialist artifacts; selected context | Synthesis, options, proposed recommendation, challenge review | Runs after independent analyses; can perform challenge now |
| `specialized-pricing-analyst.md` | Prices, packages, margins, competitor positioning | Price, discount, bundle, mix, or unit-margin questions | No price or offer economics are implicated | Product costs, prices, sales mix, competitor data | Pricing Analysis Artifact | Parallel with research and finance where inputs are independent |
| `finance-fpa-analyst.md` | Forecasts, cash, scenarios, investment, targets | Material cash, profitability, investment, hiring, or forecast impact | A low-cost marketing test has no material financial exposure | Actuals, cost model, assumptions, limits | Financial Analysis Artifact | Parallel with other analysis; required for major commitments |
| `product-trend-researcher.md` | Market, customer, competitor, demand signals | External demand, category, customer, competitor, or market-entry uncertainty matters | Internal operational question with adequate local evidence | Geography, segment, question, allowed sources | Market Research Artifact | Usually parallel |
| `sales-offer-lead-gen-strategist.md` | Offers, conversion, lead generation, channel choice | Offer design, acquisition channel, lead flow, conversion question | Pricing, operations, or finance question has no acquisition component | Segment, current offer, funnel data, constraints | Offer / Lead Generation Artifact | Parallel with marketing; finance only if economics need validation |
| `marketing-growth-hacker.md` | Acquisition experiments, funnels, retention, channels | Measurable growth, campaign, funnel, or retention experiments | Major capital decision without a customer-acquisition component | Segment, channel data, budget, measurement capability | Growth Experiment / Marketing Artifact | Parallel with sales and research |
| `operations-manager.md` | Capacity, process, staffing, suppliers, implementation | Feasibility, hours, service delivery, staffing, procurement, or execution planning matters | A recommendation has not yet been sufficiently validated | Process, capacity, staffing, supplier, constraint data | Operations Analysis or Execution Plan | Parallel for feasibility; execution handoff after approval |

## Routing Rules

1. Start with the decision question, affected scope, reversibility, materiality, deadline, and missing critical evidence.
2. Match required capabilities to the table, then write a specific assignment for each selected agent using `decisions/templates/specialist-assignment.md`.
3. Run independent work in parallel. Give dependent follow-up work only the artifacts it needs.
4. Do not choose an agent just because it exists. Record exclusions in the analysis plan when useful.
5. A future agent is added by creating its definition, adding one row here with capabilities, boundaries, inputs, outputs, dependencies, and parallelism, and optionally adding focused methodology. No workflow rewrite is required.

## Naming and Contract

Name definitions by capability, for example `marketing/social-media-strategist.md` or `operations/procurement-analyst.md`. Every new agent must accept a scoped specialist assignment and return the common analysis artifact sections in `methodology/artifact-contracts.md`. It may delegate only for a missing capability; it must state the dependency and avoid making a final cross-functional decision.
