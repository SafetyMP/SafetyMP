# Audience audit of the proposed demos

**November 22, 2026.** Across ten professions, the earlier demos repeatedly asked people to read a prepared case, choose a response and inspect an explanation. Several also sent the visitor from a short technical introduction into the previous dashboard.

APS provides a useful comparison. A buyer can keep the order fixed, change the release time and trace what happens. For the proposed demos we asked three questions. What would this person actually produce at work? Which source records could change their decision? Can a second attempt leave them with a materially different outcome they can explain?

These findings come from the branch implementations and their exercised examples. The final column gives an unfamiliar task for a future practitioner session. Engagement, transfer to a new case and financial benefit still require observation with the intended audience. The [field guide](demo-field-guide.md) contains the corresponding screens, review links and industry sources.

## Floor, storefront and payroll

| Project and audience | Change observed in the proposed branch | Task for a practitioner |
| --- | --- | --- |
| **Autonomous EHS Management** · shift supervisor | Sending receiving-shift observations to the CAPA reviewer prompts a request for evidence from dispatch. Checking the dispatch crossing leaves the staging area unresolved. At dispatch staging the worker reports an obstructed walkway. The dispatch lead then owns a response and re-observation. Each additional stop costs ten illustrative minutes. | An action is due at handover. With time for two stops, what would you check and what work would you give the incoming shift? |
| **Commerce Reliability Kit** · inventory operations lead | With eight sellable units, three pickups and eight online requests, a cap of six accepts six online orders and leaves one unfilled. Lowering the cap to four fills the four online promises and leaves one sellable unit. A gross count alone leaves fulfillment unknown. | The same SKU appears under two different quantity labels. How much would you offer customers, and what evidence would make you revise it? |
| **HR-ERP** · payroll manager | Two waivers clear the exception queue while Casey still lacks a payment instruction. Checking the November 1 effective record and retrying just that employee puts all three employees on the register. Choosing a prior-period instruction and future-dated pay record instead consumes 17 simulated minutes and creates no instruction. | A new starter asks whether they will be paid in this run. What records would let you answer, who owns the next step, and what changes if cutoff passes? |

## Client and treasury finance

| Project and audience | Change observed in the proposed branch | Task for a practitioner |
| --- | --- | --- |
| **Professional Service Automation** · project accountant and engagement manager | Moving the July cutoff back to the 24th produces a $5,000 invoice and carries $1,320 of WIP. Including the late work instead triggers a simulated client query on $1,320 after the invoice is issued. Voiding and recutting exposes how the underlying source rows move. | The project manager wants to invoice all approved July time. What would you release now and what would you ask the client to confirm? |
| **Financial Digital Twin** · bank treasury and payments operations | With a delayed $35m receipt and no credit line, releasing the customer batch early settles margin 35 minutes late. Holding that batch to 10:00 and pledging $40m instead keeps margin and securities on time, uses $15m peak credit and delays the customer batch five minutes. | A receipt is late and two obligations have deadlines. Which payment would you move, what would you pledge, and how would you explain the trade-off to independent risk? |

## Referral and exchange operations

| Project and audience | Change observed in the proposed branch | Task for a practitioner |
| --- | --- | --- |
| **Asclepius** · referral coordinator | A coordination notice can be filed as correspondence. Filing the consultant letter against its earlier request for the same person gives that request a receipt while the current referral still needs follow-up. The next shift inherits the resulting register. | You inherit two open referrals for one person and three pieces of correspondence. What can you file, and what should the next coordinator still chase? |
| **Healthcare Data Exchange** · exchange privacy and data steward | For DX-104, removing the requested name lets the steward stage just id and resourceType for a US derivative. Replaying the patient’s withdrawal invalidates that staged packet. The mirror’s release view compares bundle digests. Only observations at a receiving gateway can establish when enforcement changed there. | A recipient asks for identifiers alongside a derivative record. Prepare a response, then explain what evidence you need if the patient changes their instructions. |

## Delegated work and assurance

| Project and audience | Change observed in the proposed branch | Task for a practitioner |
| --- | --- | --- |
| **CorpOS** · platform governance lead | Six recorded requests stay fixed. Requiring human review for handoffs and denying restarts changes three dispositions on replay. Two handoffs enter review and the restart is denied. The platform lead can inspect the affected requests before filing a recommendation. | You have been asked to reduce the approval queue for routine work. Which change would you recommend after replay, and which request would make you narrow it? |
| **FidusGate** · incident investigator | The ticket copy claiming an allow decision fails verification. The archived denial verifies. Adding both file snapshots documents a content change, but leaves the writer unidentified. Removing the snapshots reopens the request for that evidence. | A tool user disputes a denial and points to a changed permission file. What can a second investigator conclude from your case file, and what still needs investigation? |
| **SOC-2** · assurance preparer and review manager | For D-042 two pre-merge approval events came from one reviewer. The second distinct reviewer acted after merge, producing a deviation. Missing approval evidence for D-044 stays an open request. Retrieving the archive reveals the matching change for D-043 and returns the formerly open row for revision. | A customer asks whether October production changes met the review rule. Which rows can you support, and what would you ask the change owner to investigate? |

