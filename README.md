# AI Compliance Store Review — Draft Pack

> **DRAFT ONLY — NOT APPROVED, NOT ADOPTED.** This is a working scaffold, not a compliance certification, legal opinion, or guarantee of platform acceptance. No real store has been graded. Do not use this pack to make a live decision until its open decisions and review gates are approved.

## Purpose

A human-led checklist scaffold for reviewing public storefront evidence across payment-provider, Meta, paid-access, and other compliance topics. It is designed to organize evidence and flag questions for qualified review; it does not determine whether a business is legally compliant or whether a platform will approve an account, ad, or transaction.

## Current decisions (all unresolved)

| Decision | Status |
|---|---|
| Final repository name | TBD |
| Public or private repository | TBD |
| License | TBD — intentionally no `LICENSE` file is included |
| First store to grade | TBD — no real store should be graded from this draft |
| Whether this tool itself is paid-gated | TBD — do not enable a tool paywall or charge for tool access |
| Approval/adoption of this draft | Not approved; draft only |

A ZIP is provided for local review. Creating the archive does not create a GitHub repository or authorize a push, publication, or adoption.

The landing page includes voluntary third-party supporter links. These do not unlock the review tool or settle its paid-access decision. Third-party providers may accept real payments if their checkout is used; verify the current amount, renewal terms, and disclosures before any public launch.

## Draft review model

- **Layer A — Stripe (A1–A8):** public storefront and payment-related evidence to inspect; not an interpretation of Stripe's current rules.
- **Layer B — Meta (B1–B9):** public storefront, advertising, commerce, and data-use evidence to inspect; not an interpretation of Meta's current rules.
- **Layer C — Paid gate (C1–C2):** unresolved product-access and disclosure decisions. The gate is not configured by this pack.
- **Layer D — Other compliance (D1–D6):** jurisdiction-dependent consumer, privacy, product, accessibility, and sector-specific prompts.
- **Gap-test additions:** a structured place to record omissions discovered during a fictional-only review.

## Build order and safe use

1. Resolve the decisions above, including jurisdiction and repository/license choices.
2. Review and approve the disclaimer, evidence rules, classification gates, ratings, and checklist wording.
3. Use a **fictional-store self-test only** to test the workflow; clearly label all invented facts as fictional.
4. Do not enter customer data, credentials, payment details, account identifiers, private URLs, or production logs in this repository.
5. Grade a real store only after the owner explicitly authorizes that separate task and the jurisdiction, scope, and evidence-handling rules are settled.
6. Publish to GitHub only after an explicit one-action override for the exact repository and visibility. No publication is authorized by this draft or ZIP request.

## Repository layout

```text
ai-compliance/
├── index.html
├── private-communities.html
├── README.md
├── CHANGELOG.md
├── WEB-HOSTING.md
├── assets/
│   ├── favicon.svg
│   └── promo-*.png
├── docs/
│   ├── jurisdiction-prompt.md
│   ├── evidence-guide.md
│   ├── classification-gates.md
│   ├── rating-rules.md
│   └── glossary.md
├── checklists/
│   ├── layer-a-stripe.md
│   ├── layer-b-meta.md
│   ├── layer-c-paid-gate.md
│   ├── layer-d-other-compliance.md
│   └── gap-test-additions.md
├── templates/
│   ├── report-template.md
│   └── evidence-snapshot.md
└── .gitignore
```

`index.html` is a build-free, static landing page with a relative-path favicon and promotional illustrations. See `WEB-HOSTING.md` for GitHub Pages and Cloudflare Pages/Workers compatibility notes. Adding the page does not change the draft's approval or publication status.

`private-communities.html` is a separate draft access page for the private Matrix room. Its age checkbox and country selection are self-attestations only; they do not verify age, identity, or location and are not reliable access controls.

`LICENSE` is deliberately absent pending a decision. Until the owner selects a license, do not represent this material as open-source or grant reuse rights. `TBD` is not approval.

## How to use a checklist (draft)

For each item, record a bounded observation, the evidence reference, the date checked, and one of the four report ratings defined in `docs/rating-rules.md`. Mark items **Not assessed** when evidence is missing. Do not infer a pass from silence, a third-party badge, or a single screenshot. Verify current official platform and legal sources at the time of any future review.

## Disclaimer

This draft is informational workflow material only. It is not legal, tax, privacy, security, payments, or advertising advice; it does not create a professional relationship; and it cannot guarantee legal compliance, platform eligibility, account standing, ad approval, or payment processing. Laws, regulator guidance, and platform policies vary by location and change over time. Obtain qualified advice and consult current official sources before relying on any finding. A human reviewer must verify evidence and approve any conclusion.
