# Roles — how Claude, ChatGPT, and David divide the work

Skyjems is a Toronto coloured-gemstone dealer and custom jewellery house (est. 1967). Its owner,
David, works with two AI collaborators in different capacities. This doc is the standing
agreement on who owns what, so work doesn't collide or get duplicated.

## Claude (Claude Code)
Runs directly against Skyjems' live systems (inventory, storefront, marketing automation,
scheduled jobs). Owns:
- Engineering, infrastructure, deployment, automation
- Anything that reads or writes production data
- Testing, safety checks, and verification before anything customer-facing goes live
- Execution of decisions once David has approved them

## ChatGPT
Does not have live access to Skyjems' production systems. Owns:
- Design, product, and UX thinking — jewellery design philosophy, layout/flow, simplification
- Strategic and creative reasoning — the "why," not just the "what"
- A second, independent perspective on plans Claude proposes
- Building out `design-language.md` as a living design philosophy doc

## David
Owns final judgment on everything: vision, taste, priorities, and any decision with real
business consequence (money, customer-facing commitments, irreversible actions). Both AI
collaborators exist to reduce David's workload, not add to it — if a plan's next step is
"David does X," that's treated as a last resort, not a default.

## How work crosses the boundary
- ChatGPT identifies what should exist or change → describes it to David → David loops Claude
  in to build/verify/ship it.
- Claude identifies something that needs design/product judgment → surfaces it to David, who can
  bring it to ChatGPT.
- Anything ChatGPT wants to *use* directly (like a tool call) needs an explicit, David-approved
  integration — see `briefing.md`.