## What the technical section contains

Each public technical entry is a component reference. A reviewer can inspect the implementation behind a business result without repeating the case. The source links below point to the proposed revision.

| Project | Technical entry |
| --- | --- |
| **Autonomous EHS Management** | Follow one CAPA verification through the permission check, allowed state transition and PostgreSQL transaction that records its verifier and audit event. [Technical entry](https://github.com/SafetyMP/Autonomous-EHS-Management/blob/9f624cb37ebf2af123d6c95abd174b996a72e9b4/demo/index.html) |
| **Commerce Reliability Kit** | The importers normalize captures, the deterministic core checks policy and evidence, and the reporting package renders results. Checkout demand belongs to the browser exercise. [Technical entry](https://github.com/SafetyMP/commerce-reliability-kit/blob/40d95f1da53451b0f0505c01dd9d6c083ae41f94/apps/demo/src/App.tsx) |
| **HR-ERP** | The run service, exception register, period lifecycle and authorization route show why waiving an exception and generating a payment instruction are different operations. [Technical entry](https://github.com/SafetyMP/HR-ERP/blob/65aa833fd79cd8798ccfc5356d781b6730a9b5b3/demo/app/component-reference.tsx) |
| **Professional Service Automation** | Invoice assembly, source transitions, Prisma storage and a database-free proof explain why voiding releases the draft’s WIP and issuing consumes it. [Technical entry](https://github.com/SafetyMP/Professional-Service-Automation/blob/c140e390e36d5f61605d7d0f6c4ab41b41d993bf/src/app/case/technical/page.tsx) |
| **Financial Digital Twin** | The settlement replay runs in the browser. Separate entries trace connected monitoring through Kafka and Flink, PostgreSQL review history and the audit service. [Technical entry](https://github.com/SafetyMP/Financial-Digital-Twin-Compliance/blob/6dc4d9778aa81405e2986aa7d2fa6e1494ed6a8b/apps/governance-console/src/app/workspace/page.tsx) |
| **Asclepius** | Four entries trace fixture identity, practice-desk state, the teaching validator and the separate Hono API. Filing a document updates the practice register. [Technical entry](https://github.com/SafetyMP/Asclepius/blob/32756812601dd43fc6376eef8f6a44992dc2308f/web/src/app/workspace/page.tsx) |
| **Healthcare Data Exchange** | The compact reference discloses how the browser stages a fixture, how the local gateway enforces policy and which endpoint observations can establish withdrawal timing. [Technical entry](https://github.com/SafetyMP/Healthcare-Data-Exchange/blob/28ad9a9bded567024c28fc5a669e26f3880c0f01/web/src/components/clinical/pilot-case.tsx) |
| **CorpOS** | The company-day script, policy gateway, counterfactual replay and linked audit receipts explain how the browser produces a comparison without executing a tool. [Technical entry](https://github.com/SafetyMP/CorpOS/blob/7d06086ee3663a1a780e6f79675c67317fa24358/apps/console/src/TechnicalGuide.tsx) |
| **FidusGate** | Gateway authorization, fixture-key signature verification, synthetic records and corroborating evidence set the limits of what an investigator can attribute. [Technical entry](https://github.com/SafetyMP/FidusGate/blob/7e1140a03f577d97041e7a03c8b031be64facef5/apps/admin-dashboard/src/ReceiptConsole.tsx) |
| **SOC-2** | The Python collector, OPA/Rego evaluator, local viewer and fixture exporter explain which three configuration checks the real assessment performs. The workpaper adds fictional operating records. [Technical entry](https://github.com/SafetyMP/SOC-2/blob/5612187d7b604fc1736061a470d6c8ba46db1e3d/demo/app.js) |

## Observing a session

Recruit someone who does the work and someone who decides whether to fund it. Give the practitioner the task in the final column without naming the control or revealing the expected result. Watch which evidence they seek, where they hesitate, whether they can explain the consequence and whether they voluntarily try a different path. Ask them to repeat with an unfamiliar record. Ask the sponsor which existing process they would compare, what they would measure and which result would make them stop the pilot. Record assistance, successful completion and the participant’s own explanation separately. [GOV.UK guidance on moderated usability testing](https://www.gov.uk/service-manual/user-research/using-moderated-usability-testing)
