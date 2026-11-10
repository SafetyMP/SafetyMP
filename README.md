# Sage Hart | SafetyMP

**Reliable, sustainable AI operations through effective risk management.**

The next challenge for organizations isn't simply adopting AI. It's making AI dependable enough to operate at scale. As agents make decisions and act across systems, risk becomes more dynamic. Sustainable adoption requires clear ownership, controls that work inside workflows, and evidence that systems behave as intended.

My experience across Amazon, AB InBev, SGS, and chemical manufacturing shaped a practical view of reliability: define the objective, identify the constraints, establish accountability, build the mechanism, and test whether it works.

**My thesis: manage risk without sacrificing innovation.** The objective isn't to eliminate uncertainty. It's to understand failure modes, contain harmful outcomes, and maintain the flexibility to adapt and compete.

SafetyMP is where I build in public at the intersection of **enterprise operations, AI, and risk**. These repositories explore concrete mechanisms, not claims of production readiness.

## Explore by operating challenge

| Operating question | Research and reference projects |
| --- | --- |
| **What can go wrong when agents collaborate?** | [Agentic Process Safety (APS)](https://github.com/SafetyMP/Agentic-Process-Safety) — HAZOP-style analysis, simulated agent workflows, and proposed controls |
| **Who or what is authorized to act?** | [FidusGate](https://github.com/SafetyMP/FidusGate) — MCP tool-call policy decisions and signed receipts · [CorpOS](https://github.com/SafetyMP/CorpOS) — simulated handoffs and human approvals |
| **What evidence should be required before work advances?** | [Corporate/Site Harness](https://github.com/SafetyMP/corporate-site-harness) — digest-bound verification and approval gates for agent-assisted software delivery |
| **How do operations retain accountability?** | [Autonomous EHS Management](https://github.com/SafetyMP/Autonomous-EHS-Management) — incident records and human-verified corrective actions · [Healthcare data sandbox](https://github.com/SafetyMP/Healthcare-Data-Exchange) · [Financial compliance reference](https://github.com/SafetyMP/Financial-Digital-Twin-Compliance) |
| **How do we detect failures across system boundaries?** | [Commerce Reliability Kit](https://github.com/SafetyMP/commerce-reliability-kit) — reproducible order, fulfillment, and inventory integration tests · [Browser demo](https://safetymp.github.io/commerce-reliability-kit/) |

## Start here

- **Agent risk:** [Agentic Process Safety](https://github.com/SafetyMP/Agentic-Process-Safety) traces simulated agent decisions from hazards to proposed controls and test evidence. Research sandbox; not a safety certification or production protection.
- **Decision controls:** [FidusGate](https://github.com/SafetyMP/FidusGate) demonstrates MCP authorization and signed receipts. The Cedar daemon must be started separately; this is not a production security product.
- **Operational accountability:** [Autonomous EHS Management](https://github.com/SafetyMP/Autonomous-EHS-Management) lets you record an incident, move a corrective and preventive action (CAPA) through verification, and inspect TRIR reporting. Optional AI suggests wording; a person closes the record. Not an OSHA filing tool. **This is the repository to clone for an operational workflow.**

## Reference implementations and limitations

- [Commerce Reliability Kit](https://github.com/SafetyMP/commerce-reliability-kit) — order, fulfillment, and inventory integration testing for agencies, connector engineers, warehouse and fulfillment software teams, and merchant technical teams. Reproduce a failure, inspect evidence, and compare faulty and corrected behavior. Early Node CLI/library with 24 synthetic scenarios; [try the separate six-fixture browser demo](https://safetymp.github.io/commerce-reliability-kit/). No merchant accounts are connected, and demo outcomes do not validate a production integration.
- [Agentic-Process-Safety (APS)](https://github.com/SafetyMP/Agentic-Process-Safety) — deterministic hazard and operability (HAZOP) screening for AI agent swarms, a simulated procurement workflow and an interactive browser explorer. Research sandbox with unverified hazards and proposed controls. No real purchases, safety certification or production protection.
- [FidusGate](https://github.com/SafetyMP/FidusGate) — a Model Context Protocol (MCP) tool call that records a decision and an Ed25519 receipt. `npm run dev` does not start the Cedar daemon. A down daemon denies the call. Not a production security product.
- [CorpOS](https://github.com/SafetyMP/CorpOS) — one scripted company day. Not an agent framework and not production SaaS.
- [corporate-site-harness](https://github.com/SafetyMP/corporate-site-harness) — evidence-gated Cursor delivery. Not a production governance product.
- [HR-ERP](https://github.com/SafetyMP/HR-ERP) — multi-tenant fixture for agent-governance tests. Not a certified payroll product.
- [Professional-Service-Automation](https://github.com/SafetyMP/Professional-Service-Automation) — consulting billing sketch. Not a time-tracker replacement.
- [Financial-Digital-Twin-Compliance](https://github.com/SafetyMP/Financial-Digital-Twin-Compliance) — one mock payment through Debezium, a per-record Flink streaming job, Cedar, and immudb. Not Flink CEP, XBRL, SDMX, or a core-banking system.
- [Healthcare-Data-Exchange](https://github.com/SafetyMP/Healthcare-Data-Exchange) — one Compose stack. A synthetic FHIR R4 Patient is read from an EU or US HAPI cell only after a per-cell bearer passes OPA. Not a health-information exchange. Policy edits belong in this repository.
- [healthcare-policy](https://github.com/SafetyMP/healthcare-policy) — OPAL mirror of Healthcare-Data-Exchange. Do not edit Rego here.
- [Asclepius](https://github.com/SafetyMP/Asclepius) — nine-resource FHIR teaching kit. Not for clinical use. Not Medplum or HAPI.
- [SOC-2](https://github.com/SafetyMP/SOC-2) — small Open Policy Agent (OPA) sensor pack. Not a certification and not a claim of one.

The application repositories are Apache-2.0. This profile is too: [LICENSE](LICENSE). It has no application code.

Product changes belong on the product repository ([Contributing](CONTRIBUTING.md)). Vulnerability reports belong on the product repository ([Security](SECURITY.md)).

LinkedIn: [Sage Hart](https://www.linkedin.com/in/sage-hart-csp)
