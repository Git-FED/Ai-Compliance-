# Evidence guide (draft)

> **Draft only.** This guide favors minimal, verifiable evidence and does not authorize collection of private records.

## Evidence hierarchy

Prefer, in order where relevant: (1) current official law/regulator or platform documentation for the question; (2) directly observable, public storefront/ad/checkout text; (3) a dated capture of that public evidence; and (4) a clearly labeled reviewer note. A platform help page is evidence of platform guidance, not proof that a store complies. A public page is evidence of what was visible at the capture time, not proof of actual operations.

## Record only what is needed

For each evidence item, use `templates/evidence-snapshot.md`. Capture the source URL without tracking parameters, capture date/time and time zone, region/locale if relevant, the relevant page or section, a short factual excerpt or observation, and a local evidence reference. Keep the statement precise: “refund window shown as 30 days on page X” is preferable to “refund policy compliant.”

Do not collect or commit customer records, private dashboards, credentials, payment-card data, API keys, authentication tokens, order records, personal identifiers, unredacted screenshots, browser HAR files, or production logs. Do not bypass access controls or consent requirements. If such material is necessary for a separate authorized review, use an approved secure system outside this repository and cite only a non-sensitive reference.

## Source freshness and confidence

- Record the date checked; policies and rules can change.
- Prefer the source's effective date and applicable region. If either is unclear, say so.
- Distinguish **observed**, **reported**, **inferred**, and **not verified** facts.
- Use a second independent source for high-impact or ambiguous issues when practical.
- If evidence conflicts, preserve the conflict and mark the result Conditional or escalate; do not select the more convenient version.
- A missing page or failed capture is not proof of non-compliance. Record it as unavailable and mark Not assessed or Conditional.

## Citation format

`[E-01] Source title — publisher, region/locale, effective date if shown, URL (without query/token), accessed YYYY-MM-DD, observation: ...`

Use fictional URLs and invented facts only in the fictional self-test; label them **FICTIONAL — TEST DATA**. Do not include actual customer or merchant identifiers in evidence IDs.
