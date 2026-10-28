# Classification gates (draft)

> **Draft only.** These are conservative workflow controls, not legal thresholds or platform enforcement rules.

## Gate sequence

1. **Authorization and scope:** confirm authority to review, the subject, review date, applicable geographies, and boundaries. If material scope is missing, stop with **NOT RATED — SCOPE INCOMPLETE**; do not assign one of the four ratings.
2. **Evidence sufficiency:** every conclusion needs a traceable evidence reference. Missing, inaccessible, stale, conflicting, or unverified evidence cannot support CLEAR. Mark Not assessed; use CONDITIONAL where the uncertainty is material to the overall outcome.
3. **Current-source check:** for a claim about a law, regulator, Stripe, Meta, or another platform, identify and check the current official source for the relevant region and date. If that has not been done, phrase the point as an unverified question, not a rule.
4. **Material risk / stop:** a specific, credible, current source plus evidence of a material unresolved barrier may warrant BLOCKED. State the exact observed fact, source, scope, and human escalation path. Do not label an issue BLOCKED merely because evidence is missing or a reviewer is uncertain.
5. **Human review:** legal interpretation, high-impact decisions, policy ambiguity, and any recommendation to change a live account or customer-facing flow require qualified human review. The checklist itself never takes action.
6. **Overall rating:** apply the worst-flag rule in `rating-rules.md`; no numeric score or averaging.

## Gate outcomes

- **CLEAR:** only when in-scope items are supported by sufficient evidence and no unresolved material concern is identified. This is not a certification or guarantee.
- **CONDITIONAL:** a material question is unresolved, evidence is incomplete or conflicting, or a stated condition must be met before relying on the finding.
- **AT RISK:** evidence indicates a material exposure or likely issue needing prompt human attention, but the available basis does not justify a BLOCKED conclusion.
- **BLOCKED:** a verified, in-scope hard stop is supported by current authoritative evidence and a human has confirmed it. The report must explain the precise basis; use sparingly.

If no evidence has been reviewed, do not fill the gap with assumptions. Report the work as Not assessed or stop for incomplete scope.
