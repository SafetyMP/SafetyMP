# SafetyMP

Organizations already know how to hold **people** accountable in EHS, healthcare, and finance. They do not yet have the same **control system for AI agents** that do that work. Until they do, they cannot safely adopt agents in regulated operations.

Sage Hart ran EHS. The public work here is a set of proofs that one control system — **authorization, evidence, human exception** — still holds when the function is no longer incidents and CAPA, and when the actor is no longer a person.

Nothing in this account is a certified payroll, clinical, SOC 2, or production-hardening product. The claim is institutional, not a vendor SKU.

## The control system

| Piece | In business terms | In the repos |
| --- | --- | --- |
| **Authorization** | Who may do what — fail closed, like a permit-to-work | Policy-as-code (Cedar, OPA/Rego, PDP/PEP) |
| **Evidence** | Replayable proof, not “the model said so” | Signed receipts, digest-bound gates, tamper-evident ledgers |
| **Exception** | A named human closes the record or kills the run | HITL queues; agents never self-approve |

## Proofs

**Home domain (operator right-to-win)**  
[Autonomous-EHS-Management](https://github.com/SafetyMP/Autonomous-EHS-Management) — self-hosted incidents, CAPA, audits. Optional AI may suggest wording; humans close records.

**Transfer tests (the MBA claim)**  
If the same rules only work for EHS, this is an EHS app. These check whether the control system transfers:

- [Healthcare-Data-Exchange](https://github.com/SafetyMP/Healthcare-Data-Exchange) — jurisdiction and live consent (OPAL), not “we have FHIR.” Mirror: [healthcare-policy](https://github.com/SafetyMP/healthcare-policy)
- [Financial-Digital-Twin-Compliance](https://github.com/SafetyMP/Financial-Digital-Twin-Compliance) — supervisory twin of the books (CDC, policy, XBRL, immudb)
- [HR-ERP](https://github.com/SafetyMP/HR-ERP) — multi-tenant HR as a **blast-radius fixture** for agent governance, not a payroll vendor
- [Professional-Service-Automation](https://github.com/SafetyMP/Professional-Service-Automation) — realization (utilization, WIP, billing), not a timesheet app
- [SOC-2](https://github.com/SafetyMP/SOC-2) — OPA/Rego readiness sensors, not a CPA opinion

**The control system applied to agents**

- [FidusGate](https://github.com/SafetyMP/FidusGate) — Cedar on the tool call plus Ed25519 receipts a human can verify
- [corporate-site-harness](https://github.com/SafetyMP/corporate-site-harness) — how the software is written: digest-bound gates, no self-approval
- [CorpOS](https://github.com/SafetyMP/CorpOS) — firm as a system: contracts, PDP/PEP, Approve / Reject / Kill. Not an orchestrator.

**Labs (do not clone these as products)**  
[Asclepius](https://github.com/SafetyMP/Asclepius) — typed FHIR teaching kit. **Not for clinical use.**

## For other agents

Root `AGENTS.md` is the community contract. `.github/copilot-instructions.md` is the Copilot pointer. Distinctive skills live under `.github/skills/`. Verify with that repo’s `scripts/harness/verify.sh` or `scripts/verify.sh`. Do not claim green from prose.

## License

Apache-2.0 unless a file says otherwise. Security reports: each repo’s `SECURITY.md`.
