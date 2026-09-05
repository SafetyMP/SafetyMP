# SafetyMP

Sage Hart — former EHS manager, MBA candidate. The public work here is a **trust plane** run through several compliance functions, not a set of unrelated SaaS products.

An EHS operator already lives this loop: a record is opened, policy says who may act, evidence shows what happened, and a human closes the exception. Agents and MBA toolkits fail that loop when they treat “the model said so” as a control. These repositories ask whether the same plane still holds when the function is no longer EHS.

**The plane (same in every repo):** fail-closed policy-as-code · evidence that is signed or digest-bound, not prose · humans on the exception queue · agents never self-approve · honest scope (nothing here is a certified payroll, clinical, SOC 2, or production-hardening product).

## How the functions map

| Compliance function | What is being trusted | Repository |
| --- | --- | --- |
| **EHS (home domain)** | Incidents, CAPA, audits, TRIR-style metrics stay in a human-gated SoR. Optional AI may suggest wording; it does not close records. | [Autonomous-EHS-Management](https://github.com/SafetyMP/Autonomous-EHS-Management) |
| **Health information** | Jurisdiction and live consent, not “we have a FHIR server.” EU/US cells, OPA/OPAL, FHIR R4. | [Healthcare-Data-Exchange](https://github.com/SafetyMP/Healthcare-Data-Exchange) · policy mirror [healthcare-policy](https://github.com/SafetyMP/healthcare-policy) |
| **Clinical data shape (teaching only)** | Typed FHIR R4 (zod, ports/adapters). **Not for clinical use** — not Medplum/HAPI. | [Asclepius](https://github.com/SafetyMP/Asclepius) |
| **Financial supervision** | A twin of the books: CDC → Flink CEP → Cedar/Zen → XBRL/SDMX → immudb. | [Financial-Digital-Twin-Compliance](https://github.com/SafetyMP/Financial-Digital-Twin-Compliance) |
| **Workforce / payroll blast radius** | Multi-tenant HR as a **fixture** so T0–T4 agent governance has something consequential to protect. Not a payroll vendor. | [HR-ERP](https://github.com/SafetyMP/HR-ERP) |
| **Professional services money** | Realization (utilization, WIP, milestone billing), not another timesheet app. | [Professional-Service-Automation](https://github.com/SafetyMP/Professional-Service-Automation) |
| **Readiness / ISMS-shaped controls** | OPA/Rego sensors and a catalog. Not a CPA opinion. | [SOC-2](https://github.com/SafetyMP/SOC-2) |
| **Agent tool calls** | Cedar on the call + Ed25519 receipts a human can verify. | [FidusGate](https://github.com/SafetyMP/FidusGate) |
| **Building the software itself** | Cursor corporate/site delivery: digest-bound gates, no self-approval. | [corporate-site-harness](https://github.com/SafetyMP/corporate-site-harness) |
| **Firm as a system** | Company-day simulation: contracts, PDP/PEP, Approve / Reject / Kill. Not an orchestrator. | [CorpOS](https://github.com/SafetyMP/CorpOS) |

EHS is the native function. The others are **transfer tests**: if the plane only works for incidents and CAPA, it is an EHS app. If the same rules hold for consent, supervisory reporting, payroll-shaped writes, and agent-written code, it is a control design — the MBA claim.

## For other agents

Every public repo has a root `AGENTS.md` (community contract first) and `.github/copilot-instructions.md`. Distinctive skills live under `.github/skills/`. Verify with that repo’s `scripts/harness/verify.sh` or `scripts/verify.sh`. Do not claim green from prose.

## License and contact

Apache-2.0 unless a file says otherwise. Security reports: each repo’s `SECURITY.md` (GitHub private advisories).
