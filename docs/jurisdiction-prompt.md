# Jurisdiction and scope prompt (draft)

> **Draft only.** Complete this before any real-store review. If scope cannot be established, stop before assigning a rating.

## Reviewer intake

- Review reference (non-identifying code): `[REVIEW-REF]`
- Business/store display name (only if authorized and necessary): `[NAME OR OMIT]`
- Public storefront URL (omit query strings, tokens, and private paths): `[PUBLIC URL]`
- Review date and time zone: `[DATE / TIME ZONE]`
- Store operator's country/region, if known: `[COUNTRY / REGION / UNKNOWN]`
- Countries/regions where customers are actively targeted or served: `[LIST / UNKNOWN]`
- Product/service category and any age or sector restrictions: `[DESCRIPTION / UNKNOWN]`
- Sales channels in scope (web, app, social commerce, ads): `[LIST]`
- Review scope and exclusions: `[SCOPE]`
- Evidence access limits or consent restrictions: `[LIMITS]`
- Human reviewer and escalation contact/role (no personal contact details in public repo): `[ROLE]`

Do not guess a jurisdiction from a domain suffix, language, currency, shipping destination selector, or IP-derived location. Distinguish where the business is established, where it targets customers, and where it fulfills orders. Record unknowns explicitly.

## Prompt for a future reviewer

> Review only the authorized, in-scope public evidence and the supplied jurisdiction facts. First identify missing or ambiguous scope. Do not infer legal compliance, platform approval, or absence of a policy violation from missing evidence. For each checklist item, cite the evidence reference and observation date, separate direct observation from inference, and list the current official source that a qualified human must verify. If the jurisdiction or material facts are unknown, mark the item Not assessed or Conditional as appropriate and state what would resolve the uncertainty. Do not calculate a numeric score. Apply the worst-flag rule in `rating-rules.md`. Do not store personal data, credentials, payment data, or account identifiers in the report or repository. Escalate legal interpretation and any proposed live action to a qualified human.

## Scope stop conditions

Stop and report **NOT RATED — SCOPE INCOMPLETE** when the store or review scope cannot be identified, authorization to inspect is unclear, or the jurisdictions material to the question are unknown. This is a workflow stop label, not a fifth rating. Do not proceed to a real-store grade until the missing scope is resolved.
