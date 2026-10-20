# Business Decision System

This repository is a reusable, evidence-aware system for supporting small-business decisions. It stores durable business knowledge separately from decision work; it does not make or approve decisions automatically.

## Authoritative Structure

- `company/shared/`: durable context that applies across the business portfolio.
- `company/<business-id>/`: durable context for one business. A location-specific fact belongs here with its location scope stated.
- `decisions/<decision-id>/`: one decision's brief, targeted analyses, recommendation, approval state, execution, and review.
- `methodology/`: reusable standards and workflow.
- `agents/registry.md`: capability-based registry used to select agents. Agent definitions remain in `agents/`.

## Non-Negotiable Rules

- Never invent business data, sources, customer claims, calculations, or outcomes. State `UNKNOWN` when information is unavailable.
- Treat Indonesia as the default market and use `IDR` / `Rp` for internal monetary context and calculations. Follow `methodology/indonesia-and-currency.md`.
- Classify material claims as `FACT`, `OBSERVATION`, `INFERENCE`, `HYPOTHESIS`, `ASSUMPTION`, `UNKNOWN`, or `CONFLICTING EVIDENCE`.
- Preserve scope, source, date/freshness, limitation, and confidence for material claims.
- Treat a recommendation as `proposed` until a human marks the decision `approved`, `rejected`, `deferred`, or `experimental`.
- Send each specialist only the context and evidence needed for its explicit assignment. Reference durable files instead of copying them.
- Specialists analyze their domain; the Business Strategist synthesizes options and recommendation. Do not bypass the challenge stage for material commitments.
- Store decision artifacts in the relevant decision folder and update durable context only after results have been reviewed and provenance is retained.

Read `methodology/operating-workflow.md` before starting decision work. Use `methodology/` templates and `decisions/templates/` rather than creating ad hoc formats.
