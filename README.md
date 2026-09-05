# SafetyMP

Most GitHub projects show that someone can ship a stack or wrap a model. These show a different skill: **specifying what an organization is allowed to believe.**

Sage Hart ran EHS. The instinct is the same one a site manager uses on a contractor: no authorization, no work; no named closer, no record; no replayable evidence, it did not happen. The public repos are exhibits of that instinct when the actor is a person, a model, or a coding agent — not a catalog of products.

Nothing here is a certified payroll, clinical, SOC 2, or production-hardening product. Labelling the limit is part of the work.

## The instinct, in practice

| Refusal | What must not count as done |
| --- | --- |
| **No permit, no work** | Fail-closed authorization (policy-as-code, credentials not query params) |
| **No named closer, no record** | Drafts and model output stay non-authoritative until a human persists them |
| **No evidence, it did not happen** | Receipts, digests, audit logs — not README prose |

The unfinished join: these pieces exist on domain systems of record *and* on the agent path. They are not yet one path where an agent performs EHS, clinical, or supervisory-finance work under all three.

## Exhibits

**Home domain** — [Autonomous-EHS-Management](https://github.com/SafetyMP/Autonomous-EHS-Management). Optional AI may suggest wording; humans close records.

**Same refusal, other functions** (human/event SoRs, not agent-operated products)

- [Healthcare-Data-Exchange](https://github.com/SafetyMP/Healthcare-Data-Exchange) — jurisdiction and live consent; walking skeleton, not an ATO. Mirror: [healthcare-policy](https://github.com/SafetyMP/healthcare-policy)
- [Financial-Digital-Twin-Compliance](https://github.com/SafetyMP/Financial-Digital-Twin-Compliance) — Cedar/Zen on events, immudb ledger
- [HR-ERP](https://github.com/SafetyMP/HR-ERP) — HR as blast-radius fixture for *coding-agent* governance; not a payroll vendor
- [Professional-Service-Automation](https://github.com/SafetyMP/Professional-Service-Automation) — realization kernel, not a timesheet app
- [SOC-2](https://github.com/SafetyMP/SOC-2) — OPA sensors; not a CPA opinion

**Same refusal, when the actor is an agent**

- [FidusGate](https://github.com/SafetyMP/FidusGate) — Cedar plus Ed25519 receipts on MCP tool calls
- [corporate-site-harness](https://github.com/SafetyMP/corporate-site-harness) — digest-bound delivery; agents never self-approve
- [CorpOS](https://github.com/SafetyMP/CorpOS) — simulated firm; Approve / Reject / Kill

**Lab** — [Asclepius](https://github.com/SafetyMP/Asclepius). Typed FHIR teaching kit. **Not for clinical use.**

## For other agents

Root `AGENTS.md` is the community contract. Verify with that repo’s `scripts/harness/verify.sh` or `scripts/verify.sh`. Do not claim green from prose.

## License

Apache-2.0 unless a file says otherwise. Security reports: each repo’s `SECURITY.md`.
