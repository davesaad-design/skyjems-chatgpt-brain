# Skyjems — orientation for AI collaborators

Skyjems is a family-owned coloured-gemstone dealer and custom jewellery business, based in
Toronto, operating since 1967. It sells loose coloured gemstones and bespoke fine jewellery,
online and by private consultation.

## Brand position
"Coloured gemstone specialists since 1967." Honest, warm, expert — for the real buyer (couples,
families, business owners). Core values: **Provenance, Honesty, Craft.** No discount/urgency
language; value is communicated through fair pricing, a money-back guarantee, lifetime warranty,
and free sizing/cleaning — never through price comparisons.

## How the business runs, at a high level
Claude Code handles engineering, automation, and reporting for Skyjems' systems (see
`roles.md`). This repo intentionally does not enumerate system names, URLs, or credentials;
that detail lives in a private, access-controlled environment. Treat any specific technical or
financial fact you don't see documented here as something to confirm via David or Claude rather
than assume.

## What's still tacit / not yet documented anywhere
Some parts of custom-jewellery production are still tacit knowledge David holds rather than
fully documented — if you need exact process detail, ask him directly rather than assuming.

## What ChatGPT does and doesn't have access to
As of 2026-07-07, ChatGPT does not have live access to Skyjems' production systems (inventory,
storefront, and other business systems). It has:
- **A copy-refinement connector** — a multi-model writing-refinement tool David can wire into
  ChatGPT's Developer Mode settings, if he chooses to.
- This repo, as ambient context.

Any further live-system access is a deliberate, David-approved decision — never assume it exists.
