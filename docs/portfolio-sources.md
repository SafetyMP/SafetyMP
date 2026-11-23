# Portfolio source notes

## November 23, 2026

The [field guide](demo-field-guide.md) covers twelve interactive cases and one archived written exercise. Ten project sites have a published case and technical guide, including CorpOS. Professional Service Automation runs locally on its default branch. The healthcare-policy operator case shares the Healthcare Data Exchange implementation. The exchange’s published rule-publication trace covers one piece of that workflow. The operator’s decision about the receiving gateway appears in the review build.

APS is the published reference. The other eleven opening images come from their review builds. Each guide entry identifies the earlier case where a visitor can compare the published version. The short funding questions are proposed tests. Potential gains in time, accuracy or avoided delay have yet to be measured in a deployment. [Public repository inventory](https://github.com/SafetyMP?tab=repositories)

### Sources for distinguishing the work

- A referring clinic tracks a request and the specialist’s report. A study team uses information released for a particular purpose. The referral exercise concerns report receipt, while the disclosure exercise concerns fields leaving the gateway. [HL7 referral request](https://hl7.org/fhir/R4/servicerequest.html) · [CRISP research disclosure workflow](https://www.crisphealth.org/research/)
- An exchange operator needs evidence of what the receiver loaded. Rule publication and consent updates can arrive at different times. [OPA bundle management](https://www.openpolicyagent.org/docs/management-bundles) · [OPAL distribution design](https://docs.opal.ac/overview/design/)
- A merchant can compare ordered and remaining quantities at the fulfillment line. A project accountant instead reconciles work accepted and amounts already billed. [Shopify fulfillment quantities](https://shopify.dev/docs/api/admin-graphql/latest/objects/FulfillmentOrderLineItem) · [Microsoft project invoicing](https://learn.microsoft.com/en-us/dynamics365/project-operations/invoicing/post-project-invoices)
- The payments desk works against intraday deadlines. Independent risk monitors stressed liquidity over 30 days. [Basel Committee intraday monitoring](https://www.bis.org/publ/bcbs248.htm) · [Liquidity coverage ratio](https://www.bis.org/publ/bcbs238.htm)
- A safety action owner gathers evidence that controls work after installation. The platform incident lead coordinates people with distinct responsibilities and observations. [OSHA hazard prevention and control](https://www.osha.gov/safety-management/hazard-prevention) · [Google SRE incident response](https://sre.google/workbook/incident-response/)
- A customer assurance team answers evidence requests about releases. A tool-call investigator examines the authorization decision for a specific request. A release reviewer checks the identity of the artifact itself. [GitLab customer assurance process](https://handbook.gitlab.com/handbook/security/security-assurance/field-security/customer-security-assessment-process/) · [Cedar authorization](https://docs.cedarpolicy.com/auth/authorization.html) · [SLSA artifact provenance](https://slsa.dev/spec/v1.2/provenance)

## November 22, 2026

The public GitHub inventory contains 14 repositories. Eleven have their own demos, including APS. Nine of those projects use GitHub Pages. CorpOS and Professional Service Automation provide local applications. The remaining repositories are this profile, the healthcare policy mirror and the archived Corporate/Site Harness. The [demo field guide](demo-field-guide.md) connects those entry points to decisions a visitor can investigate. Its suggested pilot measures are hypotheses. Each project's published README describes the software available on its default branch. [Public repository inventory](https://github.com/SafetyMP?tab=repositories)

## November 14, 2026

The following notes document the earlier profile refresh.

## Scope and sources

The public GitHub inventory contained this profile plus the 13 repositories below. Descriptions were reconciled against published default-branch READMEs and linked implementation guides. Private repositories were excluded. Local work in other repositories was preserved.

| Repository README at review | Revision | GitHub status at review |
| --- | --- | --- |
| [Agentic-Process-Safety](https://github.com/SafetyMP/Agentic-Process-Safety/blob/0489da1b77680d8efeee74ba05f2a0b42a8811dc/README.md) | [`0489da1`](https://github.com/SafetyMP/Agentic-Process-Safety/commit/0489da1b77680d8efeee74ba05f2a0b42a8811dc) | Public |
| [Asclepius](https://github.com/SafetyMP/Asclepius/blob/6695d9ad1317f05fd5a755bd66a9af30f91d9210/README.md) | [`6695d9a`](https://github.com/SafetyMP/Asclepius/commit/6695d9ad1317f05fd5a755bd66a9af30f91d9210) | Public |
| [Autonomous-EHS-Management](https://github.com/SafetyMP/Autonomous-EHS-Management/blob/1237e148b550af6ab084a0f6f7a7927e48bef0cd/README.md) | [`1237e14`](https://github.com/SafetyMP/Autonomous-EHS-Management/commit/1237e148b550af6ab084a0f6f7a7927e48bef0cd) | Public |
| [CorpOS](https://github.com/SafetyMP/CorpOS/blob/05fb25558ffea8a42004e4d210e6ac5f163bc6ea/README.md) | [`05fb255`](https://github.com/SafetyMP/CorpOS/commit/05fb25558ffea8a42004e4d210e6ac5f163bc6ea) | Public |
| [FidusGate](https://github.com/SafetyMP/FidusGate/blob/825bb668c58b67911b8c51e5920f1006227ba12d/README.md) | [`825bb66`](https://github.com/SafetyMP/FidusGate/commit/825bb668c58b67911b8c51e5920f1006227ba12d) | Public |
| [Financial-Digital-Twin-Compliance](https://github.com/SafetyMP/Financial-Digital-Twin-Compliance/blob/4003b94487ebc59bbd63fbdf93b316572e4b093d/README.md) | [`4003b94`](https://github.com/SafetyMP/Financial-Digital-Twin-Compliance/commit/4003b94487ebc59bbd63fbdf93b316572e4b093d) | Public |
| [HR-ERP](https://github.com/SafetyMP/HR-ERP/blob/2a032d01b38f8ea249813dfeac5caf6922d509e3/README.md) | [`2a032d0`](https://github.com/SafetyMP/HR-ERP/commit/2a032d01b38f8ea249813dfeac5caf6922d509e3) | Public |
| [Healthcare-Data-Exchange](https://github.com/SafetyMP/Healthcare-Data-Exchange/blob/b875c3df6f3fa8ae7294be02b4c2e45cc9fae1dc/README.md) | [`b875c3d`](https://github.com/SafetyMP/Healthcare-Data-Exchange/commit/b875c3df6f3fa8ae7294be02b4c2e45cc9fae1dc) | Public |
| [Professional-Service-Automation](https://github.com/SafetyMP/Professional-Service-Automation/blob/abcb2f22d5e012495e96698c114081270f46a807/README.md) | [`abcb2f2`](https://github.com/SafetyMP/Professional-Service-Automation/commit/abcb2f22d5e012495e96698c114081270f46a807) | Public |
| [SOC-2](https://github.com/SafetyMP/SOC-2/blob/c95b88b2102928bacfe3aff85d08d388522ff8d6/README.md) | [`c95b88b`](https://github.com/SafetyMP/SOC-2/commit/c95b88b2102928bacfe3aff85d08d388522ff8d6) | Public |
| [commerce-reliability-kit](https://github.com/SafetyMP/commerce-reliability-kit/blob/6508ea26eec9253c16e47d91aa513bac707e9e9c/README.md) | [`6508ea2`](https://github.com/SafetyMP/commerce-reliability-kit/commit/6508ea26eec9253c16e47d91aa513bac707e9e9c) | Public |
| [corporate-site-harness](https://github.com/SafetyMP/corporate-site-harness/blob/bb6a1ae9389c5bfc7ef1e271739e1f73c11e41fb/README.md) | [`bb6a1ae`](https://github.com/SafetyMP/corporate-site-harness/commit/bb6a1ae9389c5bfc7ef1e271739e1f73c11e41fb) | Archived |
| [healthcare-policy](https://github.com/SafetyMP/healthcare-policy/blob/c15b3e916d6736ef136020bb7e6ed9bfc171003c/README.md) | [`c15b3e9`](https://github.com/SafetyMP/healthcare-policy/commit/c15b3e916d6736ef136020bb7e6ed9bfc171003c) | Public |

Financial Digital Twin's root README had not yet caught up with the governance workspace. Its [connected-workspace guide](https://github.com/SafetyMP/Financial-Digital-Twin-Compliance/blob/4003b94487ebc59bbd63fbdf93b316572e4b093d/docs/governance-integration.md) and merged [PR #272](https://github.com/SafetyMP/Financial-Digital-Twin-Compliance/pull/272) establish the newer implementation. The guide's historical statement that implementation was not merged is superseded by that merge. The profile distinguishes the synthetic Pages demo from the connected development application; it does not claim production deployment.

Other material corrections include APS's guided investigation, FidusGate's operator console and receipt demo, SOC-2's local GitHub assessment workspace, the EHS corporate application, and the healthcare and HR browser experiences. The policy mirror remains a supporting repository; Corporate/Site Harness is explicitly archived.

## Editorial choices

Five featured projects provide different entry points into agent risk, operational accountability, authorization, financial review, and integration reliability. The remaining public work stays discoverable in a compact directory. Project-level setup, test counts, releases, and detailed limitations remain with their owning repositories.

The structure follows GitHub's [profile portfolio guidance](https://docs.github.com/en/account-and-profile/tutorials/using-your-github-profile-to-enhance-your-resume) and [profile README requirements](https://docs.github.com/en/account-and-profile/how-tos/profile-customization/managing-your-profile-readme). It uses a brief introduction, clear project purposes, direct demo/source links, and a contact path. There is no generated activity feed or third-party stats dependency.

This repository controls profile content. Account biography, social links, and pinned repositories are separate settings. A suitable pin shortlist is the five featured projects; pins were not changed by this repository update.

## Verification boundary

Source review establishes what the public repositories document and implement. Link availability and Markdown rendering are separate presentation checks. Neither establishes that every demo interaction, backend, security control, or product test passes. Product suites and connected deployments are outside this documentation update.

For this refresh, independent documentation review found no blocking issues. GitHub's Markdown renderer preserved the five featured projects, six-row directory, and all README links; local document targets resolved and `git diff --check` passed. All 64 existing GitHub, GitHub Docs, and demo destinations returned HTTP 200. LinkedIn returned its automated-access status 999, so the existing contact URL was retained without claiming automated verification. The newly added source-notes page is verified after publication.

For future refreshes, follow [Contributing](../CONTRIBUTING.md), recheck public visibility and archive status, and update this snapshot only after reconciling the inventory.

