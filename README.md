# SafetyMP

Public Apache-2.0 **systems of record** you can fork, plus one evidence-gated Cursor factory. Agents propose. Digests and humans decide. Nothing here is a certified payroll, clinical, SOC 2, or production-hardening product.

## Start here

| If you need | Repository |
| --- | --- |
| Self-hosted EHS incidents, CAPA, audits | [Autonomous-EHS-Management](https://github.com/SafetyMP/Autonomous-EHS-Management) |
| Federated HIE (EU/US cells, OPAL consent, FHIR R4) | [Healthcare-Data-Exchange](https://github.com/SafetyMP/Healthcare-Data-Exchange) |
| Supervisory financial-compliance digital twin | [Financial-Digital-Twin-Compliance](https://github.com/SafetyMP/Financial-Digital-Twin-Compliance) |
| Cedar gates + Ed25519 receipts for MCP tool calls | [FidusGate](https://github.com/SafetyMP/FidusGate) |
| Digest-bound Cursor corporate/site delivery | [corporate-site-harness](https://github.com/SafetyMP/corporate-site-harness) |
| Company-day simulation (firm model, contracts, PDP/PEP) | [CorpOS](https://github.com/SafetyMP/CorpOS) |

## Teaching kits (not category products)

These repos keep an honest fixture domain so you can study a pattern. They are not replacements for Kimai, ERPNext, Medplum, or a CPA opinion.

- [Professional-Service-Automation](https://github.com/SafetyMP/Professional-Service-Automation) — consulting **realization** (utilization, WIP, milestone billing), not another timesheet app
- [HR-ERP](https://github.com/SafetyMP/HR-ERP) — multi-tenant HR **scaffold for agent governance** (T0–T4), not a payroll vendor
- [Asclepius](https://github.com/SafetyMP/Asclepius) — typed FHIR R4 **ports/adapters** teaching kit. **Not for clinical use**
- [SOC-2](https://github.com/SafetyMP/SOC-2) — OPA/Rego **readiness sensors**, not a certification
- [healthcare-policy](https://github.com/SafetyMP/healthcare-policy) — OPAL **mirror** of Healthcare-Data-Exchange; do not edit Rego there

## For other agents

Every public repo has a root `AGENTS.md` (community contract first) and `.github/copilot-instructions.md`. Distinctive skills live under `.github/skills/`. Verify with that repo’s `scripts/harness/verify.sh` or `scripts/verify.sh` — do not claim green from prose.

## License and contact

Apache-2.0 unless a file says otherwise. Security reports: each repo’s `SECURITY.md` (GitHub private advisories).
