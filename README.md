# Sage Hart | SafetyMP

**Reliable, sustainable AI operations through effective risk management.**

I build open-source tools at the intersection of enterprise operations, AI, and risk. My experience across Amazon, AB InBev, SGS, and chemical manufacturing shapes a practical approach: define the objective, establish accountability, build the controls, and test whether they work.

**My thesis: manage risk without sacrificing innovation.** These projects explore how people can understand automated decisions, inspect evidence, and retain authority over consequential actions.

[Explore the projects](#featured-projects) · [Choose a demo by the decision you face](docs/demo-field-guide.md) · [More of the portfolio](#more-of-the-portfolio) · [Connect on LinkedIn](https://www.linkedin.com/in/sage-hart-csp)

## Featured projects

### Agentic Process Safety — investigate agent failure modes

Compare the same agent request under different control conditions, trace why a decision changes, and form an evidence-backed position. The guided app connects procurement cases, HAZOP analysis, proposed controls, and recorded synthetic experiments.

**Research and learning workspace.** Browser comparisons illustrate a fixed model; hazards remain unverified and controls proposed. No real purchases or safety certification.

[Explore the app](https://safetymp.github.io/Agentic-Process-Safety/) · [Source](https://github.com/SafetyMP/Agentic-Process-Safety) · [Investigation guide](https://github.com/SafetyMP/Agentic-Process-Safety/blob/main/docs/USER_GUIDE.md)

### Autonomous EHS Management — connect incidents to accountable action

Self-hosted corporate EHS software for incident investigation, corrective and preventive actions (CAPA), approvals, and evidence across sites. Explore the corporate overview and incident-to-CAPA journey, or run the full application locally.

**Application with a synthetic, read-only walkthrough.** People retain approval and closure authority; module maturity varies. The demo does not validate a deployment or establish regulatory compliance.

[Explore the walkthrough](https://safetymp.github.io/Autonomous-EHS-Management/) · [Source](https://github.com/SafetyMP/Autonomous-EHS-Management) · [Self-hosting guide](https://github.com/SafetyMP/Autonomous-EHS-Management/blob/main/docs/self-host-quickstart.md)

### FidusGate — understand tool-call decisions and verify receipts

A Model Context Protocol (MCP) policy gateway and operator console combining Cedar authorization with signed decision receipts. Inspect allow/deny reasons, explore policy scenarios, and verify receipt signatures.

**Reference implementation.** Public scenarios are synthetic; browser signature checks are real, but do not prove tool execution or issuer trust. Connected operations require the separate development gateway.

[Try the demo](https://safetymp.github.io/FidusGate/) · [Source](https://github.com/SafetyMP/FidusGate) · [Local setup](https://github.com/SafetyMP/FidusGate/blob/main/docs/getting-started.md)

### Financial Digital Twin — review financial monitoring issues

A governance workspace for following alerts to supporting evidence, recording acknowledgements or escalations, and revisiting review history. The connected development workspace integrates alert and audit services with persistent reviews.

**Synthetic public demo and separate connected development application.** Demo reviews stay in the browser. Connected mode uses a configured development identity; this is not a production banking or regulatory filing system.

[Try the demo](https://safetymp.github.io/Financial-Digital-Twin-Compliance/) · [Source](https://github.com/SafetyMP/Financial-Digital-Twin-Compliance) · [Connected workspace](https://github.com/SafetyMP/Financial-Digital-Twin-Compliance/blob/main/docs/governance-integration.md)

### Commerce Reliability Kit — reproduce integration failures

Investigate order, fulfillment, and inventory discrepancies. Compare faulty and corrected behavior against the same evidence, inspect assertions, and export reports. A Node CLI and library support scenarios and normalized captures; the browser demo has its own evaluator.

**Early toolkit with synthetic demonstrations.** Missing evidence can produce an inconclusive result. No merchant accounts are connected and demo outcomes do not validate a production integration.

[Try the demo](https://safetymp.github.io/commerce-reliability-kit/) · [Source](https://github.com/SafetyMP/commerce-reliability-kit) · [CLI and library guide](https://github.com/SafetyMP/commerce-reliability-kit/blob/main/docs/cli-guide.md)

## More of the portfolio

| Project | What you can explore | Entry point |
| --- | --- | --- |
| [SOC-2](https://github.com/SafetyMP/SOC-2) | Local GitHub readiness assessment, finding review, next steps, and export. Three repository checks; not a complete SOC 2 assessment or certification. | [Synthetic demo](https://safetymp.github.io/SOC-2/) · [Local assessment](https://github.com/SafetyMP/SOC-2/blob/main/docs/local-github-assessment.md) |
| [Healthcare Data Exchange](https://github.com/SafetyMP/Healthcare-Data-Exchange) | Guided consent, care-team, and regional-access scenarios, with a separate FHIR/OPA/OPAL backend reference. Synthetic data; no clinical use. | [Guided demo](https://safetymp.github.io/Healthcare-Data-Exchange/) |
| [Asclepius](https://github.com/SafetyMP/Asclepius) | Fictional visit and referral journeys, linked health records, and a validation lab. Educational FHIR subset; no clinical use or full conformance claim. | [Learning app](https://safetymp.github.io/Asclepius/) |
| [HR-ERP](https://github.com/SafetyMP/HR-ERP) | Multi-tenant HR fixture for agent governance, tenant isolation, and evidence gates. Synthetic employee/HR demo; not a production HRIS or certified payroll product. | [Browser demo](https://safetymp.github.io/HR-ERP/) |
| [Professional Service Automation](https://github.com/SafetyMP/Professional-Service-Automation) | Consulting realization: approved time, work in progress, draft/issued invoices, and project margin. A scoped reference application. | [Source and setup](https://github.com/SafetyMP/Professional-Service-Automation#quick-start) |
| [CorpOS](https://github.com/SafetyMP/CorpOS) | A scripted company day with agent handoffs, tool controls, and human approval. A simulation and reference architecture. | [Local demo](https://github.com/SafetyMP/CorpOS#demo) |

**Supporting and historical repositories:** [healthcare-policy](https://github.com/SafetyMP/healthcare-policy) is the OPAL policy mirror; make policy changes in Healthcare Data Exchange. [Corporate/Site Harness](https://github.com/SafetyMP/corporate-site-harness) is an **archived** reference for digest-bound software-delivery gates and human approval.

## How I approach the work

- **Make the operating problem concrete:** a stale approval, an unresolved corrective action, an incomplete shipment, or an access decision.
- **Keep evidence inspectable:** connect decisions to records, policy, tests, and explicit uncertainty.
- **Build usable review workflows:** help people understand a result and decide what should happen next.

The repositories span TypeScript/React interfaces, Python tooling, Go services, PostgreSQL, and policy-as-code with OPA/Rego and Cedar. Each project documents its own setup, architecture, checks, and limitations. A passing check supports its stated scope; it does not establish production readiness or certification.

## Connect and contribute

Connect with me on [LinkedIn](https://www.linkedin.com/in/sage-hart-csp). For project questions, bugs, and contributions, start with that repository's README and contribution guide. For profile corrections, see [Contributing](https://github.com/SafetyMP/SafetyMP/blob/main/CONTRIBUTING.md); report vulnerabilities through the affected project's [security policy](https://github.com/SafetyMP/SafetyMP/blob/main/SECURITY.md).

Portfolio reviewed **November 22, 2026**. [Source and maintenance notes](https://github.com/SafetyMP/SafetyMP/blob/main/docs/portfolio-sources.md) · [Profile license: Apache-2.0](https://github.com/SafetyMP/SafetyMP/blob/main/LICENSE). Each linked project retains its own license and third-party terms.
