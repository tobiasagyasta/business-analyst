# Decision Work

Create one folder per decision, named with a stable ID such as `2026-01-coffee-price-review`. Copy only the templates that the decision needs.

Suggested layout:

```text
decisions/<decision-id>/
  brief.md
  analysis-plan.md
  analyses/
  synthesis.md
  challenge.md
  options.md
  recommendation.md
  decision-record.md
  execution.md
  review.md
```

Reference durable context files instead of copying them. Keep source evidence in the decision folder only when it is decision-specific or cannot be referenced from a durable source.

All internal monetary artifacts use `IDR` / `Rp`; record the Indonesian geographic scope of the decision.
