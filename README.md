# Sage Hart | SafetyMP

**AI governance, agentic process safety and enterprise operations.**

I build public experiments in how organizations control AI agents, enforce authorization policies and preserve operational records. This portfolio covers HAZOP hazard analysis for multi-agent systems, policy gateways, evidence-gated software delivery, commerce integration testing, and systems of record for environmental health and safety (EHS), healthcare and finance.

These repositories are research and reference implementations. Each project documents its scope, evidence and limitations.

## Explore by topic

| Area | Projects |
| --- | --- |
| Agentic process safety and HAZOP hazard analysis | [Agentic Process Safety (APS)](https://github.com/SafetyMP/Agentic-Process-Safety) |
| AI agent governance, authorization and audit receipts | [FidusGate MCP policy gateway](https://github.com/SafetyMP/FidusGate) · [CorpOS company-day simulation](https://github.com/SafetyMP/CorpOS) |
| Evidence-gated agent-assisted software delivery | [Corporate/Site Harness](https://github.com/SafetyMP/corporate-site-harness) |
| Operational records and policy-as-code | [EHS incident and CAPA console](https://github.com/SafetyMP/Autonomous-EHS-Management) · [FHIR healthcare data sandbox](https://github.com/SafetyMP/Healthcare-Data-Exchange) · [Financial compliance reference](https://github.com/SafetyMP/Financial-Digital-Twin-Compliance) |
| Commerce integration reliability | [Commerce Reliability Kit](https://github.com/SafetyMP/commerce-reliability-kit) · [Synthetic browser demo](https://safetymp.github.io/commerce-reliability-kit/) |

## Start here

- [Autonomous-EHS-Management](https://github.com/SafetyMP/Autonomous-EHS-Management) — record an incident, walk a corrective and preventive action (CAPA) to verified, and read a total recordable incident rate (TRIR) that uses annual hours when the month grid is incomplete. Optional AI may suggest wording. A person closes the record. Not an OSHA filing tool. This is the repository to clone.

## Reference, not a product

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
